# Strict

[![pub package](https://img.shields.io/pub/v/strict?style=flat-square)](https://pub.dev/packages/strict)

A heavily opinionated analysis_options for Dart & Flutter projects with strict - but
justified - lint rules. Sometimes being [pedantic](https://github.com/google/pedantic) is not enough.

### Why and How

There are plenty of rules that pedantic package doesn't take full advantage of and may be
useful for other projects, like teams that have fewer people, or just personal preference
of being even more strict than usual with linting rules.

While this is a stricter approach, this obviously is open to any changes, suggestions and
discussions - each rule deserves a why, so when the `dart/linter` comments are not enough or
disagreed with, a more specific comment is added above each rule in `lib/analysis_options.yaml`.

All rules are updated on a regular basis - more specifically when a new relevant release
adds and/or removes rules in the [dart linter](https://github.com/dart-lang/linter) library.
These updates are made and documented in `lib/all_rules.yaml`, just like a clone that we manually
diff from the dart linter's repo.

### Usage

Add this package to your `dev_dependencies` in your `pubspec.yaml`:

```yaml
dev_dependencies:
  strict: ^1.0.0
```

and the following to your `analysis_options.yaml` (create one in the root of your project if you don't
have it yet):

```yaml
  include: package:strict/analysis_options.yaml
```
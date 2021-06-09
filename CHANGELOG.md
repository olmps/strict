## Unreleased

- Disabled `avoid_annotating_with_dynamic`.

## 1.1.0

- Added `library_private_types_in_public_api`, `prefer_null_aware_method_calls`, `require_trailing_commas` and
`use_build_context_synchronously` (all unreleased yet);
- Disabled `one_member_abstracts`.

## 1.0.0

First stable release of `strict`.

- Added `deprecated_consistency`, `use_if_null_to_convert_nulls_to_bools` and `use_named_constants` (all unreleased
yet);
- Removed `avoid_as`.

## 1.0.0-nullsafety.1
- Enabled `implicit-casts`;
- Disabled `avoid_as`, `prefer_expression_function_bodies`, `sort_pub_dependencies` and
`use_key_in_widget_constructors`.

## 1.0.0-nullsafety.0

Addressed the remaining TODOs, while improving the description of some decisions. Also fixing the bad version naming.

- Updated `dart-lang/linter` rules up to version `0.1.129`: added rule `avoid_dynamic_calls` (experimental, still not
enabled);
- Enabled `avoid_annotating_with_dynamic` - which was erroneously disabled (misconception of what it really did);
- Enabled strong-mode rule of `implicit-dynamic` to `false`;
- Enabled `cast_nullable_to_non_nullable`, `tighten_type_of_initializing_formals`, `unnecessary_null_checks` and 
`unnecessary_nullable_for_final_variable_declarations` due to NNBD;
- Disabled `avoid_returning_null`, `avoid_returning_null_for_future` and `avoid_returning_null_for_void` due to NNBD;
- Customized `avoid_as` to show a `warning`, with the according explanation to why;

Contains all rules up to version `0.1.127` of `dart-lang/linter`, with pending TODOs (non-critical) in the
`analysis_options.yaml`.

## 1.0.0-0

First version of `strict`.

Contains all rules up to version `0.1.127` of `dart-lang/linter`, with pending TODOs (non-critical) in the
`analysis_options.yaml`.
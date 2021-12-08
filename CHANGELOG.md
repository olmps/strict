## 1.3.0

- Added references to unreleased rules: `avoid_final_parameters`, `no_leading_underscores_for_library_prefixes`,
`no_leading_underscores_for_local_identifiers`, `secure_pubspec_urls`, `sized_box_shrink_expand`,
`unnecessary_constructor_name`, `use_decorated_box`
- Enabled `avoid_dynamic_calls`, `avoid_multiple_declarations_per_line`, `depend_on_referenced_packages`,
`deprecated_consistency`, `eol_at_end_of_file`, `library_private_types_in_public_api`, `noop_primitive_operations`,
`prefer_null_aware_method_calls`, `require_trailing_commas`, `use_build_context_synchronously`,
`use_if_null_to_convert_nulls_to_bools`, `use_named_constants` and `use_test_throws_matchers`.
- Updated explanations on `avoid_final_parameters` and `prefer_final_parameters`.

## 1.2.0

- Added references to unreleased rules: `depend_on_referenced_packages`, `noop_primitive_operations`,
`prefer_final_parameters` and `use_test_throws_matchers`.
- Disabled `avoid_annotating_with_dynamic`.

## 1.1.0

- Added references to unreleased rules: `library_private_types_in_public_api`, `prefer_null_aware_method_calls`, 
`require_trailing_commas` and `use_build_context_synchronously`;
- Disabled `one_member_abstracts`.

## 1.0.0

First stable release of `strict`.

- Added references to unreleased rules: `deprecated_consistency`, `use_if_null_to_convert_nulls_to_bools` and
`use_named_constants`;
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
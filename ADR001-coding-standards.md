Coding Standards
====

This **Architecture Decision Record** defines the coding standards to apply to all the
code in this repository.

PHP-CS-Fixer rules
---

The following rules should be applied:
* `@PHP81Migration`
* `@PHP80Migration:risky`
* `@PHPUnit84Migration:risky`
* `@PSR1`
* `@PSR12`
* `@PhpCsFixer`
* `@Symfony`
* `ternary_to_elvis_operator`
* `set_type_to_cast`
* `self_accessor`
* `psr_autoloading`
* `php_unit_test_annotation`, with option `['style' => 'annotation']`
* `php_unit_set_up_tear_down_visibility`
* `php_unit_construct`
* `no_useless_sprintf`
* `no_homoglyph_names`
* `native_function_invocation`
* `native_constant_invocation`
* `modernize_types_casting`
* `logical_operators`
* `is_null`
* `function_to_constant`
* `fopen_flag_order`
* `error_suppression`
* `ereg_to_preg`
* `dir_constant`

# KOSL VS Code Extension Changelog

## v0.3.0

* **Added** improved TextMate grammar with better semantic highlighting.
* **Added** highlighting support for:

  * arrays
  * nested objects
  * semver values
  * punctuation
  * escaped strings
  * booleans
  * null values
* **Added** support for `Cargo.kosl` file recognition.
* **Added** improved `language-configuration.json` behavior.
* **Added** bracket pair colorization support.
* **Added** auto indentation rules.
* **Added** folding region support using `#region` and `#endregion`.
* **Added** extension marketplace icon support.
* **Added** `CONTRIBUTING.md`.
* **Added** `SECURITY.md`.
* **Added** improved README documentation.
* **Improved** file icon support for `.kosl`.
* **Improved** syntax scope compatibility across VS Code themes.
* **Improved** extension metadata and configuration structure.
* **Improved** command registration and activation events.
* **Fixed** string parsing edge cases.
* **Fixed** numeric tokenization inconsistencies.
* **Fixed** highlighting inconsistencies for nested structures.

## v0.2.1

* **Added** `README.md` and `CHANGELOG.md`.

## v0.2.0

* **Added** `icon-theme.json` file for correct rendering of icons in VS Code.
* **Fixed** icon rendering.
* **Fixed** bug where syntaxes were not being highlighted properly.

## v0.1.0

* **Initial Release**
* **Added** custom language association for `.kosl` files.
* **Added** robust TextMate grammar (`kosl.tmLanguage.json`) for precise semantic highlighting of assignments, numbers, booleans, and nested structures.
* **Added** auto-closing bracket configurations for `()`, `[]`, and `""`.
* **Added** SVG file icon support for the VS Code file explorer.

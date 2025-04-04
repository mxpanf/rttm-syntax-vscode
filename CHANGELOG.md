# Changelog

## [0.2.0] — 2025-04-04
### Added
- Support for the 11th field, an arbitrary quoted string ("...") at the end of each line
- The backlight is like `string.quoted.double.rttm`
- All RTTM types have been updated (`SPEAKER`, `LEXEME`, `NON-LEX`, …)

### Changed
- Improved detection of invalid strings (`invalid.illegal.rttm`), now correctly catches strings with less than 10 required fields
- Updated grammar for a more flexible structure

## [0.1.1] - 2025-04-04
### Added
- Updated grammar to support incomplete RTTM lines (accepts 1 to 10 tokens).
- Integrated snippet support for auto-insertion of `<NA>` placeholder. Typing `~` now triggers the insertion of `<NA>` placeholder.
- Inline snippet suggestions enabled via editor settings.
### Changed
- Modified regex in the grammar for more flexible token matching.
- Improved syntax highlighting behavior during real-time editing.
### Fixed
- Resolved issues where syntax highlighting was delayed until a full line was entered.

## [0.1.0] - 2025-04-03
### Added
- Initial release of RTTM Language extension.
- Basic syntax highlighting for complete RTTM lines with 10 required fields.
- Support for comments using the `#` symbol.

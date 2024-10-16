# Changelog

All notable changes to the "python-docstring-highlighter" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.5]

### Added

- Split `numpy` variable type and modifiers (e.g. int and optional) into separate scopes.

### Changed

- Update the tests with the latest version of the examples.
- Format files with consistent whitespace.

## [0.2.4]

### Added

- `numpy` variable detection now recognizes types with their modules (e.g. `numpy.ndarray`).
- Colorization for multi-word capitalized sections (e.g., `See Also`).

### Fixed

- Highlighting for complex type annotations (e.g., `Sequence[str]`).
- Improved support for NumPy-style multiple parameters (e.g., `param1, param2 : int`).
- Sphinx-style return type highlighting (e.g., `:rtype: int`).

## [0.2.3]

### Changed

- Base heading pattern end token to match end of line.
- Base default placeholder style for interpreted text expression to `string.regexp`.
- `google` and `numpy` variable pattern to accept a leading hyphen and a first uppercase character.

## [0.2.2]

### Changed

- VS Code minimum required version to `1.65.2`.

## [0.2.1]

### Changed

- Syntax highlighting for variables in `google`, `numpy`, and `sphinx` syntaxes.

## [0.2.0]

### Added

- Documentation.
- Raw docstring scope support.
- Renamed extension specific scopes to have a more consistent naming convention.

### Changed

- `google`, `numpy`, and `sphinx` variable regex pattern.
- Tests.

## [0.1.0]

### Added

- Initial release.

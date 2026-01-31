# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2026-01-31

### Added
- Forked from chrmina/CakeSpreadsheet
- Active maintenance and versioning
- CHANGELOG.md file

### Fixed
- **BREAKING FIX**: Deprecation warnings for CakePHP 3.8+
  - Changed `Event::subject()` to `Event::getSubject()`
  - Changed `Component::config()` to `Component::setConfig()`

### Changed
- Updated package name to `jdominguezpaz/cakespreadsheet`
- Updated repository URLs
- Enhanced README with fork information and key changes
- Updated composer.json with maintainer information
- Clarified PHP requirement to >= 5.6.0
- Clarified CakePHP requirement to ^3.6

## Historical (chrmina/CakeSpreadsheet)

This package is a fork of [chrmina/CakeSpreadsheet](https://github.com/chrmina/CakeSpreadsheet), which was originally modified from [dakota/CakeExcel](https://github.com/dakota/CakeExcel) to use PHPSpreadsheet instead of the obsolete PHPExcel library.

[Unreleased]: https://github.com/jdominguezpaz/CakeSpreadsheet/compare/1.0.0...HEAD
[1.0.0]: https://github.com/jdominguezpaz/CakeSpreadsheet/releases/tag/1.0.0

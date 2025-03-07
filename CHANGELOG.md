# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.2] - 2023-03-13

### Changed

- Update various dependencies to fix some known vulnerabilities.

## [1.3.1] - 2020-05-10

### Fixed

- GitHub Actions does not support sequences as input

## [1.3.0] - 2022-05-09

### Added

- Add support for ignores (#1)

## [1.2.0] - 2020-05-07

### Fixed

- Compatibility with latest `cargo-audit == 0.12` JSON output (#115) 
- Do not fail check if no critical vulnerabilities were found when executed for a fork repository (closes #104)

## [1.1.0]

### Fixed

- Invalid input properly terminates Action execution (#1)
- Compatibility with new `cargo-audit` JSON output (#70)

## [1.0.0] - 2019-10-09

### Added

- First public version

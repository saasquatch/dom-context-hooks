# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.3] - 2024-02-14

### Fixed

- Race condition where initialContextValue ref object may not exist before being set has been fixed

## [1.0.2] - 2023-04-20

### Updated

- Updated license copyright to be in line with SaaSquatch open-source policy

## [1.0.1] - 2021-10-25

### Updated

- Catches error messages if the context listener is undefined or unable to start

## [1.0.0] - 2021-04-21

### Added

- Initial Release
- Exported hooks:
  - createContext
  - useDomContext
  - useDomContextState

[unreleased]: https://github.com/saasquatch/dom-context-hooks/compare/dom-context-hooks@1.0.3...HEAD
[1.0.3]: https://github.com/saasquatch/dom-context-hooks/releases/tag/dom-context-hooks@1.0.3
[1.0.2]: https://github.com/saasquatch/dom-context-hooks/releases/tag/dom-context-hooks@1.0.2
[1.0.1]: https://github.com/saasquatch/dom-context-hooks/releases/tag/dom-context-hooks@1.0.1
[1.0.0]: https://github.com/saasquatch/dom-context-hooks/releases/tag/dom-context-hooks@1.0.0

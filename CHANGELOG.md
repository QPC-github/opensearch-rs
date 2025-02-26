# CHANGELOG
Inspired from [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

### Added
- Adds Github workflow for changelog verification ([#89](https://github.com/opensearch-project/opensearch-rs/pull/89))
- Adds Github workflow for unit tests ([#112](https://github.com/opensearch-project/opensearch-rs/pull/112))
- Adds support for OpenSearch Serverless ([#96](https://github.com/opensearch-project/opensearch-rs/pull/96))

### Dependencies
- Bumps `simple_logger` from 2.3.0 to 4.0.0
- Bumps `serde_with` from ~1 to ~2
- Bumps `textwrap` from ^0.15 to ^0.16
- Bumps `base64` from ^0.13 to ^0.20 ([#95](https://github.com/opensearch-project/opensearch-rs/pull/95), [#105](https://github.com/opensearch-project/opensearch-rs/pull/105))
- Bumps `aws-*` from >=0.10 to >=0.53 ([#108](https://github.com/opensearch-project/opensearch-rs/pull/108))
- Bumps `toml` from 0.5.6 to 0.7.1
- Bumps `sysinfo` from 0.26.4 to 0.28.0
- Bumps `syn` from ~1.0 to ~2.0

### Changed
- Updates users guide with complete examples ([#114](https://github.com/opensearch-project/opensearch-rs/pull/114))

### Deprecated

### Removed

### Fixed
- [BUG] cargo make test fails out of the box ([#117](https://github.com/opensearch-project/opensearch-rs/pull/117))
- Update CI to run cargo make test fails out of the box ([#120](https://github.com/opensearch-project/opensearch-rs/pull/120))
- Add cargo cache to Github actions to speed up builds ([#121](https://github.com/opensearch-project/opensearch-rs/pull/121))
- [BUG] Updated Point-in-Time request builder to support current API ([#136](https://github.com/opensearch-project/opensearch-rs/pull/136))

### Security

[Unreleased]: https://github.com/opensearch-project/opensearch-rs/compare/2.0...HEAD
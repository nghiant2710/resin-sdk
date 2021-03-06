# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [2.3.1] - 2015-07-29

### Changed

- Fix undefined Authorization header issue.
- Fix HTTP request body issue in auth module.

## [2.3.0] - 2015-07-27

### Added

- Refresh token in an interval.

### Removed

- Remove deprecated `device.register()`.

## [2.2.0] - 2015-07-03

### Added

- Implement `resin.models.device.getLocalIPAddresses()`.

## [2.1.0] - 2015-07-01

### Changed

- Upgrade `resin-settings-client` to v1.4.0.

## [2.0.0] - 2015-06-29

### Added

- Implement `resin.logs.history()`.
- Implement `resin.models.device.register()`.
- Implement `resin.settings`.
- Start making use of a CHANGELOG.
- Improve unit testing.
- Add promise support.
- Check that a device exists before attempting `rename` operation.
- Reference devices by `uuid` instead of by name.
- Markdown JSDoc documentation in `DOCUMENTATION.md`.

### Changed

- Change interface and internal workings of `resin.logs.subscribe()`.
- "get all" functions now return an empty array if no resources instead of yielding an error.
- Update JSDoc annotations to use promises.

### Removed

- Remove HTML generated JSDoc documentation.

[2.3.1]: https://github.com/resin-io/resin-sdk/compare/v2.3.0...v2.3.1
[2.3.0]: https://github.com/resin-io/resin-sdk/compare/v2.2.0...v2.3.0
[2.2.0]: https://github.com/resin-io/resin-sdk/compare/v2.1.0...v2.2.0
[2.1.0]: https://github.com/resin-io/resin-sdk/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/resin-io/resin-sdk/compare/v1.8.0...v2.0.0

# Changelog

All notable changes to this project will be documented in this file.

## [0.3.2] - 2019-01-31
### Fixed
- Return `ConduitError` with proper status code when Phabricator fails with
  HTML output and client can not parse JSON.

## [0.3.1] - 2019-01-08
### Added
- Added `Email` value to `entities.User` struct for response to `user.query`
  endpoint.

## [0.3.0] - 2018-11-19
### Changed
- Changed import paths from `etcinit` to `uber`.
- Updated vesions of dependencies.

# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0]
## [0.1.0-beta.3]
### Added
- More model unit tests to confirm expected behavior when marshalling, checking equality, and calculating hash codes

### Changed
- Changed method signatures of API client interface to expose CompletionStage instead of directly exposing a CompleteableFuture

## [0.1.0-beta.2]
### Added
- Added base ApiResponse interface and updated all existing responses to inherit from it
- Added list of site ids associated with api response to returned value from client

## [0.1.0-beta]
### Added
-  Added javadoc comment blocks to interfaces
-  Support for api commands to fetch the api current version, supported versions, 
    and detailed energy report.
- Created CHANGELOG.md

## [0.1.0-alpha]
### Added
- Added support for the api commands to get site details and overview.

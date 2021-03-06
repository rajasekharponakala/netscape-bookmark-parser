# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [v1.1.0](https://github.com/shaarli/netscape-bookmark-parser/releases/tag/v1.1.0) - UNPUBLISHED
### Added
- Add `CHANGELOG.md`
- Enable Composer cache for Travis builds

### Fixed
- Keep Composer metadata in Git-generated archives


## [v1.0.1](https://github.com/shaarli/netscape-bookmark-parser/releases/tag/v1.0.1) - 2016-08-09
### Changed
- Mark this repository as being a friendly fork maintained by the Shaarli community
- Add/update CI badges

### Fixed
- Support exports from legacy Shaarli versions (i.e. before the export refactoring)


## [v1.0.0](https://github.com/shaarli/netscape-bookmark-parser/releases/tag/v1.0.0) - 2016-08-09
### Added
- Add unitary tests using [PHPUnit](https://phpunit.de/)
    - Browser dump coverage: Chromeium, Firefox, Internet Explorer
    - Web service dump coverage: Delicious, Shaarli Community
- Add [Travis CI](https://travis-ci.org/) automated builds
- Add PHP 5.3 compatibility (use `array()` instead of the short `[]` syntax)

### Changed
- let Git homogenize line endings to make tests portable
- update Composer/Packagist metadata
- refactor the parser as a class to help splitting logic and improve readability
    - better date format support
    - multi-line descriptions
    - refactor and simplify input sanitizing

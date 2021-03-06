# Change Log

All notable changes to this project will be documented in this file. This
project adheres to [Semantic Versioning](http://semver.org/), with the exception
that I'm using PEP440 to denote pre-releases.

## [0.4.1] - 2017-07-18

### Fixed

- A bug when using a new version of skyfield.


## [0.4.0] - 2017-06-24

### Added

- Added an enum type for the `caput.config`


## [0.3.0] - 2016-08-13

### Added

- This `CHANGELOG` file.
- A new module (`caput.time`) for converting between various time
  representations (UNIX, `datetime`, and Skyfield format), and for calculating
  celestial times, including Earth Rotation Angle, Local Stellar Angle, and
  Local Stellar Day.
- Added some helper routines for creating specific `Property` attributes to
  `caput.config`.

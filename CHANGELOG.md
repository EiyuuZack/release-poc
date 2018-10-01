# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.0] - 2018-10-01
### Additions
- Log multiple applications (one at a time) on Android by allowing to change host and application name [RNMT-1549](https://outsystemsrd.atlassian.net/browse/RNMT-1549)

### Changes
- Update Android Support Library to 26.1.0 [RNMT-1862](https://outsystemsrd.atlassian.net/browse/RNMT-1862)
- Update [cordova-outsystems-security](https://github.com/OutSystems/cordova-outsystems-security) dependency
- Update [cordova-outsystems-broadcaster](https://github.com/OutSystems/cordova-outsystems-broadcaster) dependency

## [1.2.4] - 2018-05-30
### Fixes
- Not accepting legitimate null values sent from the Platform [RNMT-1654](https://outsystemsrd.atlassian.net/browse/RNMT-1654)

## [1.2.3] - 2018-05-22
### Fixes
- Wrong timezone in log timestamp on iOS [RNMT-1639](https://outsystemsrd.atlassian.net/browse/RNMT-1639)

## [1.2.2] - 2018-04-11
### Fixes
- Crash on Android that would sometimes occur due to unexpected end of streams [RNMT-1550](https://outsystemsrd.atlassian.net/browse/RNMT-1550)
- Wrong handling on Android of dates using Arabic-Indic numerals instead of Arabic [RNMT-1551](https://outsystemsrd.atlassian.net/browse/RNMT-1551)

## [1.2.1] - 2018-03-22
### Fixes
- Crash on Android that would sometimes occur when sending logs to Service Center [RNMT-1394](https://outsystemsrd.atlassian.net/browse/RNMT-1394)

## [1.2.0] - 2018-03-12
### Changes
- Update [cordova-outsystems-security](https://github.com/OutSystems/cordova-outsystems-security) dependency

## [1.1.1] - 2018-03-09
### Changes
- Update [cordova-outsystems-broadcaster](https://github.com/OutSystems/cordova-outsystems-broadcaster) dependency

## 1.1.0 - 2018-02-21
### Additions
- Listen and react to events broadcast from [cordova-outsystems-broadcaster](https://github.com/OutSystems/cordova-outsystems-broadcaster), such as stop emitting when there is no network available

[1.3.0]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.3.0...HEAD
[1.3.0]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.2.4...1.3.0
[1.2.4]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.2.3...1.2.4
[1.2.3]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.2.2...1.2.3
[1.2.2]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.2.1...1.2.2
[1.2.1]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.1.1...1.2.0
[1.1.1]: https://github.com/OutSystems/cordova-outsystems-logger/compare/1.1.0...1.1.1

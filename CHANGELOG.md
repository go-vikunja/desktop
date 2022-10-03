# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

All releases can be found on https://code.vikunja.io/desktop/releases.

The releases aim at the api and frontend versions which is why there are missing versions.

## [0.19.2 - 2022-08-17]

### Dependencies

* *(deps)* Update dependency electron to v20.0.2 (#111)
* *(deps)* Update dependency electron to v20.0.3 (#112)
* *(deps)* Update dependency electron to v20.1.1 (#113)
* *(deps)* Update dependency electron to v20.1.2 (#114)
* *(deps)* Update dependency electron to v20.1.3 (#115)
* *(deps)* Update dependency electron to v20.1.4 (#116)
* *(deps)* Update dependency electron to v20.2.0 (#117)
* *(deps)* Update dependency electron to v21 (#118)
* *(deps)* Update dependency electron to v21.0.1 (#119)

### Features

* Add sponsor to readme (relm) ([5b4d5c7](5b4d5c784b4ea447ea928c8c9ee83a58b51f10f4))

### Miscellaneous Tasks

* Disable mac builds ([0563fb2](0563fb2ee5ae16357cdd9463be33ca3f3977c596))

## [0.19.0 - 2022-08-03]

### Dependencies

* *(deps)* Update dependency electron-builder to v22.13.1 (#61)
* *(deps)* Update dependency electron to v15.2.0 (#60)
* *(deps)* Update dependency electron to v15.3.0 (#63)
* *(deps)* Update dependency electron to v15.3.1 (#64)
* *(deps)* Update dependency electron to v15.3.2 (#66)
* *(deps)* Update dependency electron to v16 (#65)
* *(deps)* Update dependency electron to v16.0.1 (#67)
* *(deps)* Update dependency electron-builder to v22.14.5 (#68)
* *(deps)* Update dependency electron to v16.0.2 (#69)
* *(deps)* Update dependency electron to v16.0.3 (#71)
* *(deps)* Update dependency electron to v16.0.4 (#72)
* *(deps)* Update dependency electron to v16.0.5 (#73)
* *(deps)* Update dependency electron to v16.0.6 (#74)
* *(deps)* Update dependency electron to v16.0.7 (#75)
* *(deps)* Update dependency electron to v16.0.8 (#76)
* *(deps)* Update dependency electron to v17 (#77)
* *(deps)* Update dependency electron-builder to v22.14.13 (#78)
* *(deps)* Update dependency electron to v17.0.1 (#79)
* *(deps)* Update dependency electron to v17.1.0 (#80)
* *(deps)* Update dependency electron to v17.1.1 (#81)
* *(deps)* Update dependency electron to v17.1.2 (#82)
* *(deps)* Update dependency electron to v17.2.0 (#83)
* *(deps)* Update dependency electron to v17.3.0 (#84)
* *(deps)* Update dependency electron to v18 (#85)
* *(deps)* Update dependency electron to v18.0.1 (#86)
* *(deps)* Update dependency electron to v18.0.2 (#87)
* *(deps)* Update dependency electron to v18.0.3 (#88)
* *(deps)* Update dependency electron-builder to v23 (#89)
* *(deps)* Update dependency electron to v18.0.4 (#90)
* *(deps)* Update dependency electron to v18.1.0 (#91)
* *(deps)* Update dependency electron to v18.2.0 (#92)
* *(deps)* Update dependency electron to v18.2.2 (#93)
* *(deps)* Update dependency electron to v18.2.3 (#94)
* *(deps)* Update dependency electron to v18.2.4 (#95)
* *(deps)* Update dependency electron to v18.3.1 (#96)
* *(deps)* Update dependency electron to v19 (#97)
* *(deps)* Update dependency electron to v19.0.2 (#98)
* *(deps)* Update dependency electron to v19.0.3 (#99)
* *(deps)* Update dependency electron to v19.0.4 (#100)
* *(deps)* Update dependency electron to v19.0.6 (#101)
* *(deps)* Update dependency electron-builder to v23.1.0 (#102)
* *(deps)* Update dependency electron to v19.0.7 (#104)
* *(deps)* Update dependency electron to v19.0.8 (#105)
* *(deps)* Update dependency electron to v19.0.9 (#106)
* *(deps)* Update dependency electron to v19.0.10 (#107)
* *(deps)* Update dependency electron-builder to v23.3.3 (#108)
* *(deps)* Update dependency electron to v20 (#109)
* *(deps)* Update dependency electron to v20.0.1 (#110)

### Miscellaneous Tasks

* *(ci)* Use latest s3 plugin
* *(ci)* Sign drone config

### Other

* *(other)* Update dependency electron to v14.0.1 (#58)
* *(other)* Update dependency electron to v15 (#59)

## [0.18.0 - 2021-09-05]

### Added 

* Add drone pipeline for PR
* Enable mac builds

### Changed

* Cleanup
* Fix sed for macos
* Install yarn on mac
* Only upload .dmg files for macos builds
* Sign drone config

### Dependency Updates

* Update dependency electron-builder to v22.11.7 (#45)
* Update dependency electron to v13.0.1 (#41)
* Update dependency electron to v13.1.0 (#42)
* Update dependency electron to v13.1.1 (#43)
* Update dependency electron to v13.1.2 (#44)
* Update dependency electron to v13.1.3 (#46)
* Update dependency electron to v13.1.4 (#47)
* Update dependency electron to v13.1.5 (#48)
* Update dependency electron to v13.1.6 (#49)
* Update dependency electron to v13.1.7 (#50)
* Update dependency electron to v13.1.8 (#51)
* Update dependency electron to v13.1.9 (#52)
* Update dependency electron to v13.2.0 (#53)
* Update dependency electron to v13.2.1 (#54)
* Update dependency electron to v13.2.2 (#55)
* Update dependency electron to v13.2.3 (#56)
* Update dependency electron to v13 (#39)
* Update dependency electron to v14 (#57)


## [0.17.0 - 2021-05-20]

For a list of changes in this release, see [the frontend changelog](https://kolaente.dev/vikunja/frontend/releases/tag/v0.17.0).

### Added

* Add darwin release pipeline
* Add pipeline type

### Changed

* Change release target path for unstable releases
* Change version to download to unstable
* Disable the mac builds for now
* Move release steps in one pipeline step for macos
* Switch main branch to main
* Switch to wine-mono for building

### Fixed

* Fix missing application icon on Linux. (#19)
* Fix version in package.json

### Dependency Updates

* Update dependency electron-builder to v22.10.5 (#23)
* Update dependency electron-builder to v22.11.1 (#31)
* Update dependency electron-builder to v22.11.2 (#33)
* Update dependency electron-builder to v22.11.3 (#34)
* Update dependency electron-builder to v22.11.4 (#35)
* Update dependency electron-builder to v22.11.5 (#37)
* Update dependency electron to v11.2.0 (#12)
* Update dependency electron to v11.2.1 (#14)
* Update dependency electron to v11.2.2 (#20)
* Update dependency electron to v11.2.3 (#21)
* Update dependency electron to v11.3.0 (#22)
* Update dependency electron to v12.0.1 (#25)
* Update dependency electron to v12.0.2 (#26)
* Update dependency electron to v12.0.3 (#27)
* Update dependency electron to v12.0.4 (#28)
* Update dependency electron to v12.0.5 (#29)
* Update dependency electron to v12.0.6 (#30)
* Update dependency electron to v12.0.7 (#32)
* Update dependency electron to v12.0.8 (#36)
* Update dependency electron to v12.0.9 (#38)
* Update dependency electron to v12 (#24)

## [0.16.0 - 2021-01-10]

For a list of changes in this release, see [the frontend changelog](https://kolaente.dev/vikunja/frontend/releases/tag/v0.16.0).

### Added

* Add yarn cache to drone
* Configure Renovate (#1)

### Changed

* Change license to GPLv3
* Pin dependencies (#2)
* Update dependency electron to v10.1.5 (#3)
* Update dependency electron to v11.0.1 (#5)
* Update dependency electron to v11.0.2 (#6)
* Update dependency electron to v11.0.3 (#7)
* Update dependency electron to v11.0.4 (#8)
* Update dependency electron to v11.1.0 (#9)
* Update dependency electron to v11.1.1 (#10)
* Update dependency electron to v11 (#4)

## [0.15.0 - 2020-10-19]

First initial release.

For a list of changes in this release, see [the frontend changelog](https://kolaente.dev/vikunja/frontend/releases/tag/v0.15.0).


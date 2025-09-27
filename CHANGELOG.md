# Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.3.0](https://github.com/rahuliyer95/homebridge-smartrent/compare/v1.2.7...v1.3.0) (2025-09-27)

### Features

* **client:** add heartbeat for WebSocket to fix constant connection closure ([1d2744e](https://github.com/rahuliyer95/homebridge-smartrent/commit/1d2744efefbfb7602e2790917a05d17318dbd08c))
* **client:** add `axio-retry` to handle retry errors ([77c5a5c](https://github.com/rahuliyer95/homebridge-smartrent/commit/77c5a5c58e9e8d6e8c728ce49bd030949fa159a0))

### Dependencies

* **deps:** bump axios from 1.11.0 to 1.12.2 ([#316](https://github.com/rahuliyer95/homebridge-smartrent/issues/316)) ([d7af3ae](https://github.com/rahuliyer95/homebridge-smartrent/commit/d7af3ae0c847fa25e9ed12f8eb0fe8fdb3cd3bfe))

## [1.2.7](https://github.com/rahuliyer95/homebridge-smartrent/compare/v1.2.6...v1.2.7) (2025-08-06)

### Bug Fixes

* **client:** improve WebSocket error logging ([193f71c](https://github.com/rahuliyer95/homebridge-smartrent/commit/193f71cb0096dad7a5c2fed2c356d2a3f3c586e6))

## [1.2.6](https://github.com/rahuliyer95/homebridge-smartrent/compare/v1.2.5...v1.2.6) (2025-08-02)

### Bug Fixes

* update app version to `4.5.3` to resolve 403 errors ([a0ab7d9](https://github.com/rahuliyer95/homebridge-smartrent/commit/a0ab7d94d593d634ae43702c1b215749e5ec7bed))

## [1.2.5](https://github.com/rahuliyer95/homebridge-smartrent/compare/v1.2.4...v1.2.5) (2025-07-29)

### Dependencies

* **deps:** bump @homebridge/plugin-ui-utils from 2.0.2 to 2.1.0 ([#245](https://github.com/rahuliyer95/homebridge-smartrent/issues/245)) ([4c7e43f](https://github.com/rahuliyer95/homebridge-smartrent/commit/4c7e43f90aa567b6be2b3ee52c0bb8a3198cb50a))
* **deps:** bump axios from 1.10.0 to 1.11.0 ([#283](https://github.com/rahuliyer95/homebridge-smartrent/issues/283)) ([41fc200](https://github.com/rahuliyer95/homebridge-smartrent/commit/41fc20015357091b7dd4a8470905a35a11b52d40))
* **deps:** bump axios from 1.9.0 to 1.10.0 ([#252](https://github.com/rahuliyer95/homebridge-smartrent/issues/252)) ([d3d7038](https://github.com/rahuliyer95/homebridge-smartrent/commit/d3d7038395c93c22573c7f87dbc9c8844e7f6406))
* **deps:** bump form-data from 4.0.0 to 4.0.4 ([#282](https://github.com/rahuliyer95/homebridge-smartrent/issues/282)) ([5d2b9d4](https://github.com/rahuliyer95/homebridge-smartrent/commit/5d2b9d4c0c275cb7cc8d24ac91d6b166355fdc6f))
* **deps:** bump ws from 8.18.2 to 8.18.3 ([#264](https://github.com/rahuliyer95/homebridge-smartrent/issues/264)) ([f8e42f5](https://github.com/rahuliyer95/homebridge-smartrent/commit/f8e42f5f25c5a80746a030cf9b78d17d968da6dd))

## [1.2.4](https://github.com/rahuliyer95/homebridge-smartrent/compare/v1.2.3...v1.2.4) (2025-06-08)

### Bug Fixes

* **thermostat:** handle `auto` mode in thermostat ([#244](https://github.com/rahuliyer95/homebridge-smartrent/issues/244)) ([1d90127](https://github.com/rahuliyer95/homebridge-smartrent/commit/1d901278d8195530b3a21ca04f0c6f683d1f0f55))

## [1.2.3](https://github.com/rahuliyer95/homebridge-smartrent/compare/v1.2.2...v1.2.3) (2025-06-07)

### Dependencies

* **deps:** bump ws from 8.18.1 to 8.18.2 ([#220](https://github.com/rahuliyer95/homebridge-smartrent/issues/220)) ([7478175](https://github.com/rahuliyer95/homebridge-smartrent/commit/7478175c1369eef77ec475c96df41dce366df0fd))

## [1.0.3](https://github.com/Burry/homebridge-smartrent/compare/v1.0.2...v1.0.3) (2022-08-12)


### Bug Fixes

* use Promise-based event listener registration ([#96](https://github.com/Burry/homebridge-smartrent/issues/96)) ([d23dbf7](https://github.com/Burry/homebridge-smartrent/commit/d23dbf7e276e82d49b11d2f62690f0ac26b33c7a)), closes [#4](https://github.com/Burry/homebridge-smartrent/issues/4) [#5](https://github.com/Burry/homebridge-smartrent/issues/5)

### [1.0.2](https://github.com/Burry/homebridge-smartrent/compare/v1.0.1...v1.0.2) (2022-01-24)


### Bug Fixes

* cleaner, less error-prone logger ([149e4c2](https://github.com/Burry/homebridge-smartrent/commit/149e4c27654b6935b37342b41f5ebf0804d5cc7b))
* use HOOBS-compatible characteristic handlers ([4cf8e4c](https://github.com/Burry/homebridge-smartrent/commit/4cf8e4cff8a9b877e5696db1ad03792a92445610))

### [1.0.1](https://github.com/Burry/homebridge-smartrent/compare/v1.0.0...v1.0.1) (2022-01-24)


### Bug Fixes

* drop minimum Node version to 12 ([acaf3b2](https://github.com/Burry/homebridge-smartrent/commit/acaf3b2445a1b1a31c168186eaa385e4f53c8683))

## 1.0.0 (2022-01-24)


### Features

* initial commit ([5206863](https://github.com/Burry/homebridge-smartrent/commit/5206863e35c5297cf052de7388a029979b3a24ac))

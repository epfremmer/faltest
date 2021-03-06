# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [3.2.2](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@3.2.1...@faltest/lifecycle@3.2.2) (2020-06-09)


### Bug Fixes

* add `enabled` flag to `createFailureArtifactsHelpers` ([bbff9b0](https://github.com/CrowdStrike/faltest/commit/bbff9b0e173cb7391e90156f2fe894614cd8c172))

### [3.2.1](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@3.2.0...@faltest/lifecycle@3.2.1) (2020-06-09)


### Bug Fixes

* remove redundant `WEBDRIVER_FAILURE_ARTIFACTS_OUTPUT_DIR` ([d18da33](https://github.com/CrowdStrike/faltest/commit/d18da33c8df8d31d2c66c3f9c5d91be7c4378efb))

## [3.2.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@3.1.0...@faltest/lifecycle@3.2.0) (2020-06-09)


### Features

* add failure artifacts to tests ([a3023ef](https://github.com/CrowdStrike/faltest/commit/a3023efca010d2d25a6e537a7ced93c9eba425ba))

## [3.1.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@3.0.1...@faltest/lifecycle@3.1.0) (2020-06-05)


### Features

* add `faltestOptions` to test context ([b0bd065](https://github.com/CrowdStrike/faltest/commit/b0bd065e7e8b32f1f4c153e4304a9e604884027e))

### [3.0.1](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@3.0.0...@faltest/lifecycle@3.0.1) (2020-06-05)


### Bug Fixes

* use the newer kill-orphans event ([8e56c26](https://github.com/CrowdStrike/faltest/commit/8e56c2657a5d452c7c55ac40ecdb2974f83d98a9))

## [3.0.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.15...@faltest/lifecycle@3.0.0) (2020-06-05)


### ⚠ BREAKING CHANGES

* the event signature changed

### Features

* update to the new event syntax ([f6c71e5](https://github.com/CrowdStrike/faltest/commit/f6c71e5782da68646ca36df8401479fa59845838))

### [2.0.15](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.14...@faltest/lifecycle@2.0.15) (2020-04-09)


### Bug Fixes

* recover after login failure ([243aa8c](https://github.com/CrowdStrike/faltest/commit/243aa8ca4f6e9a41b130cc1bc8ca0fa4864f0919))

### [2.0.14](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.13...@faltest/lifecycle@2.0.14) (2020-04-09)


### Bug Fixes

* init-context doesn't need to be called twice per test ([368c8aa](https://github.com/CrowdStrike/faltest/commit/368c8aafaa96c3c10818a676fc858213713aaf69))

### [2.0.13](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.12...@faltest/lifecycle@2.0.13) (2020-02-21)

### [2.0.12](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.11...@faltest/lifecycle@2.0.12) (2020-01-27)


### Bug Fixes

* bring back `reporterOptions` ([313024e](https://github.com/CrowdStrike/faltest/commit/313024e9057620f353e68666d05cb1a6890dea5c))

### [2.0.11](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.10...@faltest/lifecycle@2.0.11) (2020-01-13)

### [2.0.10](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.9...@faltest/lifecycle@2.0.10) (2020-01-09)

### [2.0.9](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.8...@faltest/lifecycle@2.0.9) (2020-01-09)

### [2.0.8](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.7...@faltest/lifecycle@2.0.8) (2020-01-06)

### [2.0.7](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.6...@faltest/lifecycle@2.0.7) (2020-01-02)

### [2.0.6](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.5...2.0.6) (2019-12-11)


### Bug Fixes

* broken release ([b629a5b](https://github.com/CrowdStrike/faltest/commit/b629a5ba02391d7c3992ccfa1bba95023088064b))

### [2.0.5](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.4...2.0.5) (2019-12-11)

### [2.0.4](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.3...2.0.4) (2019-12-10)

### [2.0.3](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.2...2.0.3) (2019-12-10)

### [2.0.2](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.1...2.0.2) (2019-12-10)


### Bug Fixes

* recycle state if overrides change ([8988d72](https://github.com/CrowdStrike/faltest/commit/8988d725eb4272bb6add7a6b673cd5c9b39661df))

### [2.0.1](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@2.0.0...2.0.1) (2019-12-06)

## [2.0.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.8...2.0.0) (2019-12-06)


### ⚠ BREAKING CHANGES

* remote api change
startWebDriver and startBrowser now take whole options object instead of just overrides.

### Features

* allow modifying capabilities via `customizeCapabilities` ([7683fd3](https://github.com/CrowdStrike/faltest/commit/7683fd39be42d5e8a8740c33d8c3cc8a34a77b99))

### [1.3.8](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.7...1.3.8) (2019-10-27)

### [1.3.7](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.6...1.3.7) (2019-10-21)


### Bug Fixes

* extract `loggedInRole` modifications ([b4a38c6](https://github.com/CrowdStrike/faltest/commit/b4a38c6))

### [1.3.6](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.5...1.3.6) (2019-10-21)


### Bug Fixes

* call log in and out once for every browser ([6928171](https://github.com/CrowdStrike/faltest/commit/6928171))
* extract `logIn` and `logOut` ([09222d7](https://github.com/CrowdStrike/faltest/commit/09222d7))

### [1.3.5](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.4...1.3.5) (2019-10-21)


### Bug Fixes

* throttle all browsers ([c43b5af](https://github.com/CrowdStrike/faltest/commit/c43b5af))

### [1.3.4](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.3...1.3.4) (2019-10-21)


### Bug Fixes

* send the new plural events no matter what ([fca7243](https://github.com/CrowdStrike/faltest/commit/fca7243))

### [1.3.3](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.2...1.3.3) (2019-10-21)

### [1.3.2](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.1...1.3.2) (2019-10-08)


### Bug Fixes

* `WEBDRIVER_BROWSERS` could be a string ([03a5f78](https://github.com/CrowdStrike/faltest/commit/03a5f78))
* use `Array.fill` for browser looping ([c32589b](https://github.com/CrowdStrike/faltest/commit/c32589b))

### [1.3.1](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.3.0...1.3.1) (2019-10-07)


### Bug Fixes

* multi line the browser override ([2ec694b](https://github.com/CrowdStrike/faltest/commit/2ec694b))

## [1.3.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.2.0...1.3.0) (2019-10-07)


### Features

* add multi browser support to the cli ([38b118c](https://github.com/CrowdStrike/faltest/commit/38b118c))

## [1.2.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.1.1...1.2.0) (2019-10-07)


### Features

* support multiple browsers in lifecycle ([78e21bb](https://github.com/CrowdStrike/faltest/commit/78e21bb))

### [1.1.1](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.1.0...1.1.1) (2019-10-01)

## [1.1.0](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.0.4...1.1.0) (2019-09-30)


### Features

* extract utils ([744588c](https://github.com/CrowdStrike/faltest/commit/744588c))

### [1.0.4](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.0.3...1.0.4) (2019-09-28)

### [1.0.3](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.0.2...1.0.3) (2019-09-28)

### [1.0.2](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.0.1...1.0.2) (2019-09-27)

### [1.0.1](https://github.com/CrowdStrike/faltest/compare/@faltest/lifecycle@1.0.0...1.0.1) (2019-09-12)

# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.1.1](https://github.com/sarakusha/typed-struct/compare/v2.1.0...v2.1.1) (2021-07-13)

## [2.1.0](https://github.com/sarakusha/typed-struct/compare/v2.0.0...v2.1.0) (2021-07-13)


### Features

* added support for 64-bit integers ([cd06e4f](https://github.com/sarakusha/typed-struct/commit/cd06e4f594ce3390ff73ea65799f1930df2ca4b6)), closes [#2](https://github.com/sarakusha/typed-struct/issues/2)
* allow structure extensions ([6d279fc](https://github.com/sarakusha/typed-struct/commit/6d279fc37dc296a42ec4d9347b481d3a5c1d7b43))

## [2.0.0](https://github.com/sarakusha/typed-struct/compare/v1.3.0...v2.0.0) (2021-06-11)


### ⚠ BREAKING CHANGES

* **crc:** The static `crc` method has been changed. It can now be used to calculate the
checksum if you have specified a checksum function for this field.

### Features

* **crc:** it is possible to pass the checksum function in the CRC field parameters ([8a8444c](https://github.com/sarakusha/typed-struct/commit/8a8444c6367b4495bf595c69fabb4f25c0dbe8e9))

## [1.3.0](https://github.com/sarakusha/typed-struct/compare/v1.2.0...v1.3.0) (2021-06-03)


### Features

* added helper function for calculating and updating checksum, rename `rows` to `lines` ([dd6a897](https://github.com/sarakusha/typed-struct/commit/dd6a8978ada4916900ce0cf7fffcda6e1ca3134c))
* added string literals ([b5242c6](https://github.com/sarakusha/typed-struct/commit/b5242c6238c31e4b6195b3aed42b16ca14a42741))
* added support for strings and string arrays ([b740377](https://github.com/sarakusha/typed-struct/commit/b7403774e632828f802b529320618e177f7a2030)), closes [#1](https://github.com/sarakusha/typed-struct/issues/1)


### Bug Fixes

* prevented extensibility and modification of StructArray ([e594211](https://github.com/sarakusha/typed-struct/commit/e594211b8f1d1735228b36fb45d154589a3903e6))
* remove `toString` ([fb8baa2](https://github.com/sarakusha/typed-struct/commit/fb8baa220b969ded0010d0718971fdfdaf0ec310))

## [1.2.0](https://github.com/sarakusha/typed-struct/compare/v1.1.1...v1.2.0) (2021-05-28)


### Features

* replacing the `toPOJO` method with the native `toJSON` ([9670e5c](https://github.com/sarakusha/typed-struct/commit/9670e5cb2909ae6837bf49fbd82cf7aa403f7da6))


### Bug Fixes

* clarified the return type of POJO and prototype changed to Object.prototype ([5404ed6](https://github.com/sarakusha/typed-struct/commit/5404ed66a8c215966800a8d9308edb244644fc63))

### [1.1.2](https://github.com/sarakusha/typed-struct/compare/v1.1.1...v1.1.2) (2021-05-27)


### Bug Fixes

* clarified the return type of POJO and prototype changed to Object.prototype ([5404ed6](https://github.com/sarakusha/typed-struct/commit/5404ed66a8c215966800a8d9308edb244644fc63))

### [1.1.1](https://github.com/sarakusha/typed-struct/compare/v1.1.0...v1.1.1) (2021-05-26)


### Bug Fixes

* assignment replaced with deep cloning in `toPOJO` ([d1aff45](https://github.com/sarakusha/typed-struct/commit/d1aff45b8f13e4696c8ba56b1ab3365e63c8dcbc))
* toString() implemented ([c836faa](https://github.com/sarakusha/typed-struct/commit/c836faabe0b3f6e6c3a600abac51fe2ff00c87ba))

## [1.1.0](https://github.com/sarakusha/typed-struct/compare/v1.0.9...v1.1.0) (2021-05-25)


### Features

* added arrays of variable length ([c883602](https://github.com/sarakusha/typed-struct/commit/c8836020d85b46f3e9d9acc323c3785beb9b7dda))
* added static method toPOJO ([bf16d94](https://github.com/sarakusha/typed-struct/commit/bf16d948117faaae1bdd2de25781cf1fe2107752))

### [1.0.9](https://github.com/sarakusha/typed-struct/compare/v1.0.8...v1.0.9) (2021-05-20)

### [1.0.8](https://github.com/sarakusha/typed-struct/compare/v1.0.7...v1.0.8) (2021-05-20)

### [1.0.7](https://github.com/sarakusha/typed-struct/compare/v1.0.6...v1.0.7) (2021-05-18)

### [1.0.6](https://github.com/sarakusha/typed-struct/compare/v1.0.5...v1.0.6) (2021-05-17)

### [1.0.5](https://github.com/sarakusha/typed-struct/compare/v1.0.4...v1.0.5) (2021-05-17)

### [1.0.4](https://github.com/sarakusha/typed-struct/compare/v1.0.3...v1.0.4) (2021-05-17)

### [1.0.3](https://github.com/sarakusha/typed-struct/compare/v1.0.2...v1.0.3) (2021-05-17)


### Bug Fixes

* **circleci:** change git:check => git:html ([fe2a68a](https://github.com/sarakusha/typed-struct/commit/fe2a68a152f18a61b5aa3017024ff96e4dc4ab98))

### [1.0.2](https://github.com/sarakusha/typed-struct/compare/v1.0.0...v1.0.2) (2021-05-17)

### [1.0.1](https://github.com/sarakusha/typed-struct/compare/v1.0.0...v1.0.1) (2021-05-17)

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.12.2](https://github.com/serenity-js/serenity-js/compare/v2.12.1...v2.12.2) (2020-07-08)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.12.1](https://github.com/serenity-js/serenity-js/compare/v2.12.0...v2.12.1) (2020-07-07)

**Note:** Version bump only for package @serenity-js/serenity-bdd





# [2.12.0](https://github.com/serenity-js/serenity-js/compare/v2.11.4...v2.12.0) (2020-07-06)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.11.4](https://github.com/serenity-js/serenity-js/compare/v2.11.3...v2.11.4) (2020-07-05)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.11.3](https://github.com/serenity-js/serenity-js/compare/v2.11.2...v2.11.3) (2020-07-05)


### Bug Fixes

* **serenity-bdd:** serenityBDDReporter reports events that occured in Mocha's before and after hooks ([a8e0ccb](https://github.com/serenity-js/serenity-js/commit/a8e0ccb20aa4bd8fed4c63816b4a09254fa09c24))





## [2.11.2](https://github.com/serenity-js/serenity-js/compare/v2.11.1...v2.11.2) (2020-07-04)


### Bug Fixes

* **serenity-bdd:** serenityBDD reporter ignores any events that happen outside of the test ([bb3b027](https://github.com/serenity-js/serenity-js/commit/bb3b027b9b1aa3f4024dcadeb8df1483d5e18906))





## [2.11.1](https://github.com/serenity-js/serenity-js/compare/v2.11.0...v2.11.1) (2020-06-30)


### Bug Fixes

* **serenity-bdd:** changed the default location of the cache directory so that npm doesn't prune it ([54d6dd4](https://github.com/serenity-js/serenity-js/commit/54d6dd4eb9c380c8fa917ffc4f2f23f98c9afcba)), closes [npm/npm#16853](https://github.com/npm/npm/issues/16853)





# [2.11.0](https://github.com/serenity-js/serenity-js/compare/v2.10.3...v2.11.0) (2020-06-20)


### Bug Fixes

* **serenity-bdd:** default Serenity BDD CLI to generating short filenames for the HTML report ([50c649d](https://github.com/serenity-js/serenity-js/commit/50c649d34fbe31f7129527a0aadca39e51e67543))
* **serenity-bdd:** moved core, assertions and rest from peerDependencies to dependencies ([966b20a](https://github.com/serenity-js/serenity-js/commit/966b20a7abf63a94463edd0f6313be3f995e0690))


### Features

* **mocha:** support for retrying failed scenarios ([2ff755b](https://github.com/serenity-js/serenity-js/commit/2ff755b4fa395ae412f4b250c3ba924a1337438c)), closes [#101](https://github.com/serenity-js/serenity-js/issues/101)





## [2.10.3](https://github.com/serenity-js/serenity-js/compare/v2.10.2...v2.10.3) (2020-06-15)


### Bug Fixes

* **serenity-bdd:** browser and platform context icons show up correctly in scenario outline reports ([a685afc](https://github.com/serenity-js/serenity-js/commit/a685afccf4436b8ed5e9259d3aad3e4fee5f0f39)), closes [#597](https://github.com/serenity-js/serenity-js/issues/597)





## [2.10.2](https://github.com/serenity-js/serenity-js/compare/v2.10.1...v2.10.2) (2020-06-11)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.10.1](https://github.com/serenity-js/serenity-js/compare/v2.10.0...v2.10.1) (2020-06-10)

**Note:** Version bump only for package @serenity-js/serenity-bdd





# [2.10.0](https://github.com/serenity-js/serenity-js/compare/v2.9.0...v2.10.0) (2020-06-06)


### Bug Fixes

* **serenity-bdd:** corrected links to feature reports for non-Cucumber test suites ([7fce935](https://github.com/serenity-js/serenity-js/commit/7fce935cdfd64099cae9351dc98f99d0598396b0))


### Features

* **serenity-bdd:** updated Serenity BDD CLI to 2.1.11 ([c7cfd0d](https://github.com/serenity-js/serenity-js/commit/c7cfd0dfabd886b0cd66267f47282ffeb0cdcf0c))





# [2.9.0](https://github.com/serenity-js/serenity-js/compare/v2.8.1...v2.9.0) (2020-06-05)


### Features

* **serenity-bdd:** choose human-readable or short file names for your HTML reports ([1b19aee](https://github.com/serenity-js/serenity-js/commit/1b19aee87023e84fd85e65cb93f8ea65e5c95f92))
* **serenity-bdd:** support for internal repositories that require authentication ([c14ac29](https://github.com/serenity-js/serenity-js/commit/c14ac29c3fd6257763f26201357721b1a04c72d5))





## [2.8.1](https://github.com/serenity-js/serenity-js/compare/v2.8.0...v2.8.1) (2020-06-02)


### Bug Fixes

* **serenity-bdd:** fixed issue with screenshots appearing out of order in the slideshow view ([a036605](https://github.com/serenity-js/serenity-js/commit/a036605fd226e0796821fa164da0460b697aa2e4)), closes [#582](https://github.com/serenity-js/serenity-js/issues/582)





# [2.8.0](https://github.com/serenity-js/serenity-js/compare/v2.7.0...v2.8.0) (2020-06-02)


### Features

* **serenity-bdd:** support for artifact repositories using local repository names ([523995b](https://github.com/serenity-js/serenity-js/commit/523995b82e6b7eedf635fb118336886125581f5d))





# [2.7.0](https://github.com/serenity-js/serenity-js/compare/v2.6.0...v2.7.0) (2020-06-01)

**Note:** Version bump only for package @serenity-js/serenity-bdd





# [2.6.0](https://github.com/serenity-js/serenity-js/compare/v2.5.5...v2.6.0) (2020-05-27)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.5.2](https://github.com/serenity-js/serenity-js/compare/v2.5.1...v2.5.2) (2020-05-16)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.5.1](https://github.com/serenity-js/serenity-js/compare/v2.5.0...v2.5.1) (2020-05-16)

**Note:** Version bump only for package @serenity-js/serenity-bdd





# [2.5.0](https://github.com/serenity-js/serenity-js/compare/v2.4.1...v2.5.0) (2020-05-14)


### Bug Fixes

* **npm:** esport ES2018 instead of ES5 since we're supporting Node >= 10 ([a77091a](https://github.com/serenity-js/serenity-js/commit/a77091aa779736172a60b6ac99ec1b869aaea816))





## [2.4.1](https://github.com/serenity-js/serenity-js/compare/v2.4.0...v2.4.1) (2020-05-03)

**Note:** Version bump only for package @serenity-js/serenity-bdd





# [2.4.0](https://github.com/serenity-js/serenity-js/compare/v2.3.6...v2.4.0) (2020-05-02)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.3.6](https://github.com/serenity-js/serenity-js/compare/v2.3.5...v2.3.6) (2020-04-28)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.3.5](https://github.com/serenity-js/serenity-js/compare/v2.3.4...v2.3.5) (2020-04-28)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.3.4](https://github.com/serenity-js/serenity-js/compare/v2.3.3...v2.3.4) (2020-04-22)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.3.3](https://github.com/serenity-js/serenity-js/compare/v2.3.2...v2.3.3) (2020-04-22)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.3.2](https://github.com/serenity-js/serenity-js/compare/v2.3.1...v2.3.2) (2020-04-08)


### Bug Fixes

* **deps:** updated TSLint and fixed some minor code style issues ([f43fd14](https://github.com/serenity-js/serenity-js/commit/f43fd14e11e2582aaa0d7cb3c186e0a58874a7fc))





## [2.3.1](https://github.com/serenity-js/serenity-js/compare/v2.3.0...v2.3.1) (2020-04-07)


### Bug Fixes

* **deps:** updated dependencies ([67401a7](https://github.com/serenity-js/serenity-js/commit/67401a774582386be02178e077b918a481630950))





# [2.3.0](https://github.com/serenity-js/serenity-js/compare/v2.2.2...v2.3.0) (2020-03-15)


### Features

* **serenity-bdd:** context icons for browsers and platforms ([65ccab0](https://github.com/serenity-js/serenity-js/commit/65ccab070d12c1d6d3f9067e3737e4c246bdbff0)), closes [#455](https://github.com/serenity-js/serenity-js/issues/455)
* **serenity-bdd:** one-way integration with jira and other issue trackers ([318abbb](https://github.com/serenity-js/serenity-js/commit/318abbbec5f6a99be3c9b8d3aa960ae05de9f8f4)), closes [#189](https://github.com/serenity-js/serenity-js/issues/189)





## [2.2.2](https://github.com/serenity-js/serenity-js/compare/v2.2.1...v2.2.2) (2020-03-08)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.2.1](https://github.com/serenity-js/serenity-js/compare/v2.2.0...v2.2.1) (2020-03-04)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.1.5](https://github.com/serenity-js/serenity-js/compare/v2.1.4...v2.1.5) (2020-02-10)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.1.4](https://github.com/serenity-js/serenity-js/compare/v2.1.3...v2.1.4) (2020-02-10)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.1.3](https://github.com/serenity-js/serenity-js/compare/v2.1.2...v2.1.3) (2020-02-10)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.1.2](https://github.com/serenity-js/serenity-js/compare/v2.1.1...v2.1.2) (2020-02-08)


### Bug Fixes

* **protractor:** distinguish between regular and 'mobile emulation' test runs ([fcd7101](https://github.com/serenity-js/serenity-js/commit/fcd7101939fddd855f45aa99b75e309b382b6b73)), closes [#323](https://github.com/serenity-js/serenity-js/issues/323)





## [2.1.1](https://github.com/serenity-js/serenity-js/compare/v2.1.0...v2.1.1) (2020-02-08)

**Note:** Version bump only for package @serenity-js/serenity-bdd





# [2.1.0](https://github.com/serenity-js/serenity-js/compare/v2.0.9...v2.1.0) (2020-02-07)


### Features

* **protractor:** browser tags include browser version and platform name ([bc4a038](https://github.com/serenity-js/serenity-js/commit/bc4a038484f75e90e44c5399c43213b472e71f38)), closes [#132](https://github.com/serenity-js/serenity-js/issues/132)





## [2.0.8](https://github.com/serenity-js/serenity-js/compare/v2.0.7...v2.0.8) (2020-02-05)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.7](https://github.com/serenity-js/serenity-js/compare/v2.0.6...v2.0.7) (2020-02-05)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.2](https://github.com/serenity-js/serenity-js/compare/v2.0.1...v2.0.2) (2020-02-04)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.132...v2.0.1) (2020-02-03)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.132](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.131...v2.0.1-alpha.132) (2020-02-03)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.131](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.130...v2.0.1-alpha.131) (2020-02-03)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.130](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.129...v2.0.1-alpha.130) (2020-02-03)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.129](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.128...v2.0.1-alpha.129) (2020-02-02)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.127](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.126...v2.0.1-alpha.127) (2020-02-02)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.126](https://github.com/serenity-js/serenity-js/compare/v2.0.1-alpha.125...v2.0.1-alpha.126) (2020-02-02)


### Bug Fixes

* **npm:** corrected the repo URL after the jan-molak -> serenity-js repo  migration ([a451199](https://github.com/serenity-js/serenity-js/commit/a4511995c50bf08977aa6c4c0f5d22ba7ead343f))





## [2.0.1-alpha.119](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.118...v2.0.1-alpha.119) (2020-02-02)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.118](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.117...v2.0.1-alpha.118) (2020-02-01)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.117](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.116...v2.0.1-alpha.117) (2020-01-29)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.116](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.115...v2.0.1-alpha.116) (2020-01-29)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.115](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.114...v2.0.1-alpha.115) (2020-01-27)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.114](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.113...v2.0.1-alpha.114) (2020-01-27)


### Bug Fixes

* **serenity-bdd:** reports are correctly stored to disk ([c050e2f](https://github.com/jan-molak/serenity-js/commit/c050e2fef0952d530394304619b42ee692f31584))





## [2.0.1-alpha.113](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.112...v2.0.1-alpha.113) (2020-01-26)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.112](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.111...v2.0.1-alpha.112) (2020-01-25)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.111](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.110...v2.0.1-alpha.111) (2020-01-25)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.110](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.109...v2.0.1-alpha.110) (2020-01-25)


### Features

* **core:** new APIs to make configuring and using Serenity/JS easier ([d11a80d](https://github.com/jan-molak/serenity-js/commit/d11a80de66519cb16b6eaa61a39694006a76b5fb))





## [2.0.1-alpha.109](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.108...v2.0.1-alpha.109) (2020-01-23)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.108](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.107...v2.0.1-alpha.108) (2020-01-20)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.107](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.106...v2.0.1-alpha.107) (2020-01-19)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.106](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.105...v2.0.1-alpha.106) (2020-01-19)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.105](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.104...v2.0.1-alpha.105) (2020-01-16)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.104](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.103...v2.0.1-alpha.104) (2020-01-10)


### Bug Fixes

* **lerna:** fixed the versions, since lerna managed to mess them up again ([0e87048](https://github.com/jan-molak/serenity-js/commit/0e87048219dc17a0c64a1bbf6b12128b18e85718))





## [2.0.1-alpha.101](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.100...v2.0.1-alpha.101) (2020-01-09)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.99](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.98...v2.0.1-alpha.99) (2020-01-09)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.98](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.97...v2.0.1-alpha.98) (2019-12-16)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.97](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.96...v2.0.1-alpha.97) (2019-12-15)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.96](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.95...v2.0.1-alpha.96) (2019-12-15)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.95](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.94...v2.0.1-alpha.95) (2019-12-11)


### Bug Fixes

* **dependencies:** updated Lerna and corrected the versions that got out of sync ([6c2f3af](https://github.com/jan-molak/serenity-js/commit/6c2f3afe98207c9241b5a7df970ec94fa37f4f1d))





## [2.0.1-alpha.90](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.89...v2.0.1-alpha.90) (2019-11-29)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.89](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.88...v2.0.1-alpha.89) (2019-11-27)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.88](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.87...v2.0.1-alpha.88) (2019-11-25)


### Bug Fixes

* **assertions:** Ensure correct 'actual' and 'expected' values are captured when an Expectation fail ([e503e55](https://github.com/jan-molak/serenity-js/commit/e503e55))


### Features

* **console-reporter:** New and shiny ConsoleReporter module to replace the experimental ConsoleRepo ([689937d](https://github.com/jan-molak/serenity-js/commit/689937d))
* **serenity-bdd:** AssertionErrors are reported together with a diff of actual/expected ([6b7a55e](https://github.com/jan-molak/serenity-js/commit/6b7a55e))





## [2.0.1-alpha.87](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.86...v2.0.1-alpha.87) (2019-11-10)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.86](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.85...v2.0.1-alpha.86) (2019-11-09)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.85](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.84...v2.0.1-alpha.85) (2019-10-13)


### Bug Fixes

* **core:** Dropped support for node 6 ([74d1ece](https://github.com/jan-molak/serenity-js/commit/74d1ece))





## [2.0.1-alpha.84](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.83...v2.0.1-alpha.84) (2019-09-24)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.83](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.82...v2.0.1-alpha.83) (2019-09-23)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.82](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.81...v2.0.1-alpha.82) (2019-09-22)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.81](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.80...v2.0.1-alpha.81) (2019-09-16)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.80](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.79...v2.0.1-alpha.80) (2019-09-05)

**Note:** Version bump only for package @serenity-js/serenity-bdd





## [2.0.1-alpha.77](https://github.com/jan-molak/serenity-js/compare/v2.0.1-alpha.76...v2.0.1-alpha.77) (2019-09-01)


### Features

* **serenity-bdd:** "serenity-bdd run" command can be configured with "--log" to specify the amount ([05cd487](https://github.com/jan-molak/serenity-js/commit/05cd487))
* **serenity-bdd:** Extracted the SerenityBDDReporter into a separate module ([fe7cfca](https://github.com/jan-molak/serenity-js/commit/fe7cfca))

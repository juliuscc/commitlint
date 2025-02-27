# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [9.1.0](https://github.com/conventional-changelog/commitlint/compare/v9.0.1...v9.1.0) (2020-06-21)


### Bug Fixes

* update dependency chalk to v4 ([#1275](https://github.com/conventional-changelog/commitlint/issues/1275)) ([a5d8fa1](https://github.com/conventional-changelog/commitlint/commit/a5d8fa118e8221361f14f5fd2b21d7aaad008a27))
* update dependency conventional-changelog-conventionalcommits to v4.3.0 ([#1816](https://github.com/conventional-changelog/commitlint/issues/1816)) ([f99aeda](https://github.com/conventional-changelog/commitlint/commit/f99aeda068aabdb250e2c9819da7229a695154b9))
* update dependency regenerator-runtime to v0.13.5 ([#1017](https://github.com/conventional-changelog/commitlint/issues/1017)) ([9c4fdf1](https://github.com/conventional-changelog/commitlint/commit/9c4fdf1b5f42677422532dad655af9aed9b43881))
* update dependency semver to v7.3.2 ([#1369](https://github.com/conventional-changelog/commitlint/issues/1369)) ([3c09722](https://github.com/conventional-changelog/commitlint/commit/3c09722d2db85a94cd1f4bf25c6b4251b2c41bbb))
* update dependency tar-fs to v2.1.0 ([#1103](https://github.com/conventional-changelog/commitlint/issues/1103)) ([7882036](https://github.com/conventional-changelog/commitlint/commit/788203689ebf51343ccf2e6eab530e19f4faf122))
* update dependency tmp to v0.2.1 ([#1817](https://github.com/conventional-changelog/commitlint/issues/1817)) ([0ff72f4](https://github.com/conventional-changelog/commitlint/commit/0ff72f41bd48b3dd37f881f6fb11477d8f643735))


### Features

* add local plugins support ([#1692](https://github.com/conventional-changelog/commitlint/issues/1692)) ([7b29c48](https://github.com/conventional-changelog/commitlint/commit/7b29c48321b513e091849fbb2cc2bf0e6ebb94a6))
* enable multiple scopes in scope-enum and scope-case rules ([#901](https://github.com/conventional-changelog/commitlint/issues/901)) ([73632ce](https://github.com/conventional-changelog/commitlint/commit/73632cec299d5c3a980d07037c08633c843a8555))





## [9.0.1](https://github.com/conventional-changelog/commitlint/compare/v9.0.0...v9.0.1) (2020-05-26)


### Bug Fixes

* add missing @babel/runtime dep [#1738](https://github.com/conventional-changelog/commitlint/issues/1738) ([#1754](https://github.com/conventional-changelog/commitlint/issues/1754)) ([09afcd6](https://github.com/conventional-changelog/commitlint/commit/09afcd647a2c1d00538cf1c970e3790d936111f8))





# [9.0.0](https://github.com/conventional-changelog/commitlint/compare/v8.3.5...v9.0.0) (2020-05-21)


### Bug Fixes

* **cli:** add missing regenerator-runtime to dependencies ([#919](https://github.com/conventional-changelog/commitlint/issues/919)) ([ee5eac9](https://github.com/conventional-changelog/commitlint/commit/ee5eac98fa97ba5ba17030c8d2705aee5c7f3a3a))
* [#840](https://github.com/conventional-changelog/commitlint/issues/840) add caret to lodash versions ([#843](https://github.com/conventional-changelog/commitlint/issues/843)) ([ffc0bac](https://github.com/conventional-changelog/commitlint/commit/ffc0bac26993acb2ab6a8fa51065f93c92b0d644))
* drop support for 'improvement' type ([#899](https://github.com/conventional-changelog/commitlint/issues/899)) ([b27ab08](https://github.com/conventional-changelog/commitlint/commit/b27ab08544373cfb72a4808756e2e8126ea96a97))
* **config-lerna-scopes:** correct lerna in peerDependencies ([#980](https://github.com/conventional-changelog/commitlint/issues/980)) ([f88f00d](https://github.com/conventional-changelog/commitlint/commit/f88f00d5d3d0a247b5635b50248bbb942b1ec962))
* ignore empty commit messages [#615](https://github.com/conventional-changelog/commitlint/issues/615) ([#676](https://github.com/conventional-changelog/commitlint/issues/676)) ([c3eb1a7](https://github.com/conventional-changelog/commitlint/commit/c3eb1a76e08213d7ce1f200e35f8d5d6de18982a))
* incorrect use of when in getForcedCaseFn ([#993](https://github.com/conventional-changelog/commitlint/issues/993)) ([34c11b8](https://github.com/conventional-changelog/commitlint/commit/34c11b8f3f233eca51866274a10d35231e8eb3d4))
* update dependency semver to v7.1.3 ([#995](https://github.com/conventional-changelog/commitlint/issues/995)) ([4ee307a](https://github.com/conventional-changelog/commitlint/commit/4ee307a1f8c861ae5d8a038560d166c5d00ea8ba))


### Features

* add async promise based rules methods into lint ([#976](https://github.com/conventional-changelog/commitlint/issues/976)) ([4443062](https://github.com/conventional-changelog/commitlint/commit/444306249b8a3d04524538f61edca8f6cc10d75f))
* add possibility to extend from string ([#865](https://github.com/conventional-changelog/commitlint/issues/865)) ([056c6fe](https://github.com/conventional-changelog/commitlint/commit/056c6fef346b4e84f8b1f93038a9461a7cbd9beb))
* passdown argv to lint command ([#891](https://github.com/conventional-changelog/commitlint/issues/891)) ([c49a57c](https://github.com/conventional-changelog/commitlint/commit/c49a57c77767b8213d565df3a8bbcd7369f36641))
* **config-conventional:** footer/body-max-line ([#436](https://github.com/conventional-changelog/commitlint/issues/436)) ([8b394c9](https://github.com/conventional-changelog/commitlint/commit/8b394c94ffe37322d734bd4944add4a6cb2a4689))
* **config-conventional:** increase header-max-length to 100 ([#860](https://github.com/conventional-changelog/commitlint/issues/860)) ([ff11998](https://github.com/conventional-changelog/commitlint/commit/ff11998e0cf6fcd4f03bc18ab27b1bdd6bf21906)), closes [#859](https://github.com/conventional-changelog/commitlint/issues/859)


### BREAKING CHANGES

* 'improvement' type will now be rejected by this config.





## [8.3.5](https://github.com/conventional-changelog/commitlint/compare/v8.3.4...v8.3.5) (2020-01-15)


### Bug Fixes

* **is-ignored:** move types to dev dependencies ([#897](https://github.com/conventional-changelog/commitlint/issues/897)) ([aabc549](https://github.com/conventional-changelog/commitlint/commit/aabc549))
* **resolve-extends:** move node types to dev dependencies ([#883](https://github.com/conventional-changelog/commitlint/issues/883)) ([b131a18](https://github.com/conventional-changelog/commitlint/commit/b131a18)), closes [#874](https://github.com/conventional-changelog/commitlint/issues/874)





## [8.3.4](https://github.com/conventional-changelog/commitlint/compare/v8.3.3...v8.3.4) (2020-01-03)


### Bug Fixes

* **commitlint:** use new read pkg syntax ([#888](https://github.com/conventional-changelog/commitlint/issues/888)) ([6b3b9a9](https://github.com/conventional-changelog/commitlint/commit/6b3b9a9))





## [8.3.1](https://github.com/conventional-changelog/commitlint/compare/v8.3.0...v8.3.1) (2019-10-16)


### Bug Fixes

* **load:** resolve nested parser preset factories ([#831](https://github.com/conventional-changelog/commitlint/issues/831)) ([73a7df7](https://github.com/conventional-changelog/commitlint/commit/73a7df7))





# [8.3.0](https://github.com/conventional-changelog/commitlint/compare/v8.2.0...v8.3.0) (2019-10-16)


### Features

* **cli:** add helpurl flag ([#789](https://github.com/conventional-changelog/commitlint/issues/789)) ([75cef4e](https://github.com/conventional-changelog/commitlint/commit/75cef4e))
* **config-conventional:** use parser with short breaking change support ([#821](https://github.com/conventional-changelog/commitlint/issues/821)) ([4b5300a](https://github.com/conventional-changelog/commitlint/commit/4b5300a))
* **resolve-extends:** accept absolute path in extends ([#825](https://github.com/conventional-changelog/commitlint/issues/825)) ([ecac29f](https://github.com/conventional-changelog/commitlint/commit/ecac29f))





# [8.2.0](https://github.com/conventional-changelog/commitlint/compare/v8.1.0...v8.2.0) (2019-09-16)

This release is versioned as minor change because some of the core components are rewritten to TypeScript. It's part of the full port to TypeScript, currently in progress at [#659](https://github.com/conventional-changelog/commitlint/issues/659).

### Bug Fixes

* pass defaultIgnores from configuration in @commitlint/cli ([#771](https://github.com/conventional-changelog/commitlint/issues/771)) ([a259014](https://github.com/conventional-changelog/commitlint/commit/a259014))





# [8.1.0](https://github.com/conventional-changelog/commitlint/compare/v8.0.0...v8.1.0) (2019-07-15)

This release is versioned as minor change because some of the core components are rewritten to TypeScript. It's part of the full port to TypeScript, currently in progress at [#659](https://github.com/conventional-changelog/commitlint/issues/659).

### Bug Fixes

* add explicit dependency on chalk ([#687](https://github.com/conventional-changelog/commitlint/issues/687)) ([9075844](https://github.com/conventional-changelog/commitlint/commit/9075844))
* pass ignores from configuration in @commitlint/cli ([#668](https://github.com/conventional-changelog/commitlint/issues/668)) ([da99aaa](https://github.com/conventional-changelog/commitlint/commit/da99aaa))





# [8.0.0](https://github.com/conventional-changelog/commitlint/compare/v7.6.2...v8.0.0)

### Breaking Changes

* fix: avoid excessive help text #606 (#637)
  The commitlint default formatter is now silent for reports without warnings or errors.
  Scripts relying on the success output of commitlint can restore the former output by specifying the --verbose flag.


## [7.6.2](https://github.com/conventional-changelog/commitlint/compare/v7.6.0...v7.6.2)

* Republish packages with out of sync artifacts

## [7.6.1](https://github.com/conventional-changelog/commitlint/compare/v7.6.0...v7.6.1) (2019-05-09)


### Bug Fixes

* ensure format() is available as commonjs default export [#645](https://github.com/conventional-changelog/commitlint/issues/645) ([ec3da92](https://github.com/conventional-changelog/commitlint/commit/ec3da92))
* handle absolute config paths correctly [#647](https://github.com/conventional-changelog/commitlint/issues/647) ([49b3a77](https://github.com/conventional-changelog/commitlint/commit/49b3a77))


# [7.6.0](https://github.com/conventional-changelog/commitlint/compare/v7.5.2...v7.6.0) (2019-05-06)


### Bug Fixes

* add @lerna/project to repository dependencies ([#598](https://github.com/conventional-changelog/commitlint/issues/598)) ([56f03ee](https://github.com/conventional-changelog/commitlint/commit/56f03ee))
* address security warnings for dev dependencies ([3e0d824](https://github.com/conventional-changelog/commitlint/commit/3e0d824))
* avoid excessive help text [#606](https://github.com/conventional-changelog/commitlint/issues/606) ([#637](https://github.com/conventional-changelog/commitlint/issues/637)) ([8f3c3b1](https://github.com/conventional-changelog/commitlint/commit/8f3c3b1))
* don't merge array properties with custom opts ([#616](https://github.com/conventional-changelog/commitlint/issues/616)) ([f321647](https://github.com/conventional-changelog/commitlint/commit/f321647)), closes [#594](https://github.com/conventional-changelog/commitlint/issues/594)
* remove unneeded dev dependency ([6ccaf79](https://github.com/conventional-changelog/commitlint/commit/6ccaf79))
* update cosmiconfig to safe >=5 [#599](https://github.com/conventional-changelog/commitlint/issues/599) ([f186fcb](https://github.com/conventional-changelog/commitlint/commit/f186fcb))
* use sander.readFile correctly ([#448](https://github.com/conventional-changelog/commitlint/issues/448)) ([#630](https://github.com/conventional-changelog/commitlint/issues/630)) ([8e47985](https://github.com/conventional-changelog/commitlint/commit/8e47985))


### Features

* **resolve-extends:** accept short scoped package names in extends ([#597](https://github.com/conventional-changelog/commitlint/issues/597)) ([ba90e8e](https://github.com/conventional-changelog/commitlint/commit/ba90e8e))
* adds support for plugins ([#228](https://github.com/conventional-changelog/commitlint/issues/228)) ([#588](https://github.com/conventional-changelog/commitlint/issues/588)) ([cea4564](https://github.com/conventional-changelog/commitlint/commit/cea4564))
* config based is-ignored overrides ([#595](https://github.com/conventional-changelog/commitlint/issues/595)) ([2434d71](https://github.com/conventional-changelog/commitlint/commit/2434d71))





## [7.5.2](https://github.com/conventional-changelog/commitlint/compare/v7.5.1...v7.5.2) (2019-02-11)


### Bug Fixes

* failing sentence-case for subjects with slashes ([#574](https://github.com/conventional-changelog/commitlint/issues/574)) ([48a8602](https://github.com/conventional-changelog/commitlint/commit/48a8602))
* **cli:** replace old links with new organisation links ([#578](https://github.com/conventional-changelog/commitlint/issues/578)) ([4075903](https://github.com/conventional-changelog/commitlint/commit/4075903))





## [7.5.1](https://github.com/conventional-changelog/commitlint/compare/v7.5.0...v7.5.1) (2019-02-09)


### Bug Fixes

* **is-ignored:** ignore bitbuckets automatic merge ([#573](https://github.com/conventional-changelog/commitlint/issues/573)) ([e5bdc5c](https://github.com/conventional-changelog/commitlint/commit/e5bdc5c))





<a name="7.5.0"></a>
# [7.5.0](https://github.com/conventional-changelog/commitlint/compare/v7.4.0...v7.5.0) (2019-01-31)


### Bug Fixes

* `sentence-case` allow upper-case characters in first word ([#531](https://github.com/conventional-changelog/commitlint/issues/531)) ([5a6a4a8](https://github.com/conventional-changelog/commitlint/commit/5a6a4a8)), closes [#211](https://github.com/conventional-changelog/commitlint/issues/211)
* **resolve-extends:** override array on extending rules ([#470](https://github.com/conventional-changelog/commitlint/issues/470)) ([#539](https://github.com/conventional-changelog/commitlint/issues/539)) ([b35000c](https://github.com/conventional-changelog/commitlint/commit/b35000c))
* all broken website references ([#564](https://github.com/conventional-changelog/commitlint/issues/564)) ([82eeb5a](https://github.com/conventional-changelog/commitlint/commit/82eeb5a))
* cleanup message for input with no config ([#519](https://github.com/conventional-changelog/commitlint/issues/519)) ([7d9e760](https://github.com/conventional-changelog/commitlint/commit/7d9e760))
* **cli:** avoid linebreak in empty input ([#523](https://github.com/conventional-changelog/commitlint/issues/523)) ([3141882](https://github.com/conventional-changelog/commitlint/commit/3141882))
* mark optional parameter with undefined ([#553](https://github.com/conventional-changelog/commitlint/issues/553)) ([6720284](https://github.com/conventional-changelog/commitlint/commit/6720284))
* replace all repository references with conventional changelog ([#561](https://github.com/conventional-changelog/commitlint/issues/561)) ([6c3afcd](https://github.com/conventional-changelog/commitlint/commit/6c3afcd))
* replace all website references with conventional changelog ([#563](https://github.com/conventional-changelog/commitlint/issues/563)) ([6b86fb1](https://github.com/conventional-changelog/commitlint/commit/6b86fb1))
* replace old require-uncached with import-fresh ([#533](https://github.com/conventional-changelog/commitlint/issues/533)) ([b636e8c](https://github.com/conventional-changelog/commitlint/commit/b636e8c))
* resolve path to commit message for git submodules ([83b1a47](https://github.com/conventional-changelog/commitlint/commit/83b1a47))
* slash in scope [#291](https://github.com/conventional-changelog/commitlint/issues/291) ([#529](https://github.com/conventional-changelog/commitlint/issues/529)) ([b2b63e5](https://github.com/conventional-changelog/commitlint/commit/b2b63e5))
* store concatenated array to problems variable ([#551](https://github.com/conventional-changelog/commitlint/issues/551)) ([434a70f](https://github.com/conventional-changelog/commitlint/commit/434a70f))


### Features

* add support for git submodules ([cc575fa](https://github.com/conventional-changelog/commitlint/commit/cc575fa))
* **rule-header-length:** show current header length ([6d61c4f](https://github.com/conventional-changelog/commitlint/commit/6d61c4f))




<a name="7.4.0"></a>
# [7.4.0](https://github.com/conventional-changelog/commitlint/compare/v7.3.2...v7.4.0) (2019-01-27)


### Bug Fixes

* correction to need help link ([#540](https://github.com/conventional-changelog/commitlint/issues/540)) ([fa6168a](https://github.com/conventional-changelog/commitlint/commit/fa6168a))


### Features

* **rules:** create header-case and header-full-stop rules ([#547](https://github.com/conventional-changelog/commitlint/issues/547)) ([4c36cbd](https://github.com/conventional-changelog/commitlint/commit/4c36cbd))




<a name="7.3.2"></a>
## [7.3.2](https://github.com/conventional-changelog/commitlint/compare/v7.3.1...v7.3.2) (2019-01-15)


### Bug Fixes

* move loadsh to dependencies ([1bb66a4](https://github.com/conventional-changelog/commitlint/commit/1bb66a4))




<a name="7.3.1"></a>
## [7.3.1](https://github.com/conventional-changelog/commitlint/compare/v7.3.0...v7.3.1) (2019-01-11)




**Note:** Version bump only for package @commitlint/root

<a name="7.3.0"></a>
# [7.3.0](https://github.com/conventional-changelog/commitlint/compare/v7.2.1...v7.3.0) (2019-01-11)


### Bug Fixes

* **format:** add new line to result ([#518](https://github.com/conventional-changelog/commitlint/issues/518)) ([f1d443b](https://github.com/conventional-changelog/commitlint/commit/f1d443b)), closes [#504](https://github.com/conventional-changelog/commitlint/issues/504)
* add fallback with husky git params to deprecation handling ([#498](https://github.com/conventional-changelog/commitlint/issues/498)) ([5a34b8c](https://github.com/conventional-changelog/commitlint/commit/5a34b8c))
* avoid truncated output on macOS ([#503](https://github.com/conventional-changelog/commitlint/issues/503)) ([3192368](https://github.com/conventional-changelog/commitlint/commit/3192368))
* fall back to conventional commit-parser settings for missing keys ([#496](https://github.com/conventional-changelog/commitlint/issues/496)) ([831a141](https://github.com/conventional-changelog/commitlint/commit/831a141)), closes [#399](https://github.com/conventional-changelog/commitlint/issues/399)
* respect String.protoype.repeat API contract ([f27e7ac](https://github.com/conventional-changelog/commitlint/commit/f27e7ac))
* update to security-patched dependency versions ([97c033b](https://github.com/conventional-changelog/commitlint/commit/97c033b))
* use correct label for failing empty subjects ([#481](https://github.com/conventional-changelog/commitlint/issues/481)) ([2e7e34d](https://github.com/conventional-changelog/commitlint/commit/2e7e34d)), closes [#476](https://github.com/conventional-changelog/commitlint/issues/476)


### Features

* check stage before entering prompt ([#495](https://github.com/conventional-changelog/commitlint/issues/495)) ([3b3667a](https://github.com/conventional-changelog/commitlint/commit/3b3667a)), closes [#51](https://github.com/conventional-changelog/commitlint/issues/51) [#51](https://github.com/conventional-changelog/commitlint/issues/51)
* warn on empty config ([#491](https://github.com/conventional-changelog/commitlint/issues/491)) ([b6bd36e](https://github.com/conventional-changelog/commitlint/commit/b6bd36e)), closes [#107](https://github.com/conventional-changelog/commitlint/issues/107) [#107](https://github.com/conventional-changelog/commitlint/issues/107)




<a name="7.2.1"></a>
## [7.2.1](https://github.com/conventional-changelog/commitlint/compare/v7.2.0...v7.2.1) (2018-10-11)


### Bug Fixes

* improve format module resolving ([#464](https://github.com/conventional-changelog/commitlint/issues/464)) ([baed8b1](https://github.com/conventional-changelog/commitlint/commit/baed8b1))




<a name="7.2.0"></a>
# [7.2.0](https://github.com/conventional-changelog/commitlint/compare/v7.1.2...v7.2.0) (2018-10-05)


### Bug Fixes

* **rules:** include possible body offset in footer leading blank ([ff0111a](https://github.com/conventional-changelog/commitlint/commit/ff0111a))
* handle case rules for numerics correctly ([cadcfed](https://github.com/conventional-changelog/commitlint/commit/cadcfed))
* ignore merge messages with text after newline ([b32bc93](https://github.com/conventional-changelog/commitlint/commit/b32bc93))
* use grouped regex to ignore merge commits ([#439](https://github.com/conventional-changelog/commitlint/issues/439)) ([905e9d5](https://github.com/conventional-changelog/commitlint/commit/905e9d5))


### Features

* **cli:** add format option for report output ([1ecf097](https://github.com/conventional-changelog/commitlint/commit/1ecf097))
* **load:** add formatter option with default value ([b0e63d9](https://github.com/conventional-changelog/commitlint/commit/b0e63d9))




<a name="7.1.2"></a>
## [7.1.2](https://github.com/conventional-changelog/commitlint/compare/v7.1.1...v7.1.2) (2018-09-04)




**Note:** Version bump only for package @commitlint/root

<a name="7.1.0"></a>
# [7.1.0](https://github.com/conventional-changelog/commitlint/compare/v7.0.1...v7.1.0) (2018-08-29)


### Features

* **wildcards:** add new wildcard patterns [#315](https://github.com/conventional-changelog/commitlint/issues/315) ([e9ea17f](https://github.com/conventional-changelog/commitlint/commit/e9ea17f))
* add max line length to body/footer  ([542f50e](https://github.com/conventional-changelog/commitlint/commit/542f50e))




<a name="6.2.0"></a>
# [6.2.0](https://github.com/conventional-changelog/commitlint/compare/v6.1.3...v6.2.0) (2018-05-01)


### Features

* print commit message when the message is invalid ([86c34f1](https://github.com/conventional-changelog/commitlint/commit/86c34f1)), closes [#222](https://github.com/conventional-changelog/commitlint/issues/222)
* **rules:** support array for scope-case and type-case ([#312](https://github.com/conventional-changelog/commitlint/issues/312)) ([1f46b9f](https://github.com/conventional-changelog/commitlint/commit/1f46b9f)), closes [#307](https://github.com/conventional-changelog/commitlint/issues/307)




<a name="6.1.1"></a>
## [6.1.1](https://github.com/conventional-changelog/commitlint/compare/v6.1.0...v6.1.1) (2018-02-22)


### Bug Fixes

* **ensure:** ignore word delimiters for case matching [#291](https://github.com/conventional-changelog/commitlint/issues/291) ([fa69299](https://github.com/conventional-changelog/commitlint/commit/fa69299))




<a name="6.1.0"></a>
# [6.1.0](https://github.com/conventional-changelog/commitlint/compare/v6.0.5...v6.1.0) (2018-02-03)


### Bug Fixes

* **parse:** default to angular preset for empty parserOpts ([#265](https://github.com/conventional-changelog/commitlint/issues/265)) ([ccb03b4](https://github.com/conventional-changelog/commitlint/commit/ccb03b4)), closes [#262](https://github.com/conventional-changelog/commitlint/issues/262)


### Features

* add "--config" option ([#261](https://github.com/conventional-changelog/commitlint/issues/261)) ([2c03ec6](https://github.com/conventional-changelog/commitlint/commit/2c03ec6))




<a name="6.0.5"></a>
## [6.0.5](https://github.com/conventional-changelog/commitlint/compare/v6.0.4...v6.0.5) (2018-01-31)


### Bug Fixes

* remove utils from prod dependencies ([4fb858a](https://github.com/conventional-changelog/commitlint/commit/4fb858a))




<a name="6.0.4"></a>
## [6.0.4](https://github.com/conventional-changelog/commitlint/compare/v6.0.3...v6.0.4) (2018-01-31)


### Bug Fixes

* remove faulty bin entry [#259](https://github.com/conventional-changelog/commitlint/issues/259) ([beafbc6](https://github.com/conventional-changelog/commitlint/commit/beafbc6))




<a name="6.0.3"></a>
## [6.0.3](https://github.com/conventional-changelog/commitlint/compare/v6.0.2...v6.0.3) (2018-01-31)


### Bug Fixes

* update dependency cosmiconfig to ^4.0.0 ([#234](https://github.com/conventional-changelog/commitlint/issues/234)) ([7f94ac5](https://github.com/conventional-changelog/commitlint/commit/7f94ac5))
* update dependency semver to v5.5.0 ([#236](https://github.com/conventional-changelog/commitlint/issues/236)) ([6c52bd9](https://github.com/conventional-changelog/commitlint/commit/6c52bd9))




<a name="6.0.2"></a>
## [6.0.2](https://github.com/conventional-changelog/commitlint/compare/v6.0.0...v6.0.2) (2018-01-12)


### Bug Fixes

* ignore branch merges with multiple newlines ([#227](https://github.com/conventional-changelog/commitlint/issues/227)) ([1f0c5ca](https://github.com/conventional-changelog/commitlint/commit/1f0c5ca))
* remove typo in error message of type-case ([cb577cb](https://github.com/conventional-changelog/commitlint/commit/cb577cb))




<a name="6.0.1"></a>
## [6.0.1](https://github.com/conventional-changelog/commitlint/compare/v6.0.0...v6.0.1) (2018-01-09)




**Note:** Version bump only for package @commitlint/root

<a name="6.0.0"></a>
# [6.0.0](https://github.com/conventional-changelog/commitlint/compare/v5.2.6...v6.0.0) (2018-01-09)


### Bug Fixes

* allow [0] shorthand ([84cf938](https://github.com/conventional-changelog/commitlint/commit/84cf938))
* correctly resolve parserOpts [#115](https://github.com/conventional-changelog/commitlint/issues/115) [#95](https://github.com/conventional-changelog/commitlint/issues/95) ([1353dd5](https://github.com/conventional-changelog/commitlint/commit/1353dd5))
* ignore branch merges with newlines ([#214](https://github.com/conventional-changelog/commitlint/issues/214)) ([c94c4dc](https://github.com/conventional-changelog/commitlint/commit/c94c4dc))
* sanitize ensure.case [#211](https://github.com/conventional-changelog/commitlint/issues/211) ([#217](https://github.com/conventional-changelog/commitlint/issues/217)) ([03aeefc](https://github.com/conventional-changelog/commitlint/commit/03aeefc))


### Styles

* validate rule configuration ([edf7187](https://github.com/conventional-changelog/commitlint/commit/edf7187))


### BREAKING CHANGES

* Due to additional validation while reading
commitlint config, previously ignored rule
settings are now considered critical errors
when starting the CLI. The new behaviour is
designed to help developers find issues with
their configuration quicker.




<a name="5.2.6"></a>
## [5.2.6](https://github.com/conventional-changelog/commitlint/compare/v5.2.5...v5.2.6) (2017-12-21)


### Bug Fixes

* ignore semver commits with chore type ([cdbb085](https://github.com/conventional-changelog/commitlint/commit/cdbb085)), closes [#198](https://github.com/conventional-changelog/commitlint/issues/198)




<a name="5.2.5"></a>
## [5.2.5](https://github.com/conventional-changelog/commitlint/compare/v5.2.4...v5.2.5) (2017-12-08)


### Bug Fixes

* **core:** use correct report message [#192](https://github.com/conventional-changelog/commitlint/issues/192) ([e3a78bc](https://github.com/conventional-changelog/commitlint/commit/e3a78bc))




<a name="5.2.4"></a>
## [5.2.4](https://github.com/conventional-changelog/commitlint/compare/v5.2.3...v5.2.4) (2017-12-08)




**Note:** Version bump only for package @commitlint/root

<a name="5.2.3"></a>
## [5.2.3](https://github.com/conventional-changelog/commitlint/compare/v5.2.2...v5.2.3) (2017-12-05)


### Bug Fixes

* **cli:** add support for GIT_PARAMS on windows ([c62bd41](https://github.com/conventional-changelog/commitlint/commit/c62bd41)), closes [#103](https://github.com/conventional-changelog/commitlint/issues/103) [#175](https://github.com/conventional-changelog/commitlint/issues/175)




<a name="5.2.2"></a>
## [5.2.2](https://github.com/conventional-changelog/commitlint/compare/v5.2.1...v5.2.2) (2017-11-30)


### Bug Fixes

* **travis-cli:** read push commits directly ([9bc56c6](https://github.com/conventional-changelog/commitlint/commit/9bc56c6))




<a name="5.2.1"></a>
## [5.2.1](https://github.com/conventional-changelog/commitlint/compare/v5.2.0...v5.2.1) (2017-11-30)


### Bug Fixes

* **travis-cli:** lint ranges only for pr builds ([85b201f](https://github.com/conventional-changelog/commitlint/commit/85b201f))




<a name="5.2.0"></a>
# [5.2.0](https://github.com/conventional-changelog/commitlint/compare/v5.1.3...v5.2.0) (2017-11-30)


### Bug Fixes

* consider pull requests from forks ([4653c2c](https://github.com/conventional-changelog/commitlint/commit/4653c2c))


### Features

* **babel-preset-commitlint:** add jsx tranform ([#163](https://github.com/conventional-changelog/commitlint/issues/163)) ([5190241](https://github.com/conventional-changelog/commitlint/commit/5190241))




<a name="5.1.3"></a>
## [5.1.3](https://github.com/conventional-changelog/commitlint/compare/v5.1.2...v5.1.3) (2017-11-24)


### Bug Fixes

* **config-conventional:** add missing applicable attribute to type-enum ([a8db0b1](https://github.com/conventional-changelog/commitlint/commit/a8db0b1))




<a name="5.1.2"></a>
## [5.1.2](https://github.com/conventional-changelog/commitlint/compare/v5.1.1...v5.1.2) (2017-11-24)


### Bug Fixes

* **prompt:** apply forced cases properly ([3a569a7](https://github.com/conventional-changelog/commitlint/commit/3a569a7)), closes [#145](https://github.com/conventional-changelog/commitlint/issues/145)




<a name="5.1.1"></a>
## [5.1.1](https://github.com/conventional-changelog/commitlint/compare/v5.1.0...v5.1.1) (2017-11-24)


### Bug Fixes

* set access for npm ([8aeaec2](https://github.com/conventional-changelog/commitlint/commit/8aeaec2))




<a name="5.1.0"></a>
# [5.1.0](https://github.com/conventional-changelog/commitlint/compare/v5.0.2...v5.1.0) (2017-11-24)


### Bug Fixes

* update dependency concurrently to v3.5.1 ([#147](https://github.com/conventional-changelog/commitlint/issues/147)) ([a809d0f](https://github.com/conventional-changelog/commitlint/commit/a809d0f))
* **config-conventional:** remove unneeded dependency ([d0e62fd](https://github.com/conventional-changelog/commitlint/commit/d0e62fd))


### Features

* **prompt:** add description for build, ci and revert ([#148](https://github.com/conventional-changelog/commitlint/issues/148)) ([ee6ec6e](https://github.com/conventional-changelog/commitlint/commit/ee6ec6e))
* **travis-cli:** add reusable travis command line interface ([3e6e6a8](https://github.com/conventional-changelog/commitlint/commit/3e6e6a8))
* add conventional-changelog package ([8bb0a85](https://github.com/conventional-changelog/commitlint/commit/8bb0a85))




<a name="5.0.1"></a>
## [5.0.1](https://github.com/conventional-changelog/commitlint/compare/v5.0.0...v5.0.1) (2017-11-19)


### Bug Fixes

* **core:** fall back to globally installed config if available ([#127](https://github.com/conventional-changelog/commitlint/issues/127)) ([8612eb3](https://github.com/conventional-changelog/commitlint/commit/8612eb3))




<a name="5.0.0"></a>
# [5.0.0](https://github.com/conventional-changelog/commitlint/compare/v4.3.0...v5.0.0) (2017-11-18)

### Bug fixes

* core: interprets array values for subject-case correctly

### Features

* config-angular: disallow subject with uppercase first character, #114
* config-angular-type-enum: remove chore type


BREAKING CHANGE

TL;DR
* chore is no longer a valid commit type
* subject with leading capitalized letter are forbidden now

Angular has removed the chore type from their
conventions as of January 2017

See [angular/angular@dff6ee](https://github.com/angular/angular/commit/dff6ee32725197bdb81f3f63c5bd9805f2ed22bb#diff-6a3371457528722a734f3c51d9238c13L204)
for reference

This removes the previous chore type from the list
of allowed types.

Projects using the Angular commit convention will identify commits with chore type as faulty.

Also, formerly working commit messages are now considered problems:

*  type: SOME MESSAGE
*  type: SomeMessage
*  type: Some Message

<a name="4.3.0"></a>
# [4.3.0](https://github.com/conventional-changelog/commitlint/compare/v4.2.2...v4.3.0) (2017-11-08)


### Bug Fixes

* **core:** deprecate nlp rules  ([bbab1d8](https://github.com/conventional-changelog/commitlint/commit/bbab1d8)), closes [#54](https://github.com/conventional-changelog/commitlint/issues/54)
* **core:** ignore comments ([f3beda1](https://github.com/conventional-changelog/commitlint/commit/f3beda1)), closes [#78](https://github.com/conventional-changelog/commitlint/issues/78)


### Features

* add references-empty rule ([4fc8d5d](https://github.com/conventional-changelog/commitlint/commit/4fc8d5d))

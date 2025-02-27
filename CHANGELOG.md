# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.0.1](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v2.0.0...v2.0.1) (2019-09-06)


### Bug Fixes

* reduce memory usage ([#145](https://github.com/webpack-contrib/terser-webpack-plugin/issues/145)) ([815e533](https://github.com/webpack-contrib/terser-webpack-plugin/commit/815e533))
* revert do not run parallel mode when you have only one file ([#146](https://github.com/webpack-contrib/terser-webpack-plugin/issues/146)) ([6613a97](https://github.com/webpack-contrib/terser-webpack-plugin/commit/6613a97))

## [2.0.0](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.4.1...v2.0.0) (2019-09-05)


### ⚠ BREAKING CHANGES

* minimum require Node.js version is `8.9.0`
* the `extractComments` option is `true` by default
* the `cache` option is `true` by default
* the `parallel` option is `true` by default
* using the `extractComments.condition` option with `true` value extract only `some` comments


### Bug Fixes

* do not run parallel mode when you have only one file ([#134](https://github.com/webpack-contrib/terser-webpack-plugin/issues/134)) ([8b88b39](https://github.com/webpack-contrib/terser-webpack-plugin/commit/8b88b39))
* make `extractComments` API more consistent ([#129](https://github.com/webpack-contrib/terser-webpack-plugin/issues/129)) ([37d2df0](https://github.com/webpack-contrib/terser-webpack-plugin/commit/37d2df0))
* parallel on wsl ([#138](https://github.com/webpack-contrib/terser-webpack-plugin/issues/138)) ([0537591](https://github.com/webpack-contrib/terser-webpack-plugin/commit/0537591))


### Features

* enable the cache option by default ([#132](https://github.com/webpack-contrib/terser-webpack-plugin/issues/132)) ([960d249](https://github.com/webpack-contrib/terser-webpack-plugin/commit/960d249))
* enable the extractComments option by default ([ad2471c](https://github.com/webpack-contrib/terser-webpack-plugin/commit/ad2471c))
* enable the parallel option by default ([#131](https://github.com/webpack-contrib/terser-webpack-plugin/issues/131)) ([7b342af](https://github.com/webpack-contrib/terser-webpack-plugin/commit/7b342af))
* respect `devtool` values for source map generation ([#140](https://github.com/webpack-contrib/terser-webpack-plugin/issues/140)) ([dd37ca1](https://github.com/webpack-contrib/terser-webpack-plugin/commit/dd37ca1))

### [1.4.1](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.4.0...v1.4.1) (2019-07-31)


### Bug Fixes

* removed unnecessary dependency ([#111](https://github.com/webpack-contrib/terser-webpack-plugin/issues/111)) ([bc19b72](https://github.com/webpack-contrib/terser-webpack-plugin/commit/bc19b72))

## [1.4.0](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.3.0...v1.4.0) (2019-07-31)


### Features

* generate higher quality SourceMaps ([#109](https://github.com/webpack-contrib/terser-webpack-plugin/issues/109)) ([9d777f0](https://github.com/webpack-contrib/terser-webpack-plugin/commit/9d777f0))

## [1.3.0](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.2.4...v1.3.0) (2019-05-24)


### Features

* update terser to 4 version ([#97](https://github.com/webpack-contrib/terser-webpack-plugin/issues/97)) ([15d1595](https://github.com/webpack-contrib/terser-webpack-plugin/commit/15d1595))



### [1.2.4](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.2.3...v1.2.4) (2019-05-15)


### Bug Fixes

* disable parallel on WSL due bugs ([#90](https://github.com/webpack-contrib/terser-webpack-plugin/issues/90)) ([d9533dd](https://github.com/webpack-contrib/terser-webpack-plugin/commit/d9533dd))
* fallback for cache directory ([#86](https://github.com/webpack-contrib/terser-webpack-plugin/issues/86)) ([3cdd2ed](https://github.com/webpack-contrib/terser-webpack-plugin/commit/3cdd2ed))



<a name="1.2.3"></a>
## [1.2.3](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.2.2...v1.2.3) (2019-02-25)


### Bug Fixes

* invalidate cache after changing node version ([675edfd](https://github.com/webpack-contrib/terser-webpack-plugin/commit/675edfd))



<a name="1.2.2"></a>
## [1.2.2](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.2.1...v1.2.2) (2019-02-04)


### Bug Fixes

* cannot read property 'minify' of undefined   ([#69](https://github.com/webpack-contrib/terser-webpack-plugin/issues/69)) ([0593d7c](https://github.com/webpack-contrib/terser-webpack-plugin/commit/0593d7c))



<a name="1.2.1"></a>
## [1.2.1](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.2.0...v1.2.1) (2018-12-27)


### Bug Fixes

* don't crash when no extracted comments ([#49](https://github.com/webpack-contrib/terser-webpack-plugin/issues/49)) ([efad586](https://github.com/webpack-contrib/terser-webpack-plugin/commit/efad586))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.1.0...v1.2.0) (2018-12-22)


### Bug Fixes

* `chunks` is a `Set` in webpack@5 ([#19](https://github.com/webpack-contrib/terser-webpack-plugin/issues/19)) ([df8c425](https://github.com/webpack-contrib/terser-webpack-plugin/commit/df8c425))
* catch `work-farm` errors ([#35](https://github.com/webpack-contrib/terser-webpack-plugin/issues/35)) ([2bdcd38](https://github.com/webpack-contrib/terser-webpack-plugin/commit/2bdcd38))
* dedupe extracted comments ([#40](https://github.com/webpack-contrib/terser-webpack-plugin/issues/40)) ([7f4a159](https://github.com/webpack-contrib/terser-webpack-plugin/commit/7f4a159))
* more consistent cache ([#43](https://github.com/webpack-contrib/terser-webpack-plugin/issues/43)) ([36f5f3c](https://github.com/webpack-contrib/terser-webpack-plugin/commit/36f5f3c))
* regenerate `contenthash` when assets was uglified ([#44](https://github.com/webpack-contrib/terser-webpack-plugin/issues/44)) ([7e6f8b1](https://github.com/webpack-contrib/terser-webpack-plugin/commit/7e6f8b1))


### Features

* `chunkFilter` option for filtering chunks ([#38](https://github.com/webpack-contrib/terser-webpack-plugin/issues/38)) ([7ffe57c](https://github.com/webpack-contrib/terser-webpack-plugin/commit/7ffe57c))
* uglify `mjs` by default ([#39](https://github.com/webpack-contrib/terser-webpack-plugin/issues/39)) ([1644620](https://github.com/webpack-contrib/terser-webpack-plugin/commit/1644620))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.0.1...v1.1.0) (2018-09-14)


### Bug Fixes

* extract comment conditions is case insensitivity ([19e1e43](https://github.com/webpack-contrib/terser-webpack-plugin/commit/19e1e43))


### Features

* full coverage schema options validation ([#8](https://github.com/webpack-contrib/terser-webpack-plugin/issues/8)) ([68e531e](https://github.com/webpack-contrib/terser-webpack-plugin/commit/68e531e))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.0.1...v1.0.2) (2018-08-16)


### Internal

* migrate from `@webpack-contrib/schema-utils` to `schema-utils` ([a5432da](https://github.com/webpack-contrib/terser-webpack-plugin/commit/a5432da))

<a name="1.0.1"></a>
## [1.0.1](https://github.com/webpack-contrib/terser-webpack-plugin/compare/v1.0.0...v1.0.1) (2018-08-15)


### Bug Fixes

* `cpus` length in a chroot environment (`os.cpus()`) ([#4](https://github.com/webpack-contrib/terser-webpack-plugin/issues/4)) ([9375646](https://github.com/webpack-contrib/terser-webpack-plugin/commit/9375646))



<a name="1.0.0"></a>
# 1.0.0 (2018-08-02)

Initial publish release

# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

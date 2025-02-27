# Change Log

## 1.1.4

### Patch Changes

- Updated dependencies
  [[`ff7c3676`](https://github.com/chakra-ui/chakra-ui/commit/ff7c36764650dc7f01957c417eae1ec8ce356495),
  [`6830c0e3`](https://github.com/chakra-ui/chakra-ui/commit/6830c0e36959ebd76ce1991dd89d7303ce33b0d0),
  [`09f028e4`](https://github.com/chakra-ui/chakra-ui/commit/09f028e4f2539d51b1c9ac7f3aec422ee6848fa3)]:
  - @chakra-ui/styled-system@1.4.0

## 1.1.3

### Patch Changes

- [`a9807b33`](https://github.com/chakra-ui/chakra-ui/commit/a9807b334477ac9ecd7f3637c0ff7d5fb5c46639)
  [#2753](https://github.com/chakra-ui/chakra-ui/pull/2753) Thanks
  [@TimKolberger](https://github.com/TimKolberger)! - Restored TypeScript
  autocomplete for chakra component props in Jetbrains IDEs.

## 1.1.2

### Patch Changes

- Updated dependencies
  [[`5cef5de4`](https://github.com/chakra-ui/chakra-ui/commit/5cef5de4f45cd58f7a29436335543cb5b40c0d70)]:
  - @chakra-ui/styled-system@1.3.1

## 1.1.1

### Patch Changes

- Updated dependencies
  [[`a0e0bd9a`](https://github.com/chakra-ui/chakra-ui/commit/a0e0bd9a5d45fe08887f8df8d3eccc84951578df),
  [`4fa07745`](https://github.com/chakra-ui/chakra-ui/commit/4fa077453a5c2165b695198c57366f3cc6506c37)]:
  - @chakra-ui/styled-system@1.3.0

## 1.1.0

### Minor Changes

- [`730a2da1`](https://github.com/chakra-ui/chakra-ui/commit/730a2da19b652614bc051b9f80313d211b22d1de)
  Thanks [@segunadebayo](https://github.com/segunadebayo)! - ## Pin Input

  ### 🐛 Bug Fix

  - Fix issue where copy-paste doesn't work for pin-input

  ## Number Input

  ### 🐛 Bug Fix

  - Fix issue where number input doesn't work when using with form libraries
    that use `ref` as entry point to setting initial values (e.g React hook
    form).

    We improved `useNumberInput` to sync the initial values in the `ref` passed
    to `NumberInputField` with the internal state.

  ## System

  ### 🚀 Feature

  Add support for custom `shouldForwardProp` function in the `chakra` factory
  function.

### Patch Changes

- Updated dependencies
  [[`e73878ee`](https://github.com/chakra-ui/chakra-ui/commit/e73878ee686c11d3f94ad6ac61b19ae9508d75a5),
  [`609ac595`](https://github.com/chakra-ui/chakra-ui/commit/609ac595568799c9f2c38ccbc9ef44fdc7393baa)]:
  - @chakra-ui/utils@1.0.2
  - @chakra-ui/styled-system@1.2.0
  - @chakra-ui/color-mode@1.0.2

## 1.0.2

### Patch Changes

- [`653f3dd6`](https://github.com/chakra-ui/chakra-ui/commit/653f3dd6f30a17e366c069666acbfd9eddb11936)
  [#2709](https://github.com/chakra-ui/chakra-ui/pull/2709) Thanks
  [@with-heart](https://github.com/with-heart)! - Added default empty object
  argument values for the `props` and `opts` arguments of `useStyleConfig`.
- Updated dependencies
  [[`127baa0f`](https://github.com/chakra-ui/chakra-ui/commit/127baa0f1926bf1f8ace6f46cfdc08606fe9d347)]:
  - @chakra-ui/styled-system@1.1.1

## 1.0.1

### Patch Changes

- Updated dependencies
  [[`586ce3c1`](https://github.com/chakra-ui/chakra-ui/commit/586ce3c12bb3508027c36811233c539eeeb55256),
  [`5c482483`](https://github.com/chakra-ui/chakra-ui/commit/5c482483ce24fc798540c9792a15e06772eae213)]:
  - @chakra-ui/styled-system@1.1.0
  - @chakra-ui/utils@1.0.1
  - @chakra-ui/color-mode@1.0.1

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0 (2020-11-13)

**Note:** Version bump only for package @chakra-ui/system

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-rc.8 (2020-10-29)

### Bug Fixes

- **toast:** allow custom render in update
  ([eb8bff9](https://github.com/chakra-ui/chakra-ui/commit/eb8bff911e6ec9de0165ab1e8f5ca10d5e022459)),
  closes [#2362](https://github.com/chakra-ui/chakra-ui/issues/2362)

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-rc.7 (2020-10-25)

**Note:** Version bump only for package @chakra-ui/system

# 1.0.0-rc.6 (2020-10-25)

**Note:** Version bump only for package @chakra-ui/system

# 1.0.0-rc.5 (2020-09-27)

**Note:** Version bump only for package @chakra-ui/system

# 1.0.0-rc.4 (2020-09-25)

**Note:** Version bump only for package @chakra-ui/system

# 1.0.0-rc.3 (2020-08-30)

**Note:** Version bump only for package @chakra-ui/system

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-rc.2 (2020-08-09)

**Note:** Version bump only for package @chakra-ui/system

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-rc.1](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/system@1.0.0-rc.0...@chakra-ui/system@1.0.0-rc.1) (2020-08-06)

### Bug Fixes

- **variables:** drop unused imports
  ([552b2e9](https://github.com/chakra-ui/chakra-ui/commit/552b2e9b7510963db509a5724af5361ef07c8ecb))
- connect drawer its correct theming
  ([9ed9d3a](https://github.com/chakra-ui/chakra-ui/commit/9ed9d3aea959f38198b1ba0d48c24686630aee90))

### Features

- **system:** extend props
  ([645c683](https://github.com/chakra-ui/chakra-ui/commit/645c683ef71ad5ef5b3aa60e7e2880853df1683f))
- added cookieStorageManager. still WIP
  ([9a9c305](https://github.com/chakra-ui/chakra-ui/commit/9a9c305d9c4ae7b5b44271e633c8a3bad81df066))
- cleaned up some storageManager code. set color mode cookie to expire after a
  year
  ([d7ca15e](https://github.com/chakra-ui/chakra-ui/commit/d7ca15e6be9b393ed42cfc1a394d2872d7a8e5df))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-rc.0](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/system@1.0.0-next.7...@chakra-ui/system@1.0.0-rc.0) (2020-07-26)

**Note:** Version bump only for package @chakra-ui/system

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-next.7](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/system@1.0.0-next.6...@chakra-ui/system@1.0.0-next.7) (2020-07-26)

### Bug Fixes

- give priority to props overrides
  ([f2fe955](https://github.com/chakra-ui/chakra-ui/commit/f2fe9553373da4734712a90fec284eea7a951dfb))
- null exception for style config
  ([c28ba5a](https://github.com/chakra-ui/chakra-ui/commit/c28ba5ac075cc5c8f30806e269ed36632c01d6ea))

### Features

- add support for single and multipart config
  ([a13d0f8](https://github.com/chakra-ui/chakra-ui/commit/a13d0f8a3d97405bde6acba1c4fc126677154a8b))

### Reverts

- breakpoint handling
  ([f3ee5f1](https://github.com/chakra-ui/chakra-ui/commit/f3ee5f15c48da242c4d4d43de0dc67ff7664c81e))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-next.6](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/system@1.0.0-next.5...@chakra-ui/system@1.0.0-next.6) (2020-07-15)

**Note:** Version bump only for package @chakra-ui/system

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-next.5](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/system@1.0.0-next.4...@chakra-ui/system@1.0.0-next.5) (2020-07-15)

### Performance Improvements

- improve system pkg
  ([eebec47](https://github.com/chakra-ui/chakra-ui/commit/eebec479c6c40324833cc1beed0b540c4687d805))
- some more improvements
  ([daf94a5](https://github.com/chakra-ui/chakra-ui/commit/daf94a50f6abc9773c9552ec08b5ebf5f1cb05b9))
- some more improvements
  ([3382bab](https://github.com/chakra-ui/chakra-ui/commit/3382bab224f29f082d2a9ba2b4b2721257fbdfac))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-next.4 (2020-07-01)

### Bug Fixes

- [#891](https://github.com/chakra-ui/chakra-ui/issues/891)
  ([e107acc](https://github.com/chakra-ui/chakra-ui/commit/e107acc8487898a965b0d695c1da71f46fc56d5e))
- bug i created :)
  ([352eece](https://github.com/chakra-ui/chakra-ui/commit/352eece27b7df1a061e9d365d9b54e6beeeffd90))
- resolver functions for css
  ([ffb4cfd](https://github.com/chakra-ui/chakra-ui/commit/ffb4cfd52e1aaabaebab7b548bf570b01daaf5a6))
- style issue with progress bar
  ([b0e430a](https://github.com/chakra-ui/chakra-ui/commit/b0e430a5adffd88a56cce10555bad89d61ad686b))
- ts issue with sx prop
  ([d3b1340](https://github.com/chakra-ui/chakra-ui/commit/d3b1340cb255937927b4d4c56ce218141570b951))
- update border-radius style prop and fix w style prop
  ([09df03f](https://github.com/chakra-ui/chakra-ui/commit/09df03fba7321ae50d4d3107aaf89b1956ed3463))
- update core css support
  ([499a6a1](https://github.com/chakra-ui/chakra-ui/commit/499a6a1ddf3111b2f528b1661f17896bf6948abd))

### Features

- add support for inline-variant
  ([67bf6ad](https://github.com/chakra-ui/chakra-ui/commit/67bf6adf2bf8f3270b75f83382c2acbb8db07155))
- add support for line-clamp
  ([1173ca6](https://github.com/chakra-ui/chakra-ui/commit/1173ca6974e8b9fcf27aa301bd1accece07ca5fc))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-next.3 (2020-06-28)

### Bug Fixes

- [#891](https://github.com/chakra-ui/chakra-ui/issues/891)
  ([e107acc](https://github.com/chakra-ui/chakra-ui/commit/e107acc8487898a965b0d695c1da71f46fc56d5e))
- bug i created :)
  ([352eece](https://github.com/chakra-ui/chakra-ui/commit/352eece27b7df1a061e9d365d9b54e6beeeffd90))
- resolver functions for css
  ([ffb4cfd](https://github.com/chakra-ui/chakra-ui/commit/ffb4cfd52e1aaabaebab7b548bf570b01daaf5a6))
- style issue with progress bar
  ([b0e430a](https://github.com/chakra-ui/chakra-ui/commit/b0e430a5adffd88a56cce10555bad89d61ad686b))
- ts issue with sx prop
  ([d3b1340](https://github.com/chakra-ui/chakra-ui/commit/d3b1340cb255937927b4d4c56ce218141570b951))
- update border-radius style prop and fix w style prop
  ([09df03f](https://github.com/chakra-ui/chakra-ui/commit/09df03fba7321ae50d4d3107aaf89b1956ed3463))
- update core css support
  ([499a6a1](https://github.com/chakra-ui/chakra-ui/commit/499a6a1ddf3111b2f528b1661f17896bf6948abd))

### Features

- add support for inline-variant
  ([67bf6ad](https://github.com/chakra-ui/chakra-ui/commit/67bf6adf2bf8f3270b75f83382c2acbb8db07155))
- add support for line-clamp
  ([1173ca6](https://github.com/chakra-ui/chakra-ui/commit/1173ca6974e8b9fcf27aa301bd1accece07ca5fc))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-next.2 (2020-06-21)

### Bug Fixes

- [#891](https://github.com/chakra-ui/chakra-ui/issues/891)
  ([e107acc](https://github.com/chakra-ui/chakra-ui/commit/e107acc8487898a965b0d695c1da71f46fc56d5e))
- bug i created :)
  ([352eece](https://github.com/chakra-ui/chakra-ui/commit/352eece27b7df1a061e9d365d9b54e6beeeffd90))
- resolver functions for css
  ([ffb4cfd](https://github.com/chakra-ui/chakra-ui/commit/ffb4cfd52e1aaabaebab7b548bf570b01daaf5a6))
- style issue with progress bar
  ([b0e430a](https://github.com/chakra-ui/chakra-ui/commit/b0e430a5adffd88a56cce10555bad89d61ad686b))
- update border-radius style prop and fix w style prop
  ([09df03f](https://github.com/chakra-ui/chakra-ui/commit/09df03fba7321ae50d4d3107aaf89b1956ed3463))
- update core css support
  ([499a6a1](https://github.com/chakra-ui/chakra-ui/commit/499a6a1ddf3111b2f528b1661f17896bf6948abd))

### Features

- add support for inline-variant
  ([67bf6ad](https://github.com/chakra-ui/chakra-ui/commit/67bf6adf2bf8f3270b75f83382c2acbb8db07155))
- add support for line-clamp
  ([1173ca6](https://github.com/chakra-ui/chakra-ui/commit/1173ca6974e8b9fcf27aa301bd1accece07ca5fc))

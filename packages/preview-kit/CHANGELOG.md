<!-- markdownlint-disable --><!-- textlint-disable -->

# 📓 Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.0.1](https://github.com/sanity-io/preview-kit/compare/v4.0.0...v4.0.1) (2023-11-20)

### Bug Fixes

- **deps:** Update dependency lru-cache to v10.0.3 ([#683](https://github.com/sanity-io/preview-kit/issues/683)) ([3c41c56](https://github.com/sanity-io/preview-kit/commit/3c41c56071c650562d628ead9b90633a40b3a598))

## [4.0.0](https://github.com/sanity-io/preview-kit/compare/v3.2.11...v4.0.0) (2023-11-17)

### ⚠ BREAKING CHANGES

- **csm:** remove deprecated `createTranscoder` API
- **csm:** remove deprecated `mapToEditLinks` API
- **client:** remove deprecated `mapToEditLinks` API

### Bug Fixes

- **client:** remove deprecated `mapToEditLinks` API ([f650780](https://github.com/sanity-io/preview-kit/commit/f650780e48c931df1e2fd85523d0dceef855a5ac))
- **csm:** remove deprecated `createTranscoder` API ([11d9e3b](https://github.com/sanity-io/preview-kit/commit/11d9e3b34e4d3ef784eb92b396e28f9fe6504419))
- **csm:** remove deprecated `mapToEditLinks` API ([c19c033](https://github.com/sanity-io/preview-kit/commit/c19c033e0e3dd3c4112a0659fafddd7f7b2986f4))

## [3.2.11](https://github.com/sanity-io/preview-kit/compare/v3.2.10...v3.2.11) (2023-11-17)

### Bug Fixes

- correct deprecation message ([4e8094b](https://github.com/sanity-io/preview-kit/commit/4e8094b8b886e450002d5fad6bf7bc113760aeb2))

## [3.2.10](https://github.com/sanity-io/preview-kit/compare/v3.2.9...v3.2.10) (2023-11-17)

### Bug Fixes

- deprecate `createTranscoder` ([8cff732](https://github.com/sanity-io/preview-kit/commit/8cff732beca00f90ea72954d1deee4717b0c2ede))
- deprecate `mapToEditLinks` ([5585eb2](https://github.com/sanity-io/preview-kit/commit/5585eb2b696f4509c1011680db3b450dceeaa2b3))
- mark `createClient` as deprecated, use `@sanity/client/stega` instead ([e5206cc](https://github.com/sanity-io/preview-kit/commit/e5206cc94ee5687af2444af72c4682f7fd93909c))
- remove unused code ([7eb5924](https://github.com/sanity-io/preview-kit/commit/7eb59247511824400f4d74a05f4b4b6c2b6f677c))
- stop exporting internal `encodeJsonPathToUriComponent` API ([42485df](https://github.com/sanity-io/preview-kit/commit/42485df13fbba46f876b4811854de5a48766e867))
- stop exporting internal `parseNormalisedJsonPath` API ([9451119](https://github.com/sanity-io/preview-kit/commit/945111918955bd3e98732f8fed283ea976d5e634))
- stop exporting internal `resolveMapping` API ([987fe1c](https://github.com/sanity-io/preview-kit/commit/987fe1c45965483386ab8e2f42334da8d7e2eab4))
- stop exporting internal `walkMap` API ([3587003](https://github.com/sanity-io/preview-kit/commit/3587003b286f27324b73ac6f8fbe00b7b17bc568))
- stop exporting internals for live query ([6497d23](https://github.com/sanity-io/preview-kit/commit/6497d23d346ccd9bbd2e3abbdd1704b79839530b))

## [3.2.9](https://github.com/sanity-io/preview-kit/compare/v3.2.8...v3.2.9) (2023-11-16)

### Bug Fixes

- add `@sanity/preview-kit-compat` ([5801d15](https://github.com/sanity-io/preview-kit/commit/5801d15f676906817251f7fb6060388e4409fafd))

## [3.2.8](https://github.com/sanity-io/preview-kit/compare/v3.2.7...v3.2.8) (2023-11-16)

### Bug Fixes

- **client:** add support for `SanityStegaClient` ([070c2c8](https://github.com/sanity-io/preview-kit/commit/070c2c88f5dc46f5c75d101a1aace0499743acaa))
- **client:** use `@sanity/client/stega` under the hood ([55c65ff](https://github.com/sanity-io/preview-kit/commit/55c65ff92fb36dfecaa4ab829711a25f7134c76f))
- **deps:** update dependency @sanity/client to ^6.8.6 (main) ([#664](https://github.com/sanity-io/preview-kit/issues/664)) ([e0ca080](https://github.com/sanity-io/preview-kit/commit/e0ca0805f1d9740b700853f57d8787bbcfae25b0))
- **deps:** Update dependency lru-cache to v10.0.2 (main) ([#663](https://github.com/sanity-io/preview-kit/issues/663)) ([ceb7061](https://github.com/sanity-io/preview-kit/commit/ceb706161e998621ebeadd1e3e71184b48a4b73b))
- **turbo:** use `applySourceDocuments` from `@sanity/client/csm` ([ce8463b](https://github.com/sanity-io/preview-kit/commit/ce8463b8ebf66b9fa785fda0cacece8543d93274))

## [3.2.7](https://github.com/sanity-io/preview-kit/compare/v3.2.6...v3.2.7) (2023-11-06)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.7.1 (main) ([#661](https://github.com/sanity-io/preview-kit/issues/661)) ([d16cfbf](https://github.com/sanity-io/preview-kit/commit/d16cfbfcc783dbed9b00187003b3924e5977fe5a))

## [3.2.6](https://github.com/sanity-io/preview-kit/compare/v3.2.5...v3.2.6) (2023-10-19)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.7.0 ([#622](https://github.com/sanity-io/preview-kit/issues/622)) ([aa994a0](https://github.com/sanity-io/preview-kit/commit/aa994a0ae0e26d0f3e634a3749f5828b74c0dc5e))

## [3.2.5](https://github.com/sanity-io/preview-kit/compare/v3.2.4...v3.2.5) (2023-10-19)

### Bug Fixes

- **csm:** export `walkMap` ([32e05d2](https://github.com/sanity-io/preview-kit/commit/32e05d2a49af0814f65c3712326366490a43d012))

## [3.2.4](https://github.com/sanity-io/preview-kit/compare/v3.2.3...v3.2.4) (2023-10-16)

### Bug Fixes

- export experimental csm utils ([ffef068](https://github.com/sanity-io/preview-kit/commit/ffef06809849f59b8422ae969ff0559b5baf2236))

## [3.2.3](https://github.com/sanity-io/preview-kit/compare/v3.2.2...v3.2.3) (2023-10-16)

### Bug Fixes

- fully support `use client` ([c87b9a6](https://github.com/sanity-io/preview-kit/commit/c87b9a6f6b923d59d670c7b1ad7a11aa93e31737))

## [3.2.2](https://github.com/sanity-io/preview-kit/compare/v3.2.1...v3.2.2) (2023-10-16)

### Bug Fixes

- resolve `use client` regression ([cd1e4e4](https://github.com/sanity-io/preview-kit/commit/cd1e4e4d1af5ec13d838a2f0aaca2bebced51308))

## [3.2.1](https://github.com/sanity-io/preview-kit/compare/v3.2.0...v3.2.1) (2023-10-12)

### Bug Fixes

- **deps:** Update dependency @sanity/eventsource to v5.0.1 ([#585](https://github.com/sanity-io/preview-kit/issues/585)) ([3c6ab69](https://github.com/sanity-io/preview-kit/commit/3c6ab69140d0f7ed62b073dc206ffa7baa2271a7))
- **deps:** Update dependency @sanity/groq-store to v4.1.3 ([#604](https://github.com/sanity-io/preview-kit/issues/604)) ([1288430](https://github.com/sanity-io/preview-kit/commit/12884309159e090c4308fa520cabba676481be12))

## [3.2.0](https://github.com/sanity-io/preview-kit/compare/v3.1.6...v3.2.0) (2023-10-12)

### Features

- **csm:** support `_type` ([#597](https://github.com/sanity-io/preview-kit/issues/597)) ([38c678b](https://github.com/sanity-io/preview-kit/commit/38c678b7cf226cb91972d608d26e9209493b3921))

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.4.11 ([#570](https://github.com/sanity-io/preview-kit/issues/570)) ([de9cf81](https://github.com/sanity-io/preview-kit/commit/de9cf811cbe7b16844751a3402e25be305812312))
- **deps:** Update dependency @sanity/groq-store to v4.1.2 ([#601](https://github.com/sanity-io/preview-kit/issues/601)) ([377459f](https://github.com/sanity-io/preview-kit/commit/377459f2c5d1cb3890570ecbe32dfc9c72781c73))

## [3.1.6](https://github.com/sanity-io/preview-kit/compare/v3.1.5...v3.1.6) (2023-08-23)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to v4.1.1 ([3e5e388](https://github.com/sanity-io/preview-kit/commit/3e5e388eee60cc64a06f449db8d333f25bf20b4c))

## [3.1.5](https://github.com/sanity-io/preview-kit/compare/v3.1.4...v3.1.5) (2023-08-22)

### Bug Fixes

- reduce subscriptionThrottleMs from `50ms` to `1ms` ([14fe012](https://github.com/sanity-io/preview-kit/commit/14fe0122bf045ae98ab055f071f4b24247eeb133))

## [3.1.4](https://github.com/sanity-io/preview-kit/compare/v3.1.3...v3.1.4) (2023-08-18)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.4.9 ([#533](https://github.com/sanity-io/preview-kit/issues/533)) ([c830f70](https://github.com/sanity-io/preview-kit/commit/c830f70088be118446fa5a7640053a6a71d1178a))

## [3.1.3](https://github.com/sanity-io/preview-kit/compare/v3.1.2...v3.1.3) (2023-08-18)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.4.8 ([#527](https://github.com/sanity-io/preview-kit/issues/527)) ([e161f42](https://github.com/sanity-io/preview-kit/commit/e161f42a7a8445f84bda9093e9973f0bfc2bb864))

## [3.1.2](https://github.com/sanity-io/preview-kit/compare/v3.1.1...v3.1.2) (2023-08-17)

### Bug Fixes

- **docs:** add usage for `LiveQuery` ([d0d84c7](https://github.com/sanity-io/preview-kit/commit/d0d84c7cb655b73ce60351cf3e44a3044dd31245))

## [3.1.1](https://github.com/sanity-io/preview-kit/compare/v3.1.0...v3.1.1) (2023-08-17)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.4.7 ([#522](https://github.com/sanity-io/preview-kit/issues/522)) ([cfe03e7](https://github.com/sanity-io/preview-kit/commit/cfe03e7b31ffa05e6375a776307ebc5e80ae904a))

## [3.1.0](https://github.com/sanity-io/preview-kit/compare/v3.0.3...v3.1.0) (2023-08-14)

### Features

- add `use client` directive to `LiveQuery` ([e8c30c4](https://github.com/sanity-io/preview-kit/commit/e8c30c4f847f6329c2ad74b654142e48386bb324))

## [3.0.3](https://github.com/sanity-io/preview-kit/compare/v3.0.2...v3.0.3) (2023-08-14)

### Bug Fixes

- remove experimental internals ([633bf81](https://github.com/sanity-io/preview-kit/commit/633bf81760405dc536f71579788c3149336163a6))

## [3.0.2](https://github.com/sanity-io/preview-kit/compare/v3.0.1...v3.0.2) (2023-08-14)

### Bug Fixes

- **LiveQueryProvider:** add convenience export for lazy loading ([e27487e](https://github.com/sanity-io/preview-kit/commit/e27487e8375414cb0eb9bfdfe6c498d28d7c6a0a))

## [3.0.1](https://github.com/sanity-io/preview-kit/compare/v3.0.0...v3.0.1) (2023-08-14)

### Bug Fixes

- **live-query:** relax typings for `as` ([2ff3dac](https://github.com/sanity-io/preview-kit/commit/2ff3dacfd221d4d81a45916521b52e460c7383df))

## [3.0.0](https://github.com/sanity-io/preview-kit/compare/v2.6.0...v3.0.0) (2023-08-14)

### ⚠ BREAKING CHANGES

- remove deprecated `useListeningQuery ` and `useListeningQueryStatus` hooks
- remove deprecated `/groq-store` export

### Features

- add `LiveQuery` component ([#495](https://github.com/sanity-io/preview-kit/issues/495)) ([66efd7d](https://github.com/sanity-io/preview-kit/commit/66efd7dac5befafb52b8d83061127946646ea561))

### Bug Fixes

- remove deprecated `/groq-store` export ([240c17b](https://github.com/sanity-io/preview-kit/commit/240c17bc2ec9b19f318cd5da50cb28450c48ba00))
- remove deprecated `useListeningQuery ` and `useListeningQueryStatus` hooks ([ea3efd2](https://github.com/sanity-io/preview-kit/commit/ea3efd21415125ceeeece38411d46fc92c6bb5e3))

## [2.6.0](https://github.com/sanity-io/preview-kit/compare/v2.5.0...v2.6.0) (2023-08-13)

### Features

- **LiveQueryProvider:** add `token` prop ([616ca7e](https://github.com/sanity-io/preview-kit/commit/616ca7eb5e998a338daffcc6c370d91989cd5b08))

### Bug Fixes

- **deps:** bump `@sanity/client` ([9cd0b47](https://github.com/sanity-io/preview-kit/commit/9cd0b478d98b8b58d1d4e8d84c4354495ce01a7e))

## [2.5.0](https://github.com/sanity-io/preview-kit/compare/v2.4.12...v2.5.0) (2023-08-12)

### Features

- add `useIsEnabled` hook ([d0f6b2d](https://github.com/sanity-io/preview-kit/commit/d0f6b2dbdf4d5d1403dd1e912f2b627f002eb25b))

## [2.4.12](https://github.com/sanity-io/preview-kit/compare/v2.4.11...v2.4.12) (2023-08-11)

### Bug Fixes

- add back `ClientQueryParams` type export ([172ec03](https://github.com/sanity-io/preview-kit/commit/172ec03870c3cc50617c2427625669abfe1812d2))

## [2.4.11](https://github.com/sanity-io/preview-kit/compare/v2.4.10...v2.4.11) (2023-08-11)

### Bug Fixes

- better lazy loading of the provider ([#489](https://github.com/sanity-io/preview-kit/issues/489)) ([c37fd93](https://github.com/sanity-io/preview-kit/commit/c37fd935f0a5c01e2b555e093e11c60c1fc67019))
- **deps:** update dependency @sanity/client to ^6.4.5 ([#482](https://github.com/sanity-io/preview-kit/issues/482)) ([9bbf18c](https://github.com/sanity-io/preview-kit/commit/9bbf18cb0e05a6c4336c90776297d1c52aedada3))
- **deps:** Update dependency @sanity/groq-store to v4.0.4 ([#483](https://github.com/sanity-io/preview-kit/issues/483)) ([7b14059](https://github.com/sanity-io/preview-kit/commit/7b140594985e2d15f2f0be2c678b0e8633b12144))
- **deps:** Update dependency lru-cache to v10.0.1 ([#490](https://github.com/sanity-io/preview-kit/issues/490)) ([5ec4035](https://github.com/sanity-io/preview-kit/commit/5ec40355b574b1ae0b226d1f14371ad9e4986d3e))

## [2.4.10](https://github.com/sanity-io/preview-kit/compare/v2.4.9...v2.4.10) (2023-08-09)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^6.4.4 ([#478](https://github.com/sanity-io/preview-kit/issues/478)) ([b85eb63](https://github.com/sanity-io/preview-kit/commit/b85eb6342b24029ea8b8c9cc7b75b1a94204e14c))

## [2.4.9](https://github.com/sanity-io/preview-kit/compare/v2.4.8...v2.4.9) (2023-08-07)

### Bug Fixes

- **deps:** update dependency @sanity/client to v6.4.3 ([#470](https://github.com/sanity-io/preview-kit/issues/470)) ([f0149a3](https://github.com/sanity-io/preview-kit/commit/f0149a388a968ba5133af5adf742cb62f4b39e06))

## [2.4.8](https://github.com/sanity-io/preview-kit/compare/v2.4.7...v2.4.8) (2023-08-07)

### Bug Fixes

- add `node.module` export condition ([2dd6e6c](https://github.com/sanity-io/preview-kit/commit/2dd6e6ccc7f10defc3b311e40bd8bdf2a06b3bca))
- **deps:** update dependency @sanity/client to ^6.4.2 ([b3c464d](https://github.com/sanity-io/preview-kit/commit/b3c464de1622529065b37c5db2481c2821dfd504))
- **deps:** Update dependency @sanity/groq-store to v4.0.3 ([#468](https://github.com/sanity-io/preview-kit/issues/468)) ([4113bf7](https://github.com/sanity-io/preview-kit/commit/4113bf736d9555345c50cdb16492b4bd97221362))

## [2.4.7](https://github.com/sanity-io/preview-kit/compare/v2.4.6...v2.4.7) (2023-08-04)

### Bug Fixes

- **deps:** Update dependency @sanity/groq-store to v4.0.2 ([#456](https://github.com/sanity-io/preview-kit/issues/456)) ([47ed3ef](https://github.com/sanity-io/preview-kit/commit/47ed3ef88b10f4f64e5d2657c950981ebfa49733))

## [2.4.6](https://github.com/sanity-io/preview-kit/compare/v2.4.5...v2.4.6) (2023-08-04)

### Bug Fixes

- **deps:** update dependency `@sanity/groq-store` to v4.0.1 ([0fe3efa](https://github.com/sanity-io/preview-kit/commit/0fe3efab08f7f2f2a7fb6b9cf3241e25198e0fcd))

## [2.4.5](https://github.com/sanity-io/preview-kit/compare/v2.4.4...v2.4.5) (2023-08-04)

### Bug Fixes

- **deps:** update dependency mendoza to v3.0.2 ([de0c962](https://github.com/sanity-io/preview-kit/commit/de0c962a8500164605662c72cd1a6d7d751de260))

## [2.4.4](https://github.com/sanity-io/preview-kit/compare/v2.4.3...v2.4.4) (2023-08-04)

### Bug Fixes

- **deps:** Update dependency @sanity/groq-store to v3 ([#454](https://github.com/sanity-io/preview-kit/issues/454)) ([3b1282c](https://github.com/sanity-io/preview-kit/commit/3b1282ce2870d7e534a717e2447f3af0b35ce16b))
- **deps:** update dependency `@sanity/groq-store` to v4.0.0 ([a9bee66](https://github.com/sanity-io/preview-kit/commit/a9bee662252756378475a0f8c10d1e958aad5eae))
- **deps:** Update dependency mendoza to v3 ([#453](https://github.com/sanity-io/preview-kit/issues/453)) ([e9f96a9](https://github.com/sanity-io/preview-kit/commit/e9f96a91728eeea8a1d4ae1a5d0b64d6de847825))
- **deps:** update dependency mendoza to v3.0.1 ([5c6781b](https://github.com/sanity-io/preview-kit/commit/5c6781b0e62cbb58df5a31a155207446abe4565c))

## [2.4.3](https://github.com/sanity-io/preview-kit/compare/v2.4.2...v2.4.3) (2023-08-04)

### Bug Fixes

- **deps:** Update dependency @sanity/groq-store to v2.3.4 ([#451](https://github.com/sanity-io/preview-kit/issues/451)) ([5a0ca39](https://github.com/sanity-io/preview-kit/commit/5a0ca3924a81f10516053d97caeee58f2de29c91))
- **deps:** Update dependency mendoza to v2.1.2 ([#452](https://github.com/sanity-io/preview-kit/issues/452)) ([d91b0eb](https://github.com/sanity-io/preview-kit/commit/d91b0eb6510f8bcc0920397f8dcc4df8ff298720))

## [2.4.2](https://github.com/sanity-io/preview-kit/compare/v2.4.1...v2.4.2) (2023-08-04)

### Bug Fixes

- reduce logger noise ([4fd91d2](https://github.com/sanity-io/preview-kit/commit/4fd91d2fa5e2d81d9396f7c987bcd5f1555fceca))

## [2.4.1](https://github.com/sanity-io/preview-kit/compare/v2.4.0...v2.4.1) (2023-08-04)

### Bug Fixes

- **deps:** bump `@sanity/client` to v6.4 ([d2c31fb](https://github.com/sanity-io/preview-kit/commit/d2c31fbe8e901e51ef27d214c91a447f35be5ff7))
- **deps:** Update dependency @sanity/groq-store to v2.3.3 ([#447](https://github.com/sanity-io/preview-kit/issues/447)) ([a97b334](https://github.com/sanity-io/preview-kit/commit/a97b334ddd4537b12df7c4d3e58b621d36b38acd))
- **deps:** update peer dependency @sanity/client to v6.2.0 ([273d094](https://github.com/sanity-io/preview-kit/commit/273d09458b7edc9f48fd123e6d87b3f72ad303c0))
- don't warn on missing CSM on API endpoints that don't have them ([ac79eb9](https://github.com/sanity-io/preview-kit/commit/ac79eb90135b252bbe76b1ba8d5e83d004133ad1))
- gracefully handle a missing `studioUrl` ([48b7d8d](https://github.com/sanity-io/preview-kit/commit/48b7d8d9844a4b1b1d53af8e814edd6b23b9fa5a))

## [2.4.0](https://github.com/sanity-io/preview-kit/compare/v2.3.3...v2.4.0) (2023-08-02)

### Features

- **csm:** extracts content source maps encoding ([#429](https://github.com/sanity-io/preview-kit/issues/429)) ([7d93ab8](https://github.com/sanity-io/preview-kit/commit/7d93ab823fda3f5c1ccbea4462c3d71cee139faf))

## [2.3.3](https://github.com/sanity-io/preview-kit/compare/v2.3.2...v2.3.3) (2023-07-13)

### Bug Fixes

- **deps:** update non-major ([#423](https://github.com/sanity-io/preview-kit/issues/423)) ([dc100f4](https://github.com/sanity-io/preview-kit/commit/dc100f486cc5df0c271f1be4823100e550c57c77))

## [2.3.2](https://github.com/sanity-io/preview-kit/compare/v2.3.1...v2.3.2) (2023-07-13)

### Bug Fixes

- enable npm provenance publishing ([5ccbed7](https://github.com/sanity-io/preview-kit/commit/5ccbed72f6506c90990ca9733be801663edd00b4))

## [2.3.1](https://github.com/sanity-io/preview-kit/compare/v2.3.0...v2.3.1) (2023-07-06)

### Bug Fixes

- **docs:** stage changes to README for click to edit ([#408](https://github.com/sanity-io/preview-kit/issues/408)) ([6316e22](https://github.com/sanity-io/preview-kit/commit/6316e22b31b6c6f6812098539113314211eadd49))

## [2.3.0](https://github.com/sanity-io/preview-kit/compare/v2.2.4...v2.3.0) (2023-06-29)

### Features

- use `perspective` features ([#389](https://github.com/sanity-io/preview-kit/issues/389)) ([4139e28](https://github.com/sanity-io/preview-kit/commit/4139e286834c385e4de60d46784a6e30cd3b5549))

### Bug Fixes

- allow `encodeSourceMap` to be a string ([79d681e](https://github.com/sanity-io/preview-kit/commit/79d681e9524969f656f1a40321919a04c88e45d4))
- **deps:** update `@sanity/client` to v6.1.3 ([b149be6](https://github.com/sanity-io/preview-kit/commit/b149be6cc9fad319516edc4c8ca61a7afee850a0))
- improve logger message ([3facebf](https://github.com/sanity-io/preview-kit/commit/3facebf657431e03277787694561a92e550bcdaa))
- make `studioUrl` optional ([3ffa49f](https://github.com/sanity-io/preview-kit/commit/3ffa49f23564b652788ef3f1070f40d16ab8d6f1))
- only forward valid `client` options ([e9b0494](https://github.com/sanity-io/preview-kit/commit/e9b049436d3e415a9a537dab58e98a04bd899978))
- set `sanity.preview-kit.turbo` tag by default for CSM live preview ([0fac392](https://github.com/sanity-io/preview-kit/commit/0fac3927c81183d06ab48758c53098daf21a34ac))
- set `sanity.preview-kit` tag by default ([c1c91e0](https://github.com/sanity-io/preview-kit/commit/c1c91e0a43e6e82c47766eeaf78bb90db5b1d268))
- support `cache.listen = false` ([57de7cc](https://github.com/sanity-io/preview-kit/commit/57de7cc4e6a61abf774de9f5a6df87de9013ff8d))

## [2.2.4](https://github.com/sanity-io/preview-kit/compare/v2.2.3...v2.2.4) (2023-06-28)

### Bug Fixes

- **deps:** update non-major ([#401](https://github.com/sanity-io/preview-kit/issues/401)) ([a78891c](https://github.com/sanity-io/preview-kit/commit/a78891cc8535f4d4addabd9ed17d3c989daa9b27))

## [2.2.3](https://github.com/sanity-io/preview-kit/compare/v2.2.2...v2.2.3) (2023-06-27)

### Bug Fixes

- **deps:** update non-major ([#397](https://github.com/sanity-io/preview-kit/issues/397)) ([a0112cf](https://github.com/sanity-io/preview-kit/commit/a0112cfcee6565f545d7da7110a9df0ffaa086ee))

## [2.2.2](https://github.com/sanity-io/preview-kit/compare/v2.2.1...v2.2.2) (2023-06-21)

### Bug Fixes

- make sure cancelled requests don't throw ([27143f1](https://github.com/sanity-io/preview-kit/commit/27143f1987cba1bc6219a7e8f7a0d0dd29e1b0ef))

## [2.2.1](https://github.com/sanity-io/preview-kit/compare/v2.2.0...v2.2.1) (2023-06-21)

### Bug Fixes

- apply `includeTypes` to `count` query ([3eefa35](https://github.com/sanity-io/preview-kit/commit/3eefa35080ee2e2772ab8043223c6ae5fb1fb717))

## [2.2.0](https://github.com/sanity-io/preview-kit/compare/v2.1.1...v2.2.0) (2023-06-20)

### Features

- add `LiveQueryProvider` & `useLiveQuery` ([1e460b3](https://github.com/sanity-io/preview-kit/commit/1e460b397243e3792f123185be0f442dbaa7f43d))

### Bug Fixes

- **deps:** update dependency lru-cache to v10 ([#383](https://github.com/sanity-io/preview-kit/issues/383)) ([2cb326c](https://github.com/sanity-io/preview-kit/commit/2cb326c10b2997631e544cbe4f3bb353e7b94a81))

## [2.1.1](https://github.com/sanity-io/preview-kit/compare/v2.1.0...v2.1.1) (2023-06-10)

### Bug Fixes

- throw error if `initialSnapshot` is undefined ([1ed2bf6](https://github.com/sanity-io/preview-kit/commit/1ed2bf68b54cbebbe9ea69363d96b8ae1381b17c))

## [2.1.0](https://github.com/sanity-io/preview-kit/compare/v2.0.0...v2.1.0) (2023-06-09)

### Features

- add `useListeningQueryStatus` hook ([#378](https://github.com/sanity-io/preview-kit/issues/378)) ([1f3da96](https://github.com/sanity-io/preview-kit/commit/1f3da96c188301893cedba3bf4e0d959a6c2762b))

### Bug Fixes

- remove unused `groq` dependency ([5159973](https://github.com/sanity-io/preview-kit/commit/51599738cddbe1cf01a51e2a45fadd7ac41a7a63))

## [2.0.0](https://github.com/sanity-io/preview-kit/compare/v1.5.4...v2.0.0) (2023-06-09)

### ⚠ BREAKING CHANGES

- `definePreview` and `<PreviewSuspense>` are replaced by `<GroqStoreProvider>`.
- `usePreview` is replaced by `useListeningQuery`.
- `@sanity/client` is now a peer dependency.

[The migration guide outlines every breaking change and how to migrate your code](https://github.com/sanity-io/preview-kit/blob/main/MIGRATION.md)

### Features

- Live previews are now easier to build, have a much shorter bootup time and you no longer need separate preview versions of components as `useListeningQuery` can be disabled for production modes.
- `token` are set in a single location, `<GroqStoreProvider>`, instead of prop-drilled to every preview component.
- `Suspense` boundaries now optional, you only need them if you're code-splitting `GroqStoreProvider` with `React.lazy`

### Bug Fixes

- Preview hooks no longer perform queries while the initial dataset export is streaming, as this could lead to incomplete query results and unexpected cases of `null`.

## [1.5.2](https://github.com/sanity-io/preview-kit/compare/v1.5.1...v1.5.2) (2023-05-03)

### Bug Fixes

- make `encodeSourceMap` optional ([d03717b](https://github.com/sanity-io/preview-kit/commit/d03717b7c651bb94017ce86412a18b28de4f4d50))

## [1.5.1](https://github.com/sanity-io/preview-kit/compare/v1.5.0...v1.5.1) (2023-05-03)

### Bug Fixes

- add release notes ([8a401e0](https://github.com/sanity-io/preview-kit/commit/8a401e0ecc865d52305b15dcae8ac881f6567b96))

## [1.5.0](https://github.com/sanity-io/preview-kit/compare/v1.4.1...v1.5.0) (2023-05-03)

### Introducing Content Source Maps

> **Note**
>
> Content Source Maps are available for select [Sanity enterprise customers](https://www.sanity.io/enterprise?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch). [Contact our sales team for more information.](https://www.sanity.io/contact/sales?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch)

![](https://i.imgur.com/wt95U5Q.jpg)

Content Source Maps are an optional layer of contextual metadata sent with queries to enable use cases such as [Visual Editing](https://www.sanity.io/blog/visual-editing-sanity-vercel?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch), tracing content lineage, and more. Our implementation of Content Source Maps are based on an [open standard posted on GitHub](https://github.com/sanity-io/content-source-maps), and you can read [the API documentation here](https://#https://www.sanity.io/docs/content-source-maps?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch).

## [1.4.1](https://github.com/sanity-io/preview-kit/compare/v1.4.0...v1.4.1) (2023-05-03)

### Bug Fixes

- **docs:** add README.md to published package ([fdf29af](https://github.com/sanity-io/preview-kit/commit/fdf29afb58c26b637539b90538c90d8757885087))

## [1.4.0](https://github.com/sanity-io/preview-kit/compare/v1.3.8...v1.4.0) (2023-04-11)

### Features

- expose listen config for non-live previews ([#298](https://github.com/sanity-io/preview-kit/issues/298)) ([e5a1d56](https://github.com/sanity-io/preview-kit/commit/e5a1d56c7e04f86c4eb6e90b635bf909decfc9cc))

## [1.3.8](https://github.com/sanity-io/preview-kit/compare/v1.3.7...v1.3.8) (2023-03-24)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to v2.1.0 ([#283](https://github.com/sanity-io/preview-kit/issues/283)) ([e94fce2](https://github.com/sanity-io/preview-kit/commit/e94fce20305ded323b740eda9a02f37bcc4c2a84))
- replace `event-source-polyfill` with `@sanity/eventsource` ([#286](https://github.com/sanity-io/preview-kit/issues/286)) ([11eac9e](https://github.com/sanity-io/preview-kit/commit/11eac9ea591cc321f317c46faa6732e185e1c2a7))

## [1.3.7](https://github.com/sanity-io/preview-kit/compare/v1.3.6...v1.3.7) (2023-03-22)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to v2.0.9 ([#280](https://github.com/sanity-io/preview-kit/issues/280)) ([95cb42a](https://github.com/sanity-io/preview-kit/commit/95cb42a6dfbe9a2e9261dcca9434f38a8f9e9312))

## [1.3.6](https://github.com/sanity-io/preview-kit/compare/v1.3.5...v1.3.6) (2023-03-08)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^2.0.8 ([#262](https://github.com/sanity-io/preview-kit/issues/262)) ([900c9fe](https://github.com/sanity-io/preview-kit/commit/900c9fef6d4e13b0eb379aa38ff09885fef8139e))

## [1.3.5](https://github.com/sanity-io/preview-kit/compare/v1.3.4...v1.3.5) (2023-03-06)

### Bug Fixes

- **deps:** update dependency @sanity/pkg-utils to ^2.2.8 ([#256](https://github.com/sanity-io/preview-kit/issues/256)) ([7f730a1](https://github.com/sanity-io/preview-kit/commit/7f730a192accdf08f2ab23c753ec27f1aa54149a))

## [1.3.4](https://github.com/sanity-io/preview-kit/compare/v1.3.3...v1.3.4) (2023-02-14)

### Bug Fixes

- bump `@sanity/groq-store` to `2.0.7` ([cad23ec](https://github.com/sanity-io/preview-kit/commit/cad23ec00aa450923e84f06130f6103cecc52003))

## [1.3.3](https://github.com/sanity-io/preview-kit/compare/v1.3.2...v1.3.3) (2023-02-02)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^2.0.6 ([#222](https://github.com/sanity-io/preview-kit/issues/222)) ([434f850](https://github.com/sanity-io/preview-kit/commit/434f8506e4810bdc6cf2ee43e71d471add73ca62))
- **deps:** update dependency @types/event-source-polyfill to ^1.0.1 ([#214](https://github.com/sanity-io/preview-kit/issues/214)) ([50d1cce](https://github.com/sanity-io/preview-kit/commit/50d1ccef56e06c0be6fd82701c1be9cfbe701e95))

## [1.3.2](https://github.com/sanity-io/preview-kit/compare/v1.3.1...v1.3.2) (2023-01-23)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^2.0.5 ([#209](https://github.com/sanity-io/preview-kit/issues/209)) ([d4cc3bc](https://github.com/sanity-io/preview-kit/commit/d4cc3bc55a216d35d182424b2864eaa884908713))

## [1.3.1](https://github.com/sanity-io/preview-kit/compare/v1.3.0...v1.3.1) (2023-01-19)

### Bug Fixes

- prevent SSR hydration errors ([f67a8ff](https://github.com/sanity-io/preview-kit/commit/f67a8ff914273940b801e0d692bd9025fe3a685a))

## [1.3.0](https://github.com/sanity-io/preview-kit/compare/v1.2.24...v1.3.0) (2023-01-19)

### Features

- add optional `serverSnapshot` to `usePreview` ([#199](https://github.com/sanity-io/preview-kit/issues/199)) ([1dc68f8](https://github.com/sanity-io/preview-kit/commit/1dc68f8d58853a664bc33751c118fc6d0882d84b))

## [1.2.24](https://github.com/sanity-io/preview-kit/compare/v1.2.23...v1.2.24) (2023-01-18)

### Bug Fixes

- export \_preloadQuery for easier customization ([f3f5743](https://github.com/sanity-io/preview-kit/commit/f3f574352faa7d2eedf0379c0321ad3eced75cf2)), closes [#63](https://github.com/sanity-io/preview-kit/issues/63)
- make `overlayDrafts` configurable ([87de43d](https://github.com/sanity-io/preview-kit/commit/87de43d2be2dd05650bb60db14b0c6ccfc8a811b))

## [1.2.23](https://github.com/sanity-io/preview-kit/compare/v1.2.22...v1.2.23) (2023-01-14)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^2.0.3 ([#175](https://github.com/sanity-io/preview-kit/issues/175)) ([58ba8f3](https://github.com/sanity-io/preview-kit/commit/58ba8f3056354e9b5bed4fa7647865cca8ab5047))
- **deps:** update dependency @sanity/groq-store to ^2.0.4 ([#184](https://github.com/sanity-io/preview-kit/issues/184)) ([a867ade](https://github.com/sanity-io/preview-kit/commit/a867adead8e531528a2b5a8e0a9d63de12483706))
- **deps:** update devdependencies (non-major) to ^3.2.3 ([#177](https://github.com/sanity-io/preview-kit/issues/177)) ([002524e](https://github.com/sanity-io/preview-kit/commit/002524ebfe601f141739d51c4ddd74a345b7b301))

## [1.2.22](https://github.com/sanity-io/preview-kit/compare/v1.2.21...v1.2.22) (2023-01-12)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^2.0.2 ([#164](https://github.com/sanity-io/preview-kit/issues/164)) ([bee2092](https://github.com/sanity-io/preview-kit/commit/bee2092f6b854898c2a18e0b9f0832ff629ee4ad))

## [1.2.21](https://github.com/sanity-io/preview-kit/compare/v1.2.20...v1.2.21) (2023-01-12)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to v2 ([#160](https://github.com/sanity-io/preview-kit/issues/160)) ([aab6ca4](https://github.com/sanity-io/preview-kit/commit/aab6ca44775ec40f43a2969f2eadd9936cfae546))

## [1.2.20](https://github.com/sanity-io/preview-kit/compare/v1.2.19...v1.2.20) (2023-01-12)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.1.5 ([#157](https://github.com/sanity-io/preview-kit/issues/157)) ([2c93b47](https://github.com/sanity-io/preview-kit/commit/2c93b47b01521feb52291013c44147b508778c62))

## [1.2.19](https://github.com/sanity-io/preview-kit/compare/v1.2.18...v1.2.19) (2023-01-08)

### Bug Fixes

- improve ESM support ([e4efc52](https://github.com/sanity-io/preview-kit/commit/e4efc52c4a2c38fc3f1ed977f0afd3b2b0f1ba4c))

## [1.2.18](https://github.com/sanity-io/preview-kit/compare/v1.2.17...v1.2.18) (2023-01-07)

### Bug Fixes

- **build:** auto-generate Node ESM wrapper ([#128](https://github.com/sanity-io/preview-kit/issues/128)) ([98a8ece](https://github.com/sanity-io/preview-kit/commit/98a8eced1613300fd629d50a6c37ab8bb681a888))
- **deps:** update dependency @sanity/pkg-utils to ^2.1.1 ([#135](https://github.com/sanity-io/preview-kit/issues/135)) ([4a06b58](https://github.com/sanity-io/preview-kit/commit/4a06b585c0bfdb104cb9484a9ed6f60955bb5261))

## [1.2.17](https://github.com/sanity-io/preview-kit/compare/v1.2.16...v1.2.17) (2023-01-02)

### Bug Fixes

- **build:** include `node` directory ([#127](https://github.com/sanity-io/preview-kit/issues/127)) ([b9268b0](https://github.com/sanity-io/preview-kit/commit/b9268b0ba3312d3575f531f57554fa542b891bb7))

## [1.2.16](https://github.com/sanity-io/preview-kit/compare/v1.2.15...v1.2.16) (2023-01-02)

### Bug Fixes

- improve Node.js ESM runtime support ([5392720](https://github.com/sanity-io/preview-kit/commit/53927208ce6025ab2a1378166822d20c0b1bf500))

## [1.2.15](https://github.com/sanity-io/preview-kit/compare/v1.2.14...v1.2.15) (2022-12-30)

### Bug Fixes

- **deps:** update devdependencies (non-major) ([#120](https://github.com/sanity-io/preview-kit/issues/120)) ([ab892a0](https://github.com/sanity-io/preview-kit/commit/ab892a0b43f4ed8667b1e4f38e9256c040518465))

## [1.2.14](https://github.com/sanity-io/preview-kit/compare/v1.2.13...v1.2.14) (2022-12-23)

### Bug Fixes

- **deps:** lock file maintenance ([#112](https://github.com/sanity-io/preview-kit/issues/112)) ([09101a3](https://github.com/sanity-io/preview-kit/commit/09101a3d1ceb1dd3abc153586ba23084cc653654))

## [1.2.13](https://github.com/sanity-io/preview-kit/compare/v1.2.12...v1.2.13) (2022-12-23)

### Bug Fixes

- **deps:** update dependency @sanity/pkg-utils to ^2.0.1 ([#110](https://github.com/sanity-io/preview-kit/issues/110)) ([be2ac8a](https://github.com/sanity-io/preview-kit/commit/be2ac8ae585e5b5e1c29dbc75320a4e7f0fc5654))

## [1.2.12](https://github.com/sanity-io/preview-kit/compare/v1.2.11...v1.2.12) (2022-12-23)

### Bug Fixes

- **deps:** update dependency @sanity/pkg-utils to v2 ([#107](https://github.com/sanity-io/preview-kit/issues/107)) ([8cbf92c](https://github.com/sanity-io/preview-kit/commit/8cbf92c7c6d005ac2c87c74872da874482028f85))

## [1.2.11](https://github.com/sanity-io/preview-kit/compare/v1.2.10...v1.2.11) (2022-12-18)

### Bug Fixes

- **deps:** update dependency suspend-react to ^0.0.9 ([#95](https://github.com/sanity-io/preview-kit/issues/95)) ([e08db7c](https://github.com/sanity-io/preview-kit/commit/e08db7c832c2c0fbc075aa4058f2f8881ddc0751))

## [1.2.10](https://github.com/sanity-io/preview-kit/compare/v1.2.9...v1.2.10) (2022-12-06)

### Bug Fixes

- **deps:** update dependency @sanity/pkg-utils to ^1.20.1 ([#52](https://github.com/sanity-io/preview-kit/issues/52)) ([40f29d7](https://github.com/sanity-io/preview-kit/commit/40f29d7c0a558e390ba14e0028634ed09aa8c64e))

## [1.2.9](https://github.com/sanity-io/preview-kit/compare/v1.2.8...v1.2.9) (2022-11-25)

### Bug Fixes

- call `store.close` on `beforeunload` ([3ba6ec3](https://github.com/sanity-io/preview-kit/commit/3ba6ec3aa0aaedd62b81e4ab76a925e1a903379d))

## [1.2.8](https://github.com/sanity-io/preview-kit/compare/v1.2.7...v1.2.8) (2022-11-18)

### Bug Fixes

- support `swcMinify` in NextJS 13 ([#29](https://github.com/sanity-io/preview-kit/issues/29)) ([0c3ecec](https://github.com/sanity-io/preview-kit/commit/0c3ecec4f300c239cc3814ab5364bbb68194964e))

## [1.2.7](https://github.com/sanity-io/preview-kit/compare/v1.2.6...v1.2.7) (2022-11-16)

### Bug Fixes

- set `subscriptionThrottleMs` to `10` by default ([43f60ad](https://github.com/sanity-io/preview-kit/commit/43f60ad1c4fbe254a320c90c92ae165ef926f5f8))

## [1.2.6](https://github.com/sanity-io/preview-kit/compare/v1.2.5...v1.2.6) (2022-11-16)

### Bug Fixes

- add `documentLimit` to the `PreviewConfig` public type ([7fe1e9c](https://github.com/sanity-io/preview-kit/commit/7fe1e9c2799e53300476e264c5f57c185403bad6))

## [1.2.5](https://github.com/sanity-io/preview-kit/compare/v1.2.4...v1.2.5) (2022-11-16)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.1.2 ([#20](https://github.com/sanity-io/preview-kit/issues/20)) ([7c95b10](https://github.com/sanity-io/preview-kit/commit/7c95b105c678b931136137b526536d35cf744ceb))
- set `documentLimit` to 3000, like `next-sanity` ([b4dcbe2](https://github.com/sanity-io/preview-kit/commit/b4dcbe2264afb29a35562529f0de4ff7f6ff2f01))

## [1.2.4](https://github.com/sanity-io/preview-kit/compare/v1.2.3...v1.2.4) (2022-11-16)

### Bug Fixes

- **README:** add create-react-app examples ([3b6d705](https://github.com/sanity-io/preview-kit/commit/3b6d7057bbaae946407578cdbfc339a4c7721971))
- **README:** add remix example ([9e3a262](https://github.com/sanity-io/preview-kit/commit/9e3a2628d0110e349c0c67f289ddf2b64d9f586d))

## [1.2.3](https://github.com/sanity-io/preview-kit/compare/v1.2.2...v1.2.3) (2022-11-15)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.1.1 ([#15](https://github.com/sanity-io/preview-kit/issues/15)) ([bae9f2f](https://github.com/sanity-io/preview-kit/commit/bae9f2f78fa312767f2b77bf89613bfef4d8aaa8))

## [1.2.2](https://github.com/sanity-io/preview-kit/compare/v1.2.1...v1.2.2) (2022-11-15)

### Bug Fixes

- issue preventing remix from lazy loading `event-source-polyfill` ([e44483f](https://github.com/sanity-io/preview-kit/commit/e44483fa967bc7e572cf0c3897ebf444366d3290))
- validate `usePreview` is only called clientside ([0aeaa76](https://github.com/sanity-io/preview-kit/commit/0aeaa76ddcaa5798fd1d6eca3062127828acadf0))

## [1.2.1](https://github.com/sanity-io/preview-kit/compare/v1.2.0...v1.2.1) (2022-11-15)

### Bug Fixes

- add 'use client' directive ([00d3758](https://github.com/sanity-io/preview-kit/commit/00d375886c9acdec86b1fa0a19d484731a3b368c))
- no longer require `useMemo` on `params` ([f8fdf5b](https://github.com/sanity-io/preview-kit/commit/f8fdf5ba48e368fc178ba4c0fe0fd7005284134f))

## [1.2.0](https://github.com/sanity-io/preview-kit/compare/v1.1.3...v1.2.0) (2022-11-15)

### Features

- add support for fetching subset of dataset by type ([#9](https://github.com/sanity-io/preview-kit/issues/9)) ([fcb084d](https://github.com/sanity-io/preview-kit/commit/fcb084de983fba308683a6488a186cc2e275320e))

## [1.2.0-add-type-allowlist.1](https://github.com/sanity-io/preview-kit/compare/v1.1.3...v1.2.0-add-type-allowlist.1) (2022-11-14)

### Features

- add support for fetching subset of dataset by type ([768a6da](https://github.com/sanity-io/preview-kit/commit/768a6dab73a8cfd2e5e8f23b4f7bbeac09cc16b3))

## [1.1.3](https://github.com/sanity-io/preview-kit/compare/v1.1.2...v1.1.3) (2022-11-11)

### Bug Fixes

- infinite render loop when providing `params` ([232cf61](https://github.com/sanity-io/preview-kit/commit/232cf61a4cc185f3861d1640e9666beec35f8ee4))

## [1.1.2](https://github.com/sanity-io/preview-kit/compare/v1.1.1...v1.1.2) (2022-11-11)

### Bug Fixes

- publish package with public scope ([e4da8f6](https://github.com/sanity-io/preview-kit/commit/e4da8f6986db737325f5081abc1f3abede80e28d))

## [1.1.1](https://github.com/sanity-io/preview-kit/compare/v1.1.0...v1.1.1) (2022-11-11)

### Bug Fixes

- publish `checkAuth` fixes ([5e6d270](https://github.com/sanity-io/preview-kit/commit/5e6d270ed8faf41d77551c66815d151de59c37c1))

## [1.1.0](https://github.com/sanity-io/preview-kit/compare/v1.0.0...v1.1.0) (2022-11-11)

### Features

- add `onPublicAccessOnly` event ([242f5b2](https://github.com/sanity-io/preview-kit/commit/242f5b2cb51401472c388752ed18876d6b10bc0a))

## 1.0.0 (2022-11-11)

### Features

- add `definePreview` API ([a505793](https://github.com/sanity-io/preview-kit/commit/a505793d336e7bf801f783c46a74cbed35e071f9))
- add `PreviewSuspense` ([2072640](https://github.com/sanity-io/preview-kit/commit/2072640d60817cc36f00f81e7617f1d14eb1eac1))
- add lazy loading utils ([b361111](https://github.com/sanity-io/preview-kit/commit/b3611116f761e60f903fa910bc45c407542a93b5))

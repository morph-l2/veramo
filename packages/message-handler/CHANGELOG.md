# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [6.0.0](https://github.com/decentralized-identity/veramo/compare/v5.6.0...v6.0.0) (2024-04-02)


### Bug Fixes

* export const plugin schemas instead of defaults ([#1327](https://github.com/decentralized-identity/veramo/issues/1327)) ([7896cea](https://github.com/decentralized-identity/veramo/commit/7896ceaf2c79993eee44e46950814bea74bfe647)), closes [#1318](https://github.com/decentralized-identity/veramo/issues/1318) [#1317](https://github.com/decentralized-identity/veramo/issues/1317) [#1315](https://github.com/decentralized-identity/veramo/issues/1315)


### Code Refactoring

* generate plugin schemas as TS instead of JSON ([#1315](https://github.com/decentralized-identity/veramo/issues/1315)) ([65c2d4b](https://github.com/decentralized-identity/veramo/commit/65c2d4bc814daa9a3a89f4f7b8e8c6973b8ce2f0)), closes [#1254](https://github.com/decentralized-identity/veramo/issues/1254)


### BREAKING CHANGES

* The `plugin.schema.json` files are now generated as `plugin.schema.ts`.





# [5.6.0](https://github.com/decentralized-identity/veramo/compare/v5.5.3...v5.6.0) (2024-01-16)


### Features

* **remote-client:** allow dynamic headers param for AgentRestClient constructor ([#1314](https://github.com/decentralized-identity/veramo/issues/1314)) ([1b8a0a2](https://github.com/decentralized-identity/veramo/commit/1b8a0a2718dd63492ad3a312a6ebe5f6e7849935)), closes [#1313](https://github.com/decentralized-identity/veramo/issues/1313)





## [5.5.3](https://github.com/decentralized-identity/veramo/compare/v5.5.2...v5.5.3) (2023-10-09)


### Bug Fixes

* use DIF URLs in packages ([#1271](https://github.com/decentralized-identity/veramo/issues/1271)) ([3dfc601](https://github.com/decentralized-identity/veramo/commit/3dfc6014cdee7902c59d8db76b4c8507b870f227))





# [5.5.0](https://github.com/uport-project/veramo/compare/v5.4.1...v5.5.0) (2023-09-19)


### Bug Fixes

* **did-provider-key:** use compressed keys for creating Secp256k1 did:key ([#1217](https://github.com/uport-project/veramo/issues/1217)) ([ba8f6f5](https://github.com/uport-project/veramo/commit/ba8f6f5b9b701e57af86491504ecd209ca0c1c1d)), closes [#1213](https://github.com/uport-project/veramo/issues/1213)





## [5.4.1](https://github.com/uport-project/veramo/compare/v5.4.0...v5.4.1) (2023-08-04)


### Bug Fixes

* **ci:** benign change meant to tag all packages for another patch release ([#1211](https://github.com/uport-project/veramo/issues/1211)) ([41b5c90](https://github.com/uport-project/veramo/commit/41b5c90277171b7b38c5cf49ca01db5cf75b6300))





# [5.4.0](https://github.com/uport-project/veramo/compare/v5.3.0...v5.4.0) (2023-08-01)

**Note:** Version bump only for package @veramo/message-handler





# [5.3.0](https://github.com/uport-project/veramo/compare/v5.2.0...v5.3.0) (2023-07-27)

**Note:** Version bump only for package @veramo/message-handler





## [5.1.2](https://github.com/uport-project/veramo/compare/v5.1.1...v5.1.2) (2023-02-25)

**Note:** Version bump only for package @veramo/message-handler





# [5.1.0](https://github.com/uport-project/veramo/compare/v5.0.0...v5.1.0) (2023-02-24)

**Note:** Version bump only for package @veramo/message-handler





# [5.0.0](https://github.com/uport-project/veramo/compare/v4.3.0...v5.0.0) (2023-02-09)


### Build System

* convert veramo modules to ESM instead of CommonJS ([#1103](https://github.com/uport-project/veramo/issues/1103)) ([b5cea3c](https://github.com/uport-project/veramo/commit/b5cea3c0d80d900a47bd1d9eea68f84b70a35e7b)), closes [#1099](https://github.com/uport-project/veramo/issues/1099)


### Features

* isolate `core-types` package from `core` ([#1116](https://github.com/uport-project/veramo/issues/1116)) ([ba7a303](https://github.com/uport-project/veramo/commit/ba7a303de91cf4cc568a3af1ddf8ca98ed022e9f))


### BREAKING CHANGES

* this is a breaking change as modules will have to be imported differently: 
* https://www.typescriptlang.org/docs/handbook/esm-node.html
* https://nodejs.org/api/esm.html
* https://caniuse.com/?search=modules

test(did-provider-ion): skip a couple of tests that fail with unreasonable errors
chore: use ubuntu-latest on CI
fix: temporarily remove puppeteer tests
fix: use craco for test-react-app to enable babel config
test: fix unit and integration tests (browser tests still broken)
fix: fix some build issues that prevented tests from working
fix: missing deps flagged by pnpm





# [4.3.0](https://github.com/uport-project/veramo/compare/v4.2.0...v4.3.0) (2023-01-27)


### Features

* **did-comm:** add trust ping protocol ([#1080](https://github.com/uport-project/veramo/issues/1080)) ([fb22e63](https://github.com/uport-project/veramo/commit/fb22e632ef6dcce6a7dfec9a229c7be4d6d5c894))
* **did-comm:** support DIDComm Messaging attachments ([#1087](https://github.com/uport-project/veramo/issues/1087)) ([6679574](https://github.com/uport-project/veramo/commit/66795742a01d5390ad083610efd28a8fe59fb3a3)), closes [#612](https://github.com/uport-project/veramo/issues/612)





# [4.2.0](https://github.com/uport-project/veramo/compare/v4.1.2...v4.2.0) (2022-12-05)


### Bug Fixes

* **deps:** bump dependencies ([701b8ed](https://github.com/uport-project/veramo/commit/701b8edf981ea11c7ddb6a81d2817dbbdbb022f3))





## [4.1.1](https://github.com/uport-project/veramo/compare/v4.1.0...v4.1.1) (2022-11-01)

**Note:** Version bump only for package @veramo/message-handler





# [4.1.0](https://github.com/uport-project/veramo/compare/v4.0.2...v4.1.0) (2022-10-31)

**Note:** Version bump only for package @veramo/message-handler





# [4.0.0](https://github.com/uport-project/veramo/compare/v3.1.5...v4.0.0) (2022-09-22)


### Bug Fixes

* **did-resolver:** use interface `Resolvable` instead of the `Resolver` class ([9c2e59f](https://github.com/uport-project/veramo/commit/9c2e59f3f23f808511c6c0e8e440b4d53ba5cb00))
* update and fix inline documentation of all exported types ([#921](https://github.com/uport-project/veramo/issues/921)) ([63e64e0](https://github.com/uport-project/veramo/commit/63e64e0e2693808c4704dca8cc511dc0bab3f3b1))


### Features

* **credential-ld:** add support for browser environments ([#916](https://github.com/uport-project/veramo/issues/916)) ([435e4d2](https://github.com/uport-project/veramo/commit/435e4d260b1774f96b182c1a75ab2f1c993f2291))





## [3.1.3](https://github.com/uport-project/veramo/compare/v3.1.2...v3.1.3) (2022-06-01)

**Note:** Version bump only for package @veramo/message-handler





# [3.1.0](https://github.com/uport-project/veramo/compare/v3.0.0...v3.1.0) (2021-11-12)

**Note:** Version bump only for package @veramo/message-handler





# [3.0.0](https://github.com/uport-project/veramo/compare/v2.1.3...v3.0.0) (2021-09-20)

**Note:** Version bump only for package @veramo/message-handler





# [2.1.0](https://github.com/uport-project/veramo/compare/v2.0.1...v2.1.0) (2021-08-11)

**Note:** Version bump only for package @veramo/message-handler





# [2.0.0](https://github.com/uport-project/veramo/compare/v1.2.2...v2.0.0) (2021-07-14)

**Note:** Version bump only for package @veramo/message-handler





# [1.2.0](https://github.com/uport-project/veramo/compare/v1.1.2...v1.2.0) (2021-04-27)

**Note:** Version bump only for package @veramo/message-handler





# [1.1.0](https://github.com/uport-project/veramo/compare/v1.0.1...v1.1.0) (2021-01-26)

**Note:** Version bump only for package @veramo/message-handler





## 1.0.1 (2020-12-18)

**Note:** Version bump only for package @veramo/message-handler

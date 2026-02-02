# Changelog

## [1.8.0](https://github.com/justinwlin/actual-mcp/compare/v1.7.0...v1.8.0) (2026-02-01)


### Features

* add account management tools (create, update, close) ([157aafd](https://github.com/justinwlin/actual-mcp/commit/157aafdcfcd8eb903057a7a75708a4bdc8f1b189))
* add create-transaction tool ([#72](https://github.com/justinwlin/actual-mcp/issues/72)) ([f8cd573](https://github.com/justinwlin/actual-mcp/commit/f8cd573be318536d9d3ea9730942d5fb5fb89757))
* add OAuth 2.0 authentication support ([eff4494](https://github.com/justinwlin/actual-mcp/commit/eff4494144398bffba700ef88acf3f65c3660034))
* add run-bank-sync tool ([#93](https://github.com/justinwlin/actual-mcp/issues/93)) ([61b67d7](https://github.com/justinwlin/actual-mcp/commit/61b67d72e3789999cfe4aec78181deffffaabb99))
* Add streamable HTTP transport for Codex (Trigger Release) ([#54](https://github.com/justinwlin/actual-mcp/issues/54)) ([ec23551](https://github.com/justinwlin/actual-mcp/commit/ec235517ad3a1d205fc31e02bbcd0800cb9b92ef))
* Add Vitest unit testing framework for src/core module ([#14](https://github.com/justinwlin/actual-mcp/issues/14)) ([80d3d80](https://github.com/justinwlin/actual-mcp/commit/80d3d8028fec938ed06f03b60b234be19b3881d1))
* **auth:** add JWT validation support for OAuth authentication ([cc38d33](https://github.com/justinwlin/actual-mcp/commit/cc38d333ad61986d5b6adb533b7963a74334d068))
* Connect to actual budget server that has different encryption key ([#33](https://github.com/justinwlin/actual-mcp/issues/33)) ([f828ad4](https://github.com/justinwlin/actual-mcp/commit/f828ad4f56e73416ec82f5c55efd98bea315c196)), closes [#28](https://github.com/justinwlin/actual-mcp/issues/28)
* create PR checks ([#16](https://github.com/justinwlin/actual-mcp/issues/16)) ([b60ea97](https://github.com/justinwlin/actual-mcp/commit/b60ea973ddffc9b93a32679beb61d616decb0455))
* Enhance transaction handling with enriched data and improved input parsing ([#39](https://github.com/justinwlin/actual-mcp/issues/39)) ([74f1270](https://github.com/justinwlin/actual-mcp/commit/74f12709ee9efef7840dec15bd1c1424cb09f5f2))
* ESLint Introduction. Typings and fixes ([#15](https://github.com/justinwlin/actual-mcp/issues/15)) ([8f33ad8](https://github.com/justinwlin/actual-mcp/commit/8f33ad88c91ab3636fa95a53337cc8cc952a5773))
* Fix monthly summary with transfers calculations ([#41](https://github.com/justinwlin/actual-mcp/issues/41)) ([af59c41](https://github.com/justinwlin/actual-mcp/commit/af59c41d43ea3e85b10e475becc3f62273e8ebd0))
* get accounts tool ([#6](https://github.com/justinwlin/actual-mcp/issues/6)) ([9008dbe](https://github.com/justinwlin/actual-mcp/commit/9008dbe8a94e83b822f28a1c0190f281882b7fcc))
* github pipelines ([#9](https://github.com/justinwlin/actual-mcp/issues/9)) ([e9ae9ff](https://github.com/justinwlin/actual-mcp/commit/e9ae9ff2a53c19ba9065804c64fb257bfbc3a8f7))
* New tools for categories, payees, and rules ([#18](https://github.com/justinwlin/actual-mcp/issues/18)) ([fa9bbd2](https://github.com/justinwlin/actual-mcp/commit/fa9bbd2752e2a04ef5cc82e752100f02b0af63f3))
* Refactoring of tools & types ([#5](https://github.com/justinwlin/actual-mcp/issues/5)) ([af9d185](https://github.com/justinwlin/actual-mcp/commit/af9d1850ca76315185f36331f758597f510a4528))
* Return id in get-transactions ([#34](https://github.com/justinwlin/actual-mcp/issues/34)) ([e15bb33](https://github.com/justinwlin/actual-mcp/commit/e15bb33866106954a904f9ce1ebccf76983c95ea)), closes [#32](https://github.com/justinwlin/actual-mcp/issues/32)
* **rules:** add Zod validation and upgrade @actual-app/api to 25.12.0 ([ecf8341](https://github.com/justinwlin/actual-mcp/commit/ecf83418f7b80a9cb90ba961747b98a4dc7d563a))
* Update Actual to 25.10.0 ([#35](https://github.com/justinwlin/actual-mcp/issues/35)) ([1bd89ea](https://github.com/justinwlin/actual-mcp/commit/1bd89ea4dd3fb72e8641f8eff018f41b3d8db6a7))


### Bug Fixes

* **auth:** honor CLI port and public issuer URL in OAuth config ([d7e616a](https://github.com/justinwlin/actual-mcp/commit/d7e616a26abc22366db31c2b8d707ee934ea1553))
* **auth:** remove custom OAuth scope for provider compatibility ([c88eeae](https://github.com/justinwlin/actual-mcp/commit/c88eeaec8af45df215bdeec26cf8e18696755848))
* **auth:** use standard OIDC scopes (openid, email) ([a056ec3](https://github.com/justinwlin/actual-mcp/commit/a056ec35d4caa70c5d9b4cb3616b606e4bbbb655))
* correct repo url in README.md ([#42](https://github.com/justinwlin/actual-mcp/issues/42)) ([41b4070](https://github.com/justinwlin/actual-mcp/commit/41b4070e4c44394a15b15947a3b799de0d7e8ef4))
* deployment ([1c57a9d](https://github.com/justinwlin/actual-mcp/commit/1c57a9d980bbf5724121763372a30a202e961273))
* deployment steps ([66a0311](https://github.com/justinwlin/actual-mcp/commit/66a0311dccfa8f1cdb47052c74e21f070c0e7863))
* **deps:** update dependency dotenv to v17 ([#87](https://github.com/justinwlin/actual-mcp/issues/87)) ([8be16d9](https://github.com/justinwlin/actual-mcp/commit/8be16d9bf4e2308e4073a150bdab03f5c6a418ba))
* **deps:** update dependency express to v5.2.1 ([#78](https://github.com/justinwlin/actual-mcp/issues/78)) ([c1e0093](https://github.com/justinwlin/actual-mcp/commit/c1e0093ced6814488e3d4b732127cb757d7d550c))
* **deps:** update dependency zod-to-json-schema to v3.25.0 ([#69](https://github.com/justinwlin/actual-mcp/issues/69)) ([ecff8ee](https://github.com/justinwlin/actual-mcp/commit/ecff8eec0d9ce79cb9a769bc559603d3e972b57d))
* **deps:** upgrade @actual-app/api to v26.1.0 ([941c6f6](https://github.com/justinwlin/actual-mcp/commit/941c6f69675a847e9e034f9a44e7cde4885555d9))
* docker publish to proper username ([#29](https://github.com/justinwlin/actual-mcp/issues/29)) ([fa15085](https://github.com/justinwlin/actual-mcp/commit/fa150857d528c730b5f6ad20a33ede230e886635))
* docker run with pre-compiled binaries ([#4](https://github.com/justinwlin/actual-mcp/issues/4)) ([2171a0f](https://github.com/justinwlin/actual-mcp/commit/2171a0f5ccb2cd1ecc29affb86fb9ae6e3710200))
* prevent server crash on non-Error thrown values ([4a447d0](https://github.com/justinwlin/actual-mcp/commit/4a447d0f6c367c96f2bf8a2cfa1022fda3eeecbf))
* remove unsupported Google OAuth docs and fix timezone bug ([e4f8f86](https://github.com/justinwlin/actual-mcp/commit/e4f8f86649d9e0ab0209a54b2f5929a330c71f71))
* update actual version to latest ([f4b18e1](https://github.com/justinwlin/actual-mcp/commit/f4b18e13329bbf78ef498e1e200ea51dae3f9d88))
* update response type of accounts tool. test return is correct ([3dbe79a](https://github.com/justinwlin/actual-mcp/commit/3dbe79a665a26acea6133812f36bf8a41ac60eae))
* use valid JSON Schema 2020-12 for rule value types ([#26](https://github.com/justinwlin/actual-mcp/issues/26)) ([6ee4c7e](https://github.com/justinwlin/actual-mcp/commit/6ee4c7e4c72e3b341a0acc261ffe231781acdbdf))

## [1.7.0](https://github.com/s-stefanov/actual-mcp/compare/v1.6.0...v1.7.0) (2026-01-17)


### Features

* add run-bank-sync tool ([#93](https://github.com/s-stefanov/actual-mcp/issues/93)) ([61b67d7](https://github.com/s-stefanov/actual-mcp/commit/61b67d72e3789999cfe4aec78181deffffaabb99))

## [1.6.0](https://github.com/s-stefanov/actual-mcp/compare/v1.5.0...v1.6.0) (2025-12-21)


### Features

* add create-transaction tool ([#72](https://github.com/s-stefanov/actual-mcp/issues/72)) ([f8cd573](https://github.com/s-stefanov/actual-mcp/commit/f8cd573be318536d9d3ea9730942d5fb5fb89757))


### Bug Fixes

* **deps:** update dependency dotenv to v17 ([#87](https://github.com/s-stefanov/actual-mcp/issues/87)) ([8be16d9](https://github.com/s-stefanov/actual-mcp/commit/8be16d9bf4e2308e4073a150bdab03f5c6a418ba))
* **deps:** update dependency express to v5.2.1 ([#78](https://github.com/s-stefanov/actual-mcp/issues/78)) ([c1e0093](https://github.com/s-stefanov/actual-mcp/commit/c1e0093ced6814488e3d4b732127cb757d7d550c))
* **deps:** update dependency zod-to-json-schema to v3.25.0 ([#69](https://github.com/s-stefanov/actual-mcp/issues/69)) ([ecff8ee](https://github.com/s-stefanov/actual-mcp/commit/ecff8eec0d9ce79cb9a769bc559603d3e972b57d))

## [1.5.0](https://github.com/s-stefanov/actual-mcp/compare/v1.4.0...v1.5.0) (2025-11-10)


### Features

* Add streamable HTTP transport for Codex (Trigger Release) ([#54](https://github.com/s-stefanov/actual-mcp/issues/54)) ([ec23551](https://github.com/s-stefanov/actual-mcp/commit/ec235517ad3a1d205fc31e02bbcd0800cb9b92ef))


### Bug Fixes

* correct repo url in README.md ([#42](https://github.com/s-stefanov/actual-mcp/issues/42)) ([41b4070](https://github.com/s-stefanov/actual-mcp/commit/41b4070e4c44394a15b15947a3b799de0d7e8ef4))

## [1.4.0](https://github.com/s-stefanov/actual-mcp/compare/v1.3.0...v1.4.0) (2025-10-18)


### Features

* Enhance transaction handling with enriched data and improved input parsing ([#39](https://github.com/s-stefanov/actual-mcp/issues/39)) ([74f1270](https://github.com/s-stefanov/actual-mcp/commit/74f12709ee9efef7840dec15bd1c1424cb09f5f2))
* Fix monthly summary with transfers calculations ([#41](https://github.com/s-stefanov/actual-mcp/issues/41)) ([af59c41](https://github.com/s-stefanov/actual-mcp/commit/af59c41d43ea3e85b10e475becc3f62273e8ebd0))

## [1.3.0](https://github.com/s-stefanov/actual-mcp/compare/v1.2.2...v1.3.0) (2025-10-09)


### Features

* Connect to actual budget server that has different encryption key ([#33](https://github.com/s-stefanov/actual-mcp/issues/33)) ([f828ad4](https://github.com/s-stefanov/actual-mcp/commit/f828ad4f56e73416ec82f5c55efd98bea315c196)), closes [#28](https://github.com/s-stefanov/actual-mcp/issues/28)
* Return id in get-transactions ([#34](https://github.com/s-stefanov/actual-mcp/issues/34)) ([e15bb33](https://github.com/s-stefanov/actual-mcp/commit/e15bb33866106954a904f9ce1ebccf76983c95ea)), closes [#32](https://github.com/s-stefanov/actual-mcp/issues/32)
* Update Actual to 25.10.0 ([#35](https://github.com/s-stefanov/actual-mcp/issues/35)) ([1bd89ea](https://github.com/s-stefanov/actual-mcp/commit/1bd89ea4dd3fb72e8641f8eff018f41b3d8db6a7))

## [1.2.2](https://github.com/s-stefanov/actual-mcp/compare/v1.2.1...v1.2.2) (2025-10-08)


### Bug Fixes

* docker publish to proper username ([#29](https://github.com/s-stefanov/actual-mcp/issues/29)) ([fa15085](https://github.com/s-stefanov/actual-mcp/commit/fa150857d528c730b5f6ad20a33ede230e886635))

## [1.2.1](https://github.com/s-stefanov/actual-mcp/compare/v1.2.0...v1.2.1) (2025-10-06)


### Bug Fixes

* use valid JSON Schema 2020-12 for rule value types ([#26](https://github.com/s-stefanov/actual-mcp/issues/26)) ([6ee4c7e](https://github.com/s-stefanov/actual-mcp/commit/6ee4c7e4c72e3b341a0acc261ffe231781acdbdf))

## [1.2.0](https://github.com/s-stefanov/actual-mcp/compare/v1.1.0...v1.2.0) (2025-09-05)


### Features

* New tools for categories, payees, and rules ([#18](https://github.com/s-stefanov/actual-mcp/issues/18)) ([fa9bbd2](https://github.com/s-stefanov/actual-mcp/commit/fa9bbd2752e2a04ef5cc82e752100f02b0af63f3))

## [1.1.0](https://github.com/s-stefanov/actual-mcp/compare/v1.0.2...v1.1.0) (2025-07-26)


### Features

* Add Vitest unit testing framework for src/core module ([#14](https://github.com/s-stefanov/actual-mcp/issues/14)) ([80d3d80](https://github.com/s-stefanov/actual-mcp/commit/80d3d8028fec938ed06f03b60b234be19b3881d1))
* create PR checks ([#16](https://github.com/s-stefanov/actual-mcp/issues/16)) ([b60ea97](https://github.com/s-stefanov/actual-mcp/commit/b60ea973ddffc9b93a32679beb61d616decb0455))
* ESLint Introduction. Typings and fixes ([#15](https://github.com/s-stefanov/actual-mcp/issues/15)) ([8f33ad8](https://github.com/s-stefanov/actual-mcp/commit/8f33ad88c91ab3636fa95a53337cc8cc952a5773))


### Bug Fixes

* update actual version to latest ([f4b18e1](https://github.com/s-stefanov/actual-mcp/commit/f4b18e13329bbf78ef498e1e200ea51dae3f9d88))
* update response type of accounts tool. test return is correct ([3dbe79a](https://github.com/s-stefanov/actual-mcp/commit/3dbe79a665a26acea6133812f36bf8a41ac60eae))

## [1.0.2](https://github.com/s-stefanov/actual-mcp/compare/v1.0.1...v1.0.2) (2025-07-02)


### Bug Fixes

* deployment steps ([66a0311](https://github.com/s-stefanov/actual-mcp/commit/66a0311dccfa8f1cdb47052c74e21f070c0e7863))

## [1.0.1](https://github.com/s-stefanov/actual-mcp/compare/v1.0.0...v1.0.1) (2025-07-01)


### Bug Fixes

* deployment ([1c57a9d](https://github.com/s-stefanov/actual-mcp/commit/1c57a9d980bbf5724121763372a30a202e961273))

## 1.0.0 (2025-07-01)


### Features

* get accounts tool ([#6](https://github.com/s-stefanov/actual-mcp/issues/6)) ([9008dbe](https://github.com/s-stefanov/actual-mcp/commit/9008dbe8a94e83b822f28a1c0190f281882b7fcc))
* github pipelines ([#9](https://github.com/s-stefanov/actual-mcp/issues/9)) ([e9ae9ff](https://github.com/s-stefanov/actual-mcp/commit/e9ae9ff2a53c19ba9065804c64fb257bfbc3a8f7))
* Refactoring of tools & types ([#5](https://github.com/s-stefanov/actual-mcp/issues/5)) ([af9d185](https://github.com/s-stefanov/actual-mcp/commit/af9d1850ca76315185f36331f758597f510a4528))


### Bug Fixes

* docker run with pre-compiled binaries ([#4](https://github.com/s-stefanov/actual-mcp/issues/4)) ([2171a0f](https://github.com/s-stefanov/actual-mcp/commit/2171a0f5ccb2cd1ecc29affb86fb9ae6e3710200))

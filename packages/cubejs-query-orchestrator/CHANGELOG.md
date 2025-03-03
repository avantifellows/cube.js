# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.27.5](https://github.com/cube-js/cube.js/compare/v0.27.4...v0.27.5) (2021-05-03)


### Bug Fixes

* **query-orchestrator:** tableColumnTypes - compatibility for MySQL 8 ([a886876](https://github.com/cube-js/cube.js/commit/a88687606ce54272c8742503f62bcac8d2ca0441))





## [0.27.4](https://github.com/cube-js/cube.js/compare/v0.27.3...v0.27.4) (2021-04-29)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.27.2](https://github.com/cube-js/cube.js/compare/v0.27.1...v0.27.2) (2021-04-28)


### Bug Fixes

* Disable Scheduling when querying is not ready (before connection Wizard) ([b518ccd](https://github.com/cube-js/cube.js/commit/b518ccdd66a2f51af541bc54de2df816e138bac5))





## [0.27.1](https://github.com/cube-js/cube.js/compare/v0.27.0...v0.27.1) (2021-04-27)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.27.0](https://github.com/cube-js/cube.js/compare/v0.26.104...v0.27.0) (2021-04-26)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.103](https://github.com/cube-js/cube.js/compare/v0.26.102...v0.26.103) (2021-04-24)


### Bug Fixes

* concurrency lock driver instance & release on error ([dd60f5d](https://github.com/cube-js/cube.js/commit/dd60f5d1be59012ed33958d5889276afcc0639af))





## [0.26.101](https://github.com/cube-js/cube.js/compare/v0.26.100...v0.26.101) (2021-04-20)


### Bug Fixes

* QueryQueue - broken queuing on any error (TimeoutError: ResourceRequest timed out) ([ebe2c71](https://github.com/cube-js/cube.js/commit/ebe2c716d4ec0aa5cbc60529567f39672c199720))





## [0.26.99](https://github.com/cube-js/cube.js/compare/v0.26.98...v0.26.99) (2021-04-16)


### Bug Fixes

* Continuous refresh during Scheduled Refresh in case of both external and internal pre-aggregations are defined for the same data source ([#2566](https://github.com/cube-js/cube.js/issues/2566)) ([dcd2894](https://github.com/cube-js/cube.js/commit/dcd2894453d7afda3ea50b2592ae6610b231f5c5))





## [0.26.95](https://github.com/cube-js/cube.js/compare/v0.26.94...v0.26.95) (2021-04-13)


### Bug Fixes

* **playground:** Test connection in Connection Wizard ([715fa1c](https://github.com/cube-js/cube.js/commit/715fa1c0ab6667017e12851cbd97e97cf6807d60))





## [0.26.90](https://github.com/cube-js/cube.js/compare/v0.26.89...v0.26.90) (2021-04-11)


### Bug Fixes

* Manage stream connection release by orchestrator instead of driver ([adf059e](https://github.com/cube-js/cube.js/commit/adf059ec52e31e3ebc055b60a1ac6236c57251f8))





## [0.26.88](https://github.com/cube-js/cube.js/compare/v0.26.87...v0.26.88) (2021-04-10)


### Features

* Mysql Cube Store streaming ingests ([#2528](https://github.com/cube-js/cube.js/issues/2528)) ([0b36a6f](https://github.com/cube-js/cube.js/commit/0b36a6faa184766873ec3792785eb1aa5ca582af))





## [0.26.87](https://github.com/cube-js/cube.js/compare/v0.26.86...v0.26.87) (2021-04-10)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.81](https://github.com/cube-js/cube.js/compare/v0.26.80...v0.26.81) (2021-04-07)


### Features

* Introduce databricks-jdbc-driver ([bb0b31f](https://github.com/cube-js/cube.js/commit/bb0b31fb333f2aa379f11f6733c4efc17ec12dde))





## [0.26.79](https://github.com/cube-js/cube.js/compare/v0.26.78...v0.26.79) (2021-04-06)


### Bug Fixes

* sqlAlias on non partitioned rollups ([0675925](https://github.com/cube-js/cube.js/commit/0675925efb61a6492344b28179b7647eabb01a1d))





## [0.26.77](https://github.com/cube-js/cube.js/compare/v0.26.76...v0.26.77) (2021-04-04)


### Bug Fixes

* Reduce Redis traffic for Refresh Scheduler by introducing single pre-aggregations load cache for a whole refresh cycle ([bdb69d5](https://github.com/cube-js/cube.js/commit/bdb69d55ee15e7d9ecca69a8e237d40ee666d051))





## [0.26.76](https://github.com/cube-js/cube.js/compare/v0.26.75...v0.26.76) (2021-04-03)


### Bug Fixes

* Reduce Redis traffic while querying immutable pre-aggregation partitions by introducing LRU in memory cache for refresh keys ([#2484](https://github.com/cube-js/cube.js/issues/2484)) ([76ea3c1](https://github.com/cube-js/cube.js/commit/76ea3c1a5227cfa8eda5b0ad6a09f41b71826866))





## [0.26.74](https://github.com/cube-js/cube.js/compare/v0.26.73...v0.26.74) (2021-04-01)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.69](https://github.com/cube-js/cube.js/compare/v0.26.68...v0.26.69) (2021-03-25)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.65](https://github.com/cube-js/cube.js/compare/v0.26.64...v0.26.65) (2021-03-24)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.54](https://github.com/cube-js/cube.js/compare/v0.26.53...v0.26.54) (2021-03-12)


### Features

* Suggest to install cubestore-driver to get external pre-agg layer ([2059e57](https://github.com/cube-js/cube.js/commit/2059e57a2aa7caf81691c083949395e9697d2bcb))





## [0.26.45](https://github.com/cube-js/cube.js/compare/v0.26.44...v0.26.45) (2021-03-04)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.38](https://github.com/cube-js/cube.js/compare/v0.26.37...v0.26.38) (2021-02-26)


### Bug Fixes

* Optimize compute time during pre-aggregations load checks for queries with many partitions ([b9b590b](https://github.com/cube-js/cube.js/commit/b9b590b2891674020b23bc2e56ea2ab8dc02fa10))





## [0.26.35](https://github.com/cube-js/cube.js/compare/v0.26.34...v0.26.35) (2021-02-25)


### Features

* Use Cube Store as default external storage for CUBEJS_DEV_MODE ([e526676](https://github.com/cube-js/cube.js/commit/e52667617e5e687c92d383045fb1a8d5fd19cab6))





## [0.26.25](https://github.com/cube-js/cube.js/compare/v0.26.24...v0.26.25) (2021-02-20)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.23](https://github.com/cube-js/cube.js/compare/v0.26.22...v0.26.23) (2021-02-20)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.22](https://github.com/cube-js/cube.js/compare/v0.26.21...v0.26.22) (2021-02-20)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.19](https://github.com/cube-js/cube.js/compare/v0.26.18...v0.26.19) (2021-02-19)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.26.16](https://github.com/cube-js/cube.js/compare/v0.26.15...v0.26.16) (2021-02-18)


### Bug Fixes

* continueWaitTimeout is ignored: expose single centralized continueWaitTimeout option ([#2120](https://github.com/cube-js/cube.js/issues/2120)) ([2735d2c](https://github.com/cube-js/cube.js/commit/2735d2c1b60c0a31e3970c65b7dd1c293351614e)), closes [#225](https://github.com/cube-js/cube.js/issues/225)





## [0.26.15](https://github.com/cube-js/cube.js/compare/v0.26.14...v0.26.15) (2021-02-16)


### Features

* support SSL ca/cert/key in .env files as multiline text ([#2072](https://github.com/cube-js/cube.js/issues/2072)) ([d9f5154](https://github.com/cube-js/cube.js/commit/d9f5154e38c14417aa332f9bcd3d38ef00553e5a))





## [0.26.13](https://github.com/cube-js/cube.js/compare/v0.26.12...v0.26.13) (2021-02-12)


### Features

* type detection - check overflows for int/bigint ([393948a](https://github.com/cube-js/cube.js/commit/393948ae5fabf1c4b46ce4ea2b2dc22e8f012ee1))





## [0.26.12](https://github.com/cube-js/cube.js/compare/v0.26.11...v0.26.12) (2021-02-11)


### Bug Fixes

* **query-orchestrator:** detect negative int/decimal as strings ([#2051](https://github.com/cube-js/cube.js/issues/2051)) ([2b8b549](https://github.com/cube-js/cube.js/commit/2b8b549b022e357d85b9f4549a4ff61c9d39fbeb))
* UnhandledPromiseRejectionWarning: Error: Continue wait. fix [#1873](https://github.com/cube-js/cube.js/issues/1873) ([7f113f6](https://github.com/cube-js/cube.js/commit/7f113f61bef5b197cf26a3948a80d052a9cda79d))





## [0.26.11](https://github.com/cube-js/cube.js/compare/v0.26.10...v0.26.11) (2021-02-10)


### Bug Fixes

* CUBEJS_SCHEDULED_REFRESH_TIMER, fix [#1972](https://github.com/cube-js/cube.js/issues/1972) ([#1975](https://github.com/cube-js/cube.js/issues/1975)) ([dac7e52](https://github.com/cube-js/cube.js/commit/dac7e52ee0d3a118c9d69c9d030e58a3c048cca1))





## [0.26.10](https://github.com/cube-js/cube.js/compare/v0.26.9...v0.26.10) (2021-02-09)


### Bug Fixes

* Using .end() without the flush parameter is deprecated and throws from v.3.0.0 ([7078f41](https://github.com/cube-js/cube.js/commit/7078f4146572a4eb447b9ed6f64e071b86e0aca2))





## [0.26.7](https://github.com/cube-js/cube.js/compare/v0.26.6...v0.26.7) (2021-02-09)


### Features

* Support for Redis Sentinel + IORedis driver. fix [#1769](https://github.com/cube-js/cube.js/issues/1769) ([a5e7972](https://github.com/cube-js/cube.js/commit/a5e7972485fa97faaf9965b9794b0cf48256f484))
* Use REDIS_URL for IORedis options (with santinels) ([988bfe5](https://github.com/cube-js/cube.js/commit/988bfe5526be3506fe7b773d247ad89b3287fad4))





## [0.26.6](https://github.com/cube-js/cube.js/compare/v0.26.5...v0.26.6) (2021-02-08)


### Features

* **@cubejs-client/playground:** Building pre-aggregations message ([#1984](https://github.com/cube-js/cube.js/issues/1984)) ([e1fff5d](https://github.com/cube-js/cube.js/commit/e1fff5de4584df1bd8ef518e2436e1dcb4962975))
* **server-core:** Correct typings for driverFactory/dialectFactory ([51fb117](https://github.com/cube-js/cube.js/commit/51fb117883d2e04c3a8fce4494ac48e0938a0097))





## [0.26.2](https://github.com/cube-js/cube.js/compare/v0.26.1...v0.26.2) (2021-02-01)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.26.0](https://github.com/cube-js/cube.js/compare/v0.25.33...v0.26.0) (2021-02-01)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.32](https://github.com/cube-js/cube.js/compare/v0.25.31...v0.25.32) (2021-01-29)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.30](https://github.com/cube-js/cube.js/compare/v0.25.29...v0.25.30) (2021-01-26)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.29](https://github.com/cube-js/cube.js/compare/v0.25.28...v0.25.29) (2021-01-26)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.26](https://github.com/cube-js/cube.js/compare/v0.25.25...v0.25.26) (2021-01-25)


### Features

* BigQuery CSV pre-aggregation download support ([#1867](https://github.com/cube-js/cube.js/issues/1867)) ([5a2ea3f](https://github.com/cube-js/cube.js/commit/5a2ea3f27058a01bf08f697495c8ccce5abf9fa2))





## [0.25.24](https://github.com/cube-js/cube.js/compare/v0.25.23...v0.25.24) (2021-01-22)


### Bug Fixes

* Non default data source cache key and table schema queries are forwarded to the default data source ([2f7c672](https://github.com/cube-js/cube.js/commit/2f7c67292468da60faea284751bf8c71d2e051f5))
* Non default data source cache key and table schema queries are forwarded to the default data source: broken test ([#1856](https://github.com/cube-js/cube.js/issues/1856)) ([8aad3f5](https://github.com/cube-js/cube.js/commit/8aad3f52f476836df4f93c266af96f30ceb57131))





## [0.25.23](https://github.com/cube-js/cube.js/compare/v0.25.22...v0.25.23) (2021-01-22)


### Bug Fixes

* Map int2/4/8 to generic int type. fix [#1796](https://github.com/cube-js/cube.js/issues/1796) ([78e20eb](https://github.com/cube-js/cube.js/commit/78e20eb304eda3086cda7dbc4ea5d33ef877facb))





## [0.25.22](https://github.com/cube-js/cube.js/compare/v0.25.21...v0.25.22) (2021-01-21)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.21](https://github.com/cube-js/cube.js/compare/v0.25.20...v0.25.21) (2021-01-19)


### Bug Fixes

* **@cubejs-backend/query-orchestrator:** prevent generic pool infinite loop ([#1793](https://github.com/cube-js/cube.js/issues/1793)) ([d4129c4](https://github.com/cube-js/cube.js/commit/d4129c4d71b4afa66f62ae5d9666fcd9a08d9187))





## [0.25.20](https://github.com/cube-js/cube.js/compare/v0.25.19...v0.25.20) (2021-01-15)


### Bug Fixes

* Remove unnecessary `SELECT 1` during scheduled refresh. Fixes [#1592](https://github.com/cube-js/cube.js/issues/1592) ([#1786](https://github.com/cube-js/cube.js/issues/1786)) ([66f9d91](https://github.com/cube-js/cube.js/commit/66f9d91d12b1853b69903475af8338bfa586026b))





## [0.25.18](https://github.com/cube-js/cube.js/compare/v0.25.17...v0.25.18) (2021-01-14)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.15](https://github.com/cube-js/cube.js/compare/v0.25.14...v0.25.15) (2021-01-12)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.13](https://github.com/cube-js/cube.js/compare/v0.25.12...v0.25.13) (2021-01-07)


### Bug Fixes

* Guard from `undefined` dataSource in queue key ([6ae1fd6](https://github.com/cube-js/cube.js/commit/6ae1fd60a1e67bc73c0630b7de36b598397ce22b))





## [0.25.6](https://github.com/cube-js/cube.js/compare/v0.25.5...v0.25.6) (2020-12-30)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.5](https://github.com/cube-js/cube.js/compare/v0.25.4...v0.25.5) (2020-12-30)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.4](https://github.com/cube-js/cube.js/compare/v0.25.3...v0.25.4) (2020-12-30)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.25.2](https://github.com/cube-js/cube.js/compare/v0.25.1...v0.25.2) (2020-12-27)


### Bug Fixes

* **@cubejs-backend/query-orchestrator:** Throw an exception on empty pre-agg in readOnly mode, refs [#1597](https://github.com/cube-js/cube.js/issues/1597) ([17d5fdb](https://github.com/cube-js/cube.js/commit/17d5fdb82e0ce06d55e438913e32952f32db7923))





## [0.25.1](https://github.com/cube-js/cube.js/compare/v0.25.0...v0.25.1) (2020-12-24)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.25.0](https://github.com/cube-js/cube.js/compare/v0.24.15...v0.25.0) (2020-12-21)


### Bug Fixes

* getQueryStage throws undefined is not a function ([0de1603](https://github.com/cube-js/cube.js/commit/0de1603293fc918c0da8ff8bd514b49f14de51d8))


### Features

* Allow cross data source joins ([a58336e](https://github.com/cube-js/cube.js/commit/a58336e3840f8ac02d83de43ec7661419bceb71c))
* Allow cross data source joins: Serverless support ([034cdc8](https://github.com/cube-js/cube.js/commit/034cdc8dbf8907988df0f999fd115b8acdb4990f))





## [0.24.13](https://github.com/cube-js/cube.js/compare/v0.24.12...v0.24.13) (2020-12-18)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.24.12](https://github.com/cube-js/cube.js/compare/v0.24.11...v0.24.12) (2020-12-17)


### Features

* **query-orchestrator:** detects bigint in readOnly mode, when it's Number ([a21cc10](https://github.com/cube-js/cube.js/commit/a21cc1065031b23ee7c199cb56ec039112f83770))
* Introduce health checks ([#1607](https://github.com/cube-js/cube.js/issues/1607)) ([d96c662](https://github.com/cube-js/cube.js/commit/d96c66201ca8202907af8dc563eaaf908a5ece89))





## [0.24.9](https://github.com/cube-js/cube.js/compare/v0.24.8...v0.24.9) (2020-12-16)


### Bug Fixes

* **@cubejs-backend/mysql-driver:** Revert back test on borrow with database pool error logging. ([2cdaf40](https://github.com/cube-js/cube.js/commit/2cdaf406a7d99116849f60e00e1b1bc25605e0d3))





## [0.24.8](https://github.com/cube-js/cube.js/compare/v0.24.7...v0.24.8) (2020-12-15)


### Features

* **@cubejs-backend/query-orchestrator:** Introduce AsyncRedisClient type ([728110e](https://github.com/cube-js/cube.js/commit/728110ed0ffe5697bd5e47e3920bf2e5377a0ffd))
* **@cubejs-backend/query-orchestrator:** Migrate createRedisClient to TS ([78e8422](https://github.com/cube-js/cube.js/commit/78e8422937e79457fdcec70535225bc9ccecfce8))
* **@cubejs-backend/query-orchestrator:** Move RedisPool to TS, export RedisPoolOptions ([8e8abde](https://github.com/cube-js/cube.js/commit/8e8abde85b9fa821d21f33fc286cfb2cc56891e4))
* **@cubejs-backend/query-orchestrator:** Set redis pool options from server config ([c1270d4](https://github.com/cube-js/cube.js/commit/c1270d4cfdc243b230ade0cb3a4c59171db70d20))





## [0.24.6](https://github.com/cube-js/cube.js/compare/v0.24.5...v0.24.6) (2020-12-13)


### Features

* Move index creation orchestration to the driver: allow to control drivers when to create indexes ([2a94e71](https://github.com/cube-js/cube.js/commit/2a94e710a89954ecedf4aa6f76b89578138e7aff))





## [0.24.5](https://github.com/cube-js/cube.js/compare/v0.24.4...v0.24.5) (2020-12-09)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.24.4](https://github.com/cube-js/cube.js/compare/v0.24.3...v0.24.4) (2020-12-07)


### Features

* Ability to load SSL keys from FS ([#1512](https://github.com/cube-js/cube.js/issues/1512)) ([71da5bb](https://github.com/cube-js/cube.js/commit/71da5bb529294fabd92b3a914b1e8bceb464643c))





## [0.24.3](https://github.com/cube-js/cube.js/compare/v0.24.2...v0.24.3) (2020-12-01)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.24.2](https://github.com/cube-js/cube.js/compare/v0.24.1...v0.24.2) (2020-11-27)


### Features

* **@cubejs-backend/query-orchestrator:** Initial move to TypeScript ([#1462](https://github.com/cube-js/cube.js/issues/1462)) ([101e8dc](https://github.com/cube-js/cube.js/commit/101e8dc90d4b1266c0327adb86cab3e3caa8d4d0))





# [0.24.0](https://github.com/cube-js/cube.js/compare/v0.23.15...v0.24.0) (2020-11-26)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.23.14](https://github.com/cube-js/cube.js/compare/v0.23.13...v0.23.14) (2020-11-22)


### Bug Fixes

* **@cubejs-backend/query-orchestrator:** Intermittent lags when pre-aggregation tables are refreshed ([4efe1fc](https://github.com/cube-js/cube.js/commit/4efe1fc006282d87ab2718918d1bdd174baa6be3))





## [0.23.6](https://github.com/cube-js/cube.js/compare/v0.23.5...v0.23.6) (2020-11-02)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.23.3](https://github.com/cube-js/cube.js/compare/v0.23.2...v0.23.3) (2020-10-31)


### Features

* **@cubejs-backend/query-orchestrator:** add support for MSSQL nvarchar ([#1260](https://github.com/cube-js/cube.js/issues/1260)) Thanks to @JoshMentzer! ([a9e9919](https://github.com/cube-js/cube.js/commit/a9e9919))





# [0.23.0](https://github.com/cube-js/cube.js/compare/v0.22.4...v0.23.0) (2020-10-28)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.22.0](https://github.com/cube-js/cube.js/compare/v0.21.2...v0.22.0) (2020-10-20)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.21.1](https://github.com/cube-js/cube.js/compare/v0.21.0...v0.21.1) (2020-10-15)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.21.0](https://github.com/cube-js/cube.js/compare/v0.20.15...v0.21.0) (2020-10-09)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.20.13](https://github.com/cube-js/cube.js/compare/v0.20.12...v0.20.13) (2020-10-07)


### Bug Fixes

* **@cubejs-backend/mongobi-driver:** TypeError: v.toLowerCase is not a function ([16a15cb](https://github.com/cube-js/cube.js/commit/16a15cb))





## [0.20.9](https://github.com/cube-js/cube.js/compare/v0.20.8...v0.20.9) (2020-09-19)


### Features

* `sqlAlias` attribute for `preAggregations` and short format for pre-aggregation table names ([#1068](https://github.com/cube-js/cube.js/issues/1068)) ([98ffad3](https://github.com/cube-js/cube.js/commit/98ffad3)), closes [#86](https://github.com/cube-js/cube.js/issues/86) [#907](https://github.com/cube-js/cube.js/issues/907)





# [0.20.0](https://github.com/cube-js/cube.js/compare/v0.19.61...v0.20.0) (2020-08-26)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.19.61](https://github.com/cube-js/cube.js/compare/v0.19.60...v0.19.61) (2020-08-11)


### Bug Fixes

* avoid opening connection to the source database when caching tables from external rollup db ([#929](https://github.com/cube-js/cube.js/issues/929)) Thanks to [@jcw](https://github.com/jcw)-! ([92cd0b3](https://github.com/cube-js/cube.js/commit/92cd0b3))





## [0.19.60](https://github.com/cube-js/cube.js/compare/v0.19.59...v0.19.60) (2020-08-08)


### Bug Fixes

* Intermittent errors with empty rollups or not ready metadata for Athena and MySQL: HIVE_CANNOT_OPEN_SPLIT errors. ([fa2cf45](https://github.com/cube-js/cube.js/commit/fa2cf45))





## [0.19.56](https://github.com/cube-js/cube.js/compare/v0.19.55...v0.19.56) (2020-08-03)


### Bug Fixes

* allow renewQuery in dev mode with warning ([#868](https://github.com/cube-js/cube.js/issues/868)) Thanks to [@jcw](https://github.com/jcw)-! ([dbdbb5f](https://github.com/cube-js/cube.js/commit/dbdbb5f))





## [0.19.54](https://github.com/cube-js/cube.js/compare/v0.19.53...v0.19.54) (2020-07-23)


### Bug Fixes

* Orphaned queries in Redis queue during intensive load ([101b85f](https://github.com/cube-js/cube.js/commit/101b85f))





## [0.19.53](https://github.com/cube-js/cube.js/compare/v0.19.52...v0.19.53) (2020-07-20)


### Features

* More logging info for Orphaned Queries debugging ([99bf957](https://github.com/cube-js/cube.js/commit/99bf957))





## [0.19.52](https://github.com/cube-js/cube.js/compare/v0.19.51...v0.19.52) (2020-07-18)


### Bug Fixes

* Redis driver execAsync ignores watch directives ([ac67e5b](https://github.com/cube-js/cube.js/commit/ac67e5b))





## [0.19.50](https://github.com/cube-js/cube.js/compare/v0.19.49...v0.19.50) (2020-07-16)


### Features

* Generic readOnly external rollup implementation. MongoDB support. ([79d7bfd](https://github.com/cube-js/cube.js/commit/79d7bfd)), closes [#239](https://github.com/cube-js/cube.js/issues/239)
* Rollup mode ([#843](https://github.com/cube-js/cube.js/issues/843)) Thanks to [@jcw](https://github.com/jcw)-! ([cc41f97](https://github.com/cube-js/cube.js/commit/cc41f97))





## [0.19.46](https://github.com/cube-js/cube.js/compare/v0.19.45...v0.19.46) (2020-07-06)


### Features

* Report query usage for Athena and BigQuery ([697b53f](https://github.com/cube-js/cube.js/commit/697b53f))





## [0.19.36](https://github.com/cube-js/cube.js/compare/v0.19.35...v0.19.36) (2020-06-24)


### Bug Fixes

* Avoid excessive pre-aggregation invalidation in presence of multiple structure versions ([fd5e602](https://github.com/cube-js/cube.js/commit/fd5e602))





## [0.19.17](https://github.com/cube-js/cube.js/compare/v0.19.16...v0.19.17) (2020-05-09)


### Bug Fixes

* Continue wait errors during tables fetch ([cafaa28](https://github.com/cube-js/cube.js/commit/cafaa28))





## [0.19.15](https://github.com/cube-js/cube.js/compare/v0.19.14...v0.19.15) (2020-05-04)


### Features

* More pre-aggregation info logging ([9d69f98](https://github.com/cube-js/cube.js/commit/9d69f98))





## [0.19.14](https://github.com/cube-js/cube.js/compare/v0.19.13...v0.19.14) (2020-04-24)


### Bug Fixes

* More descriptive errors for download errors ([e834aba](https://github.com/cube-js/cube.js/commit/e834aba))





## [0.19.9](https://github.com/cube-js/cube.js/compare/v0.19.8...v0.19.9) (2020-04-16)


### Features

* Allow persisting multiple pre-aggregation structure versions to support staging pre-aggregation warm-up environments and multiple timezones ([ab9539a](https://github.com/cube-js/cube.js/commit/ab9539a))





## [0.19.8](https://github.com/cube-js/cube.js/compare/v0.19.7...v0.19.8) (2020-04-15)


### Bug Fixes

* Dead queries added to queue in serverless ([eca3d0c](https://github.com/cube-js/cube.js/commit/eca3d0c))





## [0.19.7](https://github.com/cube-js/cube.js/compare/v0.19.6...v0.19.7) (2020-04-14)


### Bug Fixes

* Associate Queue storage error with requestId ([ec2750e](https://github.com/cube-js/cube.js/commit/ec2750e))





## [0.19.6](https://github.com/cube-js/cube.js/compare/v0.19.5...v0.19.6) (2020-04-14)


### Bug Fixes

* Consistent queryKey logging ([5f1a632](https://github.com/cube-js/cube.js/commit/5f1a632))





## [0.19.5](https://github.com/cube-js/cube.js/compare/v0.19.4...v0.19.5) (2020-04-13)


### Bug Fixes

* Broken query and pre-aggregation cancel ([aa82256](https://github.com/cube-js/cube.js/commit/aa82256))


### Features

* Log queue state on Waiting for query ([395c63c](https://github.com/cube-js/cube.js/commit/395c63c))





# [0.19.0](https://github.com/cube-js/cube.js/compare/v0.18.32...v0.19.0) (2020-04-09)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.18.18](https://github.com/cube-js/cube.js/compare/v0.18.17...v0.18.18) (2020-03-28)


### Features

* Executing SQL logging message that shows final SQL ([26b8758](https://github.com/cube-js/cube.js/commit/26b8758))





## [0.18.17](https://github.com/cube-js/cube.js/compare/v0.18.16...v0.18.17) (2020-03-24)


### Features

* More places to fetch `readOnly` pre-aggregations flag from ([9877037](https://github.com/cube-js/cube.js/commit/9877037))





## [0.18.13](https://github.com/cube-js/cube.js/compare/v0.18.12...v0.18.13) (2020-03-21)


### Bug Fixes

* Various cleanup errors ([538f6d0](https://github.com/cube-js/cube.js/commit/538f6d0)), closes [#525](https://github.com/cube-js/cube.js/issues/525)





## [0.18.12](https://github.com/cube-js/cube.js/compare/v0.18.11...v0.18.12) (2020-03-19)


### Features

* Add duration to error logging ([59a4255](https://github.com/cube-js/cube.js/commit/59a4255))





## [0.18.11](https://github.com/cube-js/cube.js/compare/v0.18.10...v0.18.11) (2020-03-18)


### Bug Fixes

* Orphaned pre-aggregation tables aren't dropped because LocalCacheDriver doesn't expire keys ([393af3d](https://github.com/cube-js/cube.js/commit/393af3d))





## [0.18.7](https://github.com/cube-js/cube.js/compare/v0.18.6...v0.18.7) (2020-03-17)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.18.6](https://github.com/cube-js/cube.js/compare/v0.18.5...v0.18.6) (2020-03-16)


### Bug Fixes

* Waiting for query isn't logged for Local Queue when query is already in progress ([e7be6d1](https://github.com/cube-js/cube.js/commit/e7be6d1))





## [0.18.5](https://github.com/cube-js/cube.js/compare/v0.18.4...v0.18.5) (2020-03-15)


### Bug Fixes

* `requestId` isn't propagating to all pre-aggregations messages ([650dd6e](https://github.com/cube-js/cube.js/commit/650dd6e))





## [0.18.4](https://github.com/cube-js/cube.js/compare/v0.18.3...v0.18.4) (2020-03-09)


### Features

* Use options pattern in constructor ([#468](https://github.com/cube-js/cube.js/issues/468)) Thanks to [@jcw](https://github.com/jcw)-! ([ff20167](https://github.com/cube-js/cube.js/commit/ff20167))





## [0.18.3](https://github.com/cube-js/cube.js/compare/v0.18.2...v0.18.3) (2020-03-02)


### Bug Fixes

* CUBEJS_REDIS_POOL_MAX=0 env variable setting isn't respected ([75f6889](https://github.com/cube-js/cube.js/commit/75f6889))





## [0.18.2](https://github.com/cube-js/cube.js/compare/v0.18.1...v0.18.2) (2020-03-01)


### Bug Fixes

* Limit pre-aggregations fetch table requests using queue -- handle HA for pre-aggregations ([75833b1](https://github.com/cube-js/cube.js/commit/75833b1))





## [0.18.1](https://github.com/cube-js/cube.js/compare/v0.18.0...v0.18.1) (2020-03-01)


### Bug Fixes

* Remove user facing errors for pre-aggregations refreshes ([d15c551](https://github.com/cube-js/cube.js/commit/d15c551))





# [0.18.0](https://github.com/cube-js/cube.js/compare/v0.17.10...v0.18.0) (2020-03-01)


### Bug Fixes

* Error: client.readOnly is not a function ([6069499](https://github.com/cube-js/cube.js/commit/6069499))
* Redis query queue locking redesign ([a2eb9b2](https://github.com/cube-js/cube.js/commit/a2eb9b2)), closes [#459](https://github.com/cube-js/cube.js/issues/459)
* TypeError: Cannot read property 'queryKey' of null under load ([0c996d8](https://github.com/cube-js/cube.js/commit/0c996d8))


### Features

* Redis connection pooling ([#433](https://github.com/cube-js/cube.js/issues/433)) Thanks to [@jcw](https://github.com/jcw)! ([cf133a9](https://github.com/cube-js/cube.js/commit/cf133a9)), closes [#104](https://github.com/cube-js/cube.js/issues/104)





## [0.17.10](https://github.com/cube-js/cube.js/compare/v0.17.9...v0.17.10) (2020-02-20)


### Features

* Support external rollups from readonly source ([#395](https://github.com/cube-js/cube.js/issues/395)) ([b17e841](https://github.com/cube-js/cube.js/commit/b17e841))





## [0.17.9](https://github.com/cube-js/cube.js/compare/v0.17.8...v0.17.9) (2020-02-18)


### Features

* Enhanced trace logging ([1fdd8e9](https://github.com/cube-js/cube.js/commit/1fdd8e9))





## [0.17.5](https://github.com/cube-js/cube.js/compare/v0.17.4...v0.17.5) (2020-02-07)


### Bug Fixes

* Sanity check for silent truncate name problem during pre-aggregation creation ([e7fb2f2](https://github.com/cube-js/cube.js/commit/e7fb2f2))





## [0.17.3](https://github.com/cube-js/cube.js/compare/v0.17.2...v0.17.3) (2020-02-06)


### Features

* Pre-aggregation indexes support ([d443585](https://github.com/cube-js/cube.js/commit/d443585))





# [0.17.0](https://github.com/cube-js/cube.js/compare/v0.16.0...v0.17.0) (2020-02-04)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.16.0](https://github.com/cube-js/cube.js/compare/v0.15.4...v0.16.0) (2020-02-04)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.15.0](https://github.com/cube-js/cube.js/compare/v0.14.3...v0.15.0) (2020-01-18)


### Features

* New refreshKeyRenewalThresholds and foreground renew defaults ([9fb0abb](https://github.com/cube-js/cube.js/commit/9fb0abb))
* Slow Query Warning and scheduled refresh for cube refresh keys ([8768b0e](https://github.com/cube-js/cube.js/commit/8768b0e))





# [0.14.0](https://github.com/cube-js/cube.js/compare/v0.13.12...v0.14.0) (2020-01-16)


### Bug Fixes

* Cannot read property 'requestId' of null ([d087837](https://github.com/cube-js/cube.js/commit/d087837)), closes [#347](https://github.com/cube-js/cube.js/issues/347)


### Features

* Scheduled refresh for pre-aggregations ([c87b525](https://github.com/cube-js/cube.js/commit/c87b525))
* Scheduled Refresh REST API ([472a0c3](https://github.com/cube-js/cube.js/commit/472a0c3))





## [0.13.9](https://github.com/cube-js/cube.js/compare/v0.13.8...v0.13.9) (2020-01-03)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.13.2](https://github.com/cube-js/cube.js/compare/v0.13.1...v0.13.2) (2019-12-13)


### Features

* Propagate `requestId` for trace logging ([24d7b41](https://github.com/cube-js/cube.js/commit/24d7b41))





# [0.13.0](https://github.com/cube-js/cube.js/compare/v0.12.3...v0.13.0) (2019-12-10)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.12.2](https://github.com/cube-js/cube.js/compare/v0.12.1...v0.12.2) (2019-12-02)


### Bug Fixes

* this.versionEntries typo ([#279](https://github.com/cube-js/cube.js/issues/279)) ([743f9fb](https://github.com/cube-js/cube.js/commit/743f9fb))


### Features

* support REDIS_PASSWORD env variable ([#280](https://github.com/cube-js/cube.js/issues/280)). Thanks to [@lanphan](https://github.com/lanphan)! ([5172745](https://github.com/cube-js/cube.js/commit/5172745))





## [0.12.1](https://github.com/cube-js/cube.js/compare/v0.12.0...v0.12.1) (2019-11-26)


### Features

* Show used pre-aggregations and match rollup results in Playground ([4a67346](https://github.com/cube-js/cube.js/commit/4a67346))





# [0.12.0](https://github.com/cube-js/cube.js/compare/v0.11.25...v0.12.0) (2019-11-25)


### Features

* Show `refreshKey` values in Playground ([b49e184](https://github.com/cube-js/cube.js/commit/b49e184))





## [0.11.18](https://github.com/cube-js/cube.js/compare/v0.11.17...v0.11.18) (2019-11-09)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.11.6](https://github.com/statsbotco/cubejs-client/compare/v0.11.5...v0.11.6) (2019-10-17)


### Bug Fixes

* TypeError: Cannot read property 'table_name' of undefined: Drop orphaned tables implementation drops recent tables in cluster environments ([84ea78a](https://github.com/statsbotco/cubejs-client/commit/84ea78a))





# [0.11.0](https://github.com/statsbotco/cubejs-client/compare/v0.10.62...v0.11.0) (2019-10-15)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.10.58](https://github.com/statsbotco/cubejs-client/compare/v0.10.57...v0.10.58) (2019-10-04)


### Bug Fixes

* `continueWaitTimout` option is ignored in LocalQueueDriver ([#224](https://github.com/statsbotco/cubejs-client/issues/224)) ([4f72a52](https://github.com/statsbotco/cubejs-client/commit/4f72a52))





## [0.10.35](https://github.com/statsbotco/cubejs-client/compare/v0.10.34...v0.10.35) (2019-09-09)


### Bug Fixes

* LocalQueueDriver key interference for multitenant deployment ([aa860e4](https://github.com/statsbotco/cubejs-client/commit/aa860e4))


### Features

* Serve pre-aggregated data right from external database without hitting main one if pre-aggregation is available ([931fb7c](https://github.com/statsbotco/cubejs-client/commit/931fb7c))





## [0.10.33](https://github.com/statsbotco/cubejs-client/compare/v0.10.32...v0.10.33) (2019-09-06)


### Bug Fixes

* Revert to default queue concurrency for external pre-aggregations as driver pools expect this be aligned with default pool size ([c695ddd](https://github.com/statsbotco/cubejs-client/commit/c695ddd))





## [0.10.32](https://github.com/statsbotco/cubejs-client/compare/v0.10.31...v0.10.32) (2019-09-06)


### Bug Fixes

* In memory queue driver drop state if rollups are building too long ([ad4c062](https://github.com/statsbotco/cubejs-client/commit/ad4c062))





## [0.10.30](https://github.com/statsbotco/cubejs-client/compare/v0.10.29...v0.10.30) (2019-08-26)


### Features

* `REDIS_TLS=true` env variable support ([55858cf](https://github.com/statsbotco/cubejs-client/commit/55858cf))





## [0.10.28](https://github.com/statsbotco/cubejs-client/compare/v0.10.27...v0.10.28) (2019-08-19)


### Bug Fixes

* BigQuery to Postgres external rollup doesn't work ([feccdb5](https://github.com/statsbotco/cubejs-client/commit/feccdb5)), closes [#178](https://github.com/statsbotco/cubejs-client/issues/178)





## [0.10.16](https://github.com/statsbotco/cubejs-client/compare/v0.10.15...v0.10.16) (2019-07-20)


### Features

* BigQuery external rollup support ([10c635c](https://github.com/statsbotco/cubejs-client/commit/10c635c))





## [0.10.15](https://github.com/statsbotco/cubejs-client/compare/v0.10.14...v0.10.15) (2019-07-13)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.10.12](https://github.com/statsbotco/cubejs-client/compare/v0.10.11...v0.10.12) (2019-07-06)


### Bug Fixes

* QUERIES_undefined redis key for QueryQueue ([4c44886](https://github.com/statsbotco/cubejs-client/commit/4c44886))





## [0.10.11](https://github.com/statsbotco/cubejs-client/compare/v0.10.10...v0.10.11) (2019-07-02)


### Bug Fixes

* TypeError: Cannot read property 'startsWith' of undefined at tableDefinition.filter.column: support uppercase databases ([995b115](https://github.com/statsbotco/cubejs-client/commit/995b115))





# [0.10.0](https://github.com/statsbotco/cubejs-client/compare/v0.9.24...v0.10.0) (2019-06-21)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.9.14](https://github.com/statsbotco/cubejs-client/compare/v0.9.13...v0.9.14) (2019-06-07)


### Features

* Add option to run in production without redis ([a7de417](https://github.com/statsbotco/cubejs-client/commit/a7de417)), closes [#110](https://github.com/statsbotco/cubejs-client/issues/110)





## [0.9.4](https://github.com/statsbotco/cubejs-client/compare/v0.9.3...v0.9.4) (2019-05-22)


### Features

* Add `refreshKeyRenewalThreshold` option ([aa69449](https://github.com/statsbotco/cubejs-client/commit/aa69449)), closes [#112](https://github.com/statsbotco/cubejs-client/issues/112)





## [0.9.2](https://github.com/statsbotco/cubejs-client/compare/v0.9.1...v0.9.2) (2019-05-11)


### Bug Fixes

* External rollups serverless implementation ([6d13370](https://github.com/statsbotco/cubejs-client/commit/6d13370))





# [0.9.0](https://github.com/statsbotco/cubejs-client/compare/v0.8.7...v0.9.0) (2019-05-11)


### Features

* External rollup implementation ([d22a809](https://github.com/statsbotco/cubejs-client/commit/d22a809))





## [0.8.7](https://github.com/statsbotco/cubejs-client/compare/v0.8.6...v0.8.7) (2019-05-09)


### Bug Fixes

* **query-orchestrator:** Athena got swamped by fetch schema requests ([d8b5440](https://github.com/statsbotco/cubejs-client/commit/d8b5440))





## [0.8.4](https://github.com/statsbotco/cubejs-client/compare/v0.8.3...v0.8.4) (2019-05-02)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.8.1](https://github.com/statsbotco/cubejs-client/compare/v0.8.0...v0.8.1) (2019-04-30)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.8.0](https://github.com/statsbotco/cubejs-client/compare/v0.7.10...v0.8.0) (2019-04-29)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





## [0.7.6](https://github.com/statsbotco/cubejs-client/compare/v0.7.5...v0.7.6) (2019-04-23)


### Bug Fixes

* **query-orchestrator:** add RedisFactory and promisify methods manually ([#89](https://github.com/statsbotco/cubejs-client/issues/89)) ([cdfcd87](https://github.com/statsbotco/cubejs-client/commit/cdfcd87)), closes [#84](https://github.com/statsbotco/cubejs-client/issues/84)





# [0.7.0](https://github.com/statsbotco/cubejs-client/compare/v0.6.2...v0.7.0) (2019-04-15)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.6.0](https://github.com/statsbotco/cubejs-client/compare/v0.5.2...v0.6.0) (2019-04-09)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator





# [0.5.0](https://github.com/statsbotco/cubejs-client/compare/v0.4.6...v0.5.0) (2019-04-01)


### Features

* use local queue and cache for local dev server instead of Redis one ([50f1bbb](https://github.com/statsbotco/cubejs-client/commit/50f1bbb))





## [0.4.4](https://github.com/statsbotco/cubejs-client/compare/v0.4.3...v0.4.4) (2019-03-17)

**Note:** Version bump only for package @cubejs-backend/query-orchestrator

:robot: I have created a release *beep* *boop*
---


<details><summary>akamai-edgeworker-sdk-common: 2.0.50</summary>

## [2.0.50](https://github.com/launchdarkly-labs/js-core/compare/akamai-edgeworker-sdk-common-v2.0.49...akamai-edgeworker-sdk-common-v2.0.50) (2026-11-10)


### Bug Fixes

* **akamai-edgeworker-sdk:** reduce bundles with dual ESM and CJS output ([#2171](https://github.com/launchdarkly-labs/js-core/issues/2171)) ([1504e6c](https://github.com/launchdarkly-labs/js-core/commit/1504e6ccfc96c4821aa440200029889f32639f87))
* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* explicit return types and TS6 source compatibility fixes ([#1418](https://github.com/launchdarkly-labs/js-core/issues/1418)) ([9c131a2](https://github.com/launchdarkly-labs/js-core/commit/9c131a2e731c97a7fd4cf7ec1fe11efbbf49d6fb))
* **perf:** reduce Akamai CryptoJS bundle size ([#1877](https://github.com/launchdarkly-labs/js-core/issues/1877)) ([0b3e1ec](https://github.com/launchdarkly-labs/js-core/commit/0b3e1ec66ae1272733d4fc80d5bd82f8c9d1cf17))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-server-sdk-common bumped from ^2.26.4 to ^2.27.0
</details>

<details><summary>akamai-server-base-sdk: 3.0.51</summary>

## [3.0.51](https://github.com/launchdarkly-labs/js-core/compare/akamai-server-base-sdk-v3.0.50...akamai-server-base-sdk-v3.0.51) (2026-11-10)


### Bug Fixes

* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/akamai-edgeworker-sdk-common bumped from ^2.0.49 to ^2.0.50
</details>

<details><summary>akamai-server-edgekv-sdk: 1.4.53</summary>

## [1.4.53](https://github.com/launchdarkly-labs/js-core/compare/akamai-server-edgekv-sdk-v1.4.52...akamai-server-edgekv-sdk-v1.4.53) (2026-11-10)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/akamai-edgeworker-sdk-common bumped from ^2.0.49 to ^2.0.50
    * @launchdarkly/js-server-sdk-common bumped from ^2.26.4 to ^2.27.0
</details>

<details><summary>client-testing-plugin: 2.0.0</summary>

## [2.0.0](https://github.com/launchdarkly-labs/js-core/compare/client-testing-plugin-v1.0.31...client-testing-plugin-v2.0.0) (2026-11-10)


###   BREAKING CHANGES

* release `@launchdarkly/client-testing-plugin` ([#1755](https://github.com/launchdarkly-labs/js-core/issues/1755))
* prerelease `@launchdarkly/client-testing-plugin` ([#1422](https://github.com/launchdarkly-labs/js-core/issues/1422))

### Features

* prerelease `@launchdarkly/client-testing-plugin` ([#1422](https://github.com/launchdarkly-labs/js-core/issues/1422)) ([d801e9e](https://github.com/launchdarkly-labs/js-core/commit/d801e9e923f8c81e177e25c846cf7e76398cc36e))
* release `@launchdarkly/client-testing-plugin` ([#1755](https://github.com/launchdarkly-labs/js-core/issues/1755)) ([9d44e25](https://github.com/launchdarkly-labs/js-core/commit/9d44e25380d58b1510b510d5f2a5b6d4d05e58e9))


### Bug Fixes

* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-client-sdk-common bumped from 1.35.2 to 1.36.0
  * devDependencies
    * @launchdarkly/js-client-sdk bumped from 4.14.2 to 4.15.0
    * @launchdarkly/react-sdk bumped from 4.2.2 to 4.3.0
  * peerDependencies
    * @launchdarkly/js-client-sdk bumped from ^4.9.1 to ^4.15.0
    * @launchdarkly/react-sdk bumped from ^4.1.4 to ^4.3.0
</details>

<details><summary>cloudflare-server-sdk: 2.7.52</summary>

## [2.7.52](https://github.com/launchdarkly-labs/js-core/compare/cloudflare-server-sdk-v2.7.51...cloudflare-server-sdk-v2.7.52) (2026-11-10)


### Bug Fixes

* **cloudflare:** bundle tslib with esm module ([#1292](https://github.com/launchdarkly-labs/js-core/issues/1292)) ([d7ed722](https://github.com/launchdarkly-labs/js-core/commit/d7ed7229d277e6ff96929c279279d85b094d596f))
* Export LDMigrationError and LDMigrationTracker from the Cloudflare SDK ([#1988](https://github.com/launchdarkly-labs/js-core/issues/1988)) ([33c5433](https://github.com/launchdarkly-labs/js-core/commit/33c5433b44ff3664698d669ce8543dbaeedb42e6))
* remove `rollup-plugin-dts` dependency ([#1288](https://github.com/launchdarkly-labs/js-core/issues/1288)) ([ea64b82](https://github.com/launchdarkly-labs/js-core/commit/ea64b82a2c9d93d5c94fbc6e972cd9b5646b7cf1))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-server-sdk-common-edge bumped from 2.6.47 to 2.6.48
</details>

<details><summary>eventsource: 0.3.0</summary>

## [0.3.0](https://github.com/launchdarkly-labs/js-core/compare/eventsource-v0.2.4...eventsource-v0.3.0) (2026-11-10)


### Features

* Add optional streaming members to the platform fetch types ([#2092](https://github.com/launchdarkly-labs/js-core/issues/2092)) ([4137805](https://github.com/launchdarkly-labs/js-core/commit/4137805723e14f1f21c07b45039c4eeda9889519))
* Add the fetch-based EventSource client to @launchdarkly/eventsource ([#2030](https://github.com/launchdarkly-labs/js-core/issues/2030)) ([1414654](https://github.com/launchdarkly-labs/js-core/commit/141465483b56928f50def6e66c494f2d117517cd))
* pre-release of `@launchdarkly/eventsource` ([#2088](https://github.com/launchdarkly-labs/js-core/issues/2088)) ([bf43b71](https://github.com/launchdarkly-labs/js-core/commit/bf43b71939bc63662b1a9bcbf828b339aafc359f))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/js-sdk-common bumped from 2.32.2 to 2.33.0
</details>

<details><summary>fastly-server-sdk: 0.2.42</summary>

## [0.2.42](https://github.com/launchdarkly-labs/js-core/compare/fastly-server-sdk-v0.2.41...fastly-server-sdk-v0.2.42) (2026-11-10)


### Bug Fixes

* Accept eventsUri option in Fastly SDK init() ([#1791](https://github.com/launchdarkly-labs/js-core/issues/1791)) ([18deecd](https://github.com/launchdarkly-labs/js-core/commit/18deecddc53714850a31a8d796720fb101535af2))
* Disable event processor background flush timers for edge clients ([#1797](https://github.com/launchdarkly-labs/js-core/issues/1797)) ([bac7f81](https://github.com/launchdarkly-labs/js-core/commit/bac7f81e07bcd0bbbf2abcfd15cb6ca7f3e512cb))
* Do not cache rejected KV loads in Fastly EdgeFeatureStore ([#1796](https://github.com/launchdarkly-labs/js-core/issues/1796)) ([8f51339](https://github.com/launchdarkly-labs/js-core/commit/8f51339c6d09d2ac6f86636f2b61ae4adeb7d16e))
* explicit return types and TS6 source compatibility fixes ([#1418](https://github.com/launchdarkly-labs/js-core/issues/1418)) ([9c131a2](https://github.com/launchdarkly-labs/js-core/commit/9c131a2e731c97a7fd4cf7ec1fe11efbbf49d6fb))
* Export BasicLogger, LDContext, and LDOptions from the Fastly SDK ([#1987](https://github.com/launchdarkly-labs/js-core/issues/1987)) ([f5c3170](https://github.com/launchdarkly-labs/js-core/commit/f5c3170469c8aee4d821f163116eb11492ce1999))


### Performance Improvements

* Import only used crypto-js submodules in Fastly SDK ([#1795](https://github.com/launchdarkly-labs/js-core/issues/1795)) ([5c12f19](https://github.com/launchdarkly-labs/js-core/commit/5c12f19f5c0b6a73ad12b8ca1e1450a38a45f9a0))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
</details>

<details><summary>jest: 1.0.42</summary>

## [1.0.42](https://github.com/launchdarkly-labs/js-core/compare/jest-v1.0.41...jest-v1.0.42) (2026-11-10)


### Bug Fixes

* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/react-native-client-sdk bumped from ~10.23.4 to ~10.24.0
</details>

<details><summary>js-client-sdk: 4.15.0</summary>

## [4.15.0](https://github.com/launchdarkly-labs/js-core/compare/js-client-sdk-v4.14.2...js-client-sdk-v4.15.0) (2026-11-10)


### Features

* Add a shared WebSocket base to the contract test utils and use it in the browser contract tests ([#2136](https://github.com/launchdarkly-labs/js-core/issues/2136)) ([af2f096](https://github.com/launchdarkly-labs/js-core/commit/af2f096c72a198ceb5beda50437068aa6d354006))
* Add an opt-in fetch-based EventSource entry to the browser SDK ([#2033](https://github.com/launchdarkly-labs/js-core/issues/2033)) ([7a21f6f](https://github.com/launchdarkly-labs/js-core/commit/7a21f6f717acd88a45d2a97e634126cb7d263630))
* Add eventSource factory and usePost options to the client-side SDK common ([#2032](https://github.com/launchdarkly-labs/js-core/issues/2032)) ([f514d5b](https://github.com/launchdarkly-labs/js-core/commit/f514d5bc1fd7c995ed63e7eae3ff4624889ea941))
* add retry logic to FDv2 polling initializer ([#1230](https://github.com/launchdarkly-labs/js-core/issues/1230)) ([fe8bd37](https://github.com/launchdarkly-labs/js-core/commit/fe8bd375af48edfcfe83822bbbbe4546551c90d9))
* adding start() method to common client sdk package ([#1244](https://github.com/launchdarkly-labs/js-core/issues/1244)) ([7f5f468](https://github.com/launchdarkly-labs/js-core/commit/7f5f468f93eaa4655d1432af5e7bf8819104700a))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2059](https://github.com/launchdarkly-labs/js-core/issues/2059)) ([a80e7ee](https://github.com/launchdarkly-labs/js-core/commit/a80e7ee89736f69eb0d3b7080c03759dbb8de6a5))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2098](https://github.com/launchdarkly-labs/js-core/issues/2098)) ([0d5e30d](https://github.com/launchdarkly-labs/js-core/commit/0d5e30d1d9c904c1b34020075d397b06523a5c3a))
* expose setConnectionMode on browser SDK ([#1232](https://github.com/launchdarkly-labs/js-core/issues/1232)) ([9019808](https://github.com/launchdarkly-labs/js-core/commit/9019808edd5f78cbddd9b031da1589cbaa49938f))
* **js-client-sdk:** add ability to customize storage impl ([#1404](https://github.com/launchdarkly-labs/js-core/issues/1404)) ([77864cb](https://github.com/launchdarkly-labs/js-core/commit/77864cb04f737c8aab4476422a2a2422c7be978c))
* Prepare FDv2 EAP for browser and React Native SDKs ([#1419](https://github.com/launchdarkly-labs/js-core/issues/1419)) ([6ee9c51](https://github.com/launchdarkly-labs/js-core/commit/6ee9c515fe9aaf999fd7f0eb722d6df9a2d208d8))
* wire fdv1-fallback capability into node-client, browser, and react-native contract-test entities ([#1858](https://github.com/launchdarkly-labs/js-core/issues/1858)) ([462c950](https://github.com/launchdarkly-labs/js-core/commit/462c95098d2143802939cd010cfacd39e26a1c22))
* wire registerDebugOverrides through client common ([#1368](https://github.com/launchdarkly-labs/js-core/issues/1368)) ([9011c2a](https://github.com/launchdarkly-labs/js-core/commit/9011c2a76f7460770efe3c07b3e16338b647d9df))


### Bug Fixes

* add defensive cycle guard to prerequisite evaluation ([#1816](https://github.com/launchdarkly-labs/js-core/issues/1816)) ([9426b42](https://github.com/launchdarkly-labs/js-core/commit/9426b42dbb5e96914c62462ff7281ec6e24727b3))
* correct typeof comparisons in browser SDK ([#1301](https://github.com/launchdarkly-labs/js-core/issues/1301)) ([f4bd636](https://github.com/launchdarkly-labs/js-core/commit/f4bd6369e03353f38abfdf1b4b8ef90aa7c79ffb))
* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* Ensure FDv2 waits for network results instead of cached results. ([#1397](https://github.com/launchdarkly-labs/js-core/issues/1397)) ([142da36](https://github.com/launchdarkly-labs/js-core/commit/142da363702264debef25796f92760b8ec6ab342))
* FDv2 - Support dynamic reconnect URL for streaming. Handle 'error' event types for SSE. ([#1252](https://github.com/launchdarkly-labs/js-core/issues/1252)) ([4ef6cdd](https://github.com/launchdarkly-labs/js-core/commit/4ef6cdd3f07a15e9a6b3b831defcf41d10e6334b))
* **js-client-sdk:** better `undefined` handling ([#1303](https://github.com/launchdarkly-labs/js-core/issues/1303)) ([4818678](https://github.com/launchdarkly-labs/js-core/commit/4818678282bc6aa54aca00c2d1cb02d2a6b14bf8))
* **js-client-sdk:** better handling for event batches over 64 kb ([3a6c08a](https://github.com/launchdarkly-labs/js-core/commit/3a6c08aa83b99f27dbbf08c6af458c675f1e1723))
* Keep JSDoc in sdk-client declarations and show inherited LDClient docs ([#2181](https://github.com/launchdarkly-labs/js-core/issues/2181)) ([09b5f99](https://github.com/launchdarkly-labs/js-core/commit/09b5f99ba0f605f1d809411cd2a8762189e947a7))
* **sdk-client:** `executeAfterTrack` ordering ([58e063b](https://github.com/launchdarkly-labs/js-core/commit/58e063bad4651e25beea644425bea23a20f4870f))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-client-sdk-common bumped from 1.35.2 to 1.36.0
  * optionalDependencies
    * @launchdarkly/eventsource bumped from 0.2.4 to 0.3.0
</details>

<details><summary>js-client-sdk-common: 1.36.0</summary>

## [1.36.0](https://github.com/launchdarkly-labs/js-core/compare/js-client-sdk-common-v1.35.2...js-client-sdk-common-v1.36.0) (2026-11-10)


### Features

* Add an opt-in fetch-based EventSource entry to the browser SDK ([#2033](https://github.com/launchdarkly-labs/js-core/issues/2033)) ([7a21f6f](https://github.com/launchdarkly-labs/js-core/commit/7a21f6f717acd88a45d2a97e634126cb7d263630))
* Add eventSource factory and usePost options to the client-side SDK common ([#2032](https://github.com/launchdarkly-labs/js-core/issues/2032)) ([f514d5b](https://github.com/launchdarkly-labs/js-core/commit/f514d5bc1fd7c995ed63e7eae3ff4624889ea941))
* Add experimental FDv2 support for React Native. ([#1243](https://github.com/launchdarkly-labs/js-core/issues/1243)) ([7ed2c08](https://github.com/launchdarkly-labs/js-core/commit/7ed2c085cd35d35ffd6f48becb5a60f03b07ad1c))
* add FDv1 fallback directive parsing and TTL data model ([#1781](https://github.com/launchdarkly-labs/js-core/issues/1781)) ([4a213c3](https://github.com/launchdarkly-labs/js-core/commit/4a213c31f8afc9f5713a60f3a5517ddbc8004cd5))
* add retry logic to FDv2 polling initializer ([#1230](https://github.com/launchdarkly-labs/js-core/issues/1230)) ([fe8bd37](https://github.com/launchdarkly-labs/js-core/commit/fe8bd375af48edfcfe83822bbbbe4546551c90d9))
* adding start() method to common client sdk package ([#1244](https://github.com/launchdarkly-labs/js-core/issues/1244)) ([7f5f468](https://github.com/launchdarkly-labs/js-core/commit/7f5f468f93eaa4655d1432af5e7bf8819104700a))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2098](https://github.com/launchdarkly-labs/js-core/issues/2098)) ([0d5e30d](https://github.com/launchdarkly-labs/js-core/commit/0d5e30d1d9c904c1b34020075d397b06523a5c3a))
* expose setConnectionMode on browser SDK ([#1232](https://github.com/launchdarkly-labs/js-core/issues/1232)) ([9019808](https://github.com/launchdarkly-labs/js-core/commit/9019808edd5f78cbddd9b031da1589cbaa49938f))
* **js-client-sdk:** add ability to customize storage impl ([#1404](https://github.com/launchdarkly-labs/js-core/issues/1404)) ([77864cb](https://github.com/launchdarkly-labs/js-core/commit/77864cb04f737c8aab4476422a2a2422c7be978c))
* Move FDv1 fallback directive parsing to the shared package ([#1981](https://github.com/launchdarkly-labs/js-core/issues/1981)) ([e7a3b66](https://github.com/launchdarkly-labs/js-core/commit/e7a3b6647caf3210c9cea40e7818f164537aa50f))
* Prepare FDv2 EAP for browser and React Native SDKs ([#1419](https://github.com/launchdarkly-labs/js-core/issues/1419)) ([6ee9c51](https://github.com/launchdarkly-labs/js-core/commit/6ee9c515fe9aaf999fd7f0eb722d6df9a2d208d8))
* support per-mode FDv1 fallback configuration ([#1246](https://github.com/launchdarkly-labs/js-core/issues/1246)) ([9956bce](https://github.com/launchdarkly-labs/js-core/commit/9956bce2cc70642c63da79f904c5d5554892e046))
* support waitForNetworkResults in FDv2 data manager ([#1280](https://github.com/launchdarkly-labs/js-core/issues/1280)) ([df7fa9e](https://github.com/launchdarkly-labs/js-core/commit/df7fa9e571703132ffa697e8a005f31d7ab866dd))
* warn that payload filtering has no effect with FDv2 ([#1984](https://github.com/launchdarkly-labs/js-core/issues/1984)) ([5e37aca](https://github.com/launchdarkly-labs/js-core/commit/5e37aca49398ff01aa0c71b75d106699a1461cd3))
* wire registerDebugOverrides through client common ([#1368](https://github.com/launchdarkly-labs/js-core/issues/1368)) ([9011c2a](https://github.com/launchdarkly-labs/js-core/commit/9011c2a76f7460770efe3c07b3e16338b647d9df))


### Bug Fixes

* add defensive cycle guard to prerequisite evaluation ([#1816](https://github.com/launchdarkly-labs/js-core/issues/1816)) ([9426b42](https://github.com/launchdarkly-labs/js-core/commit/9426b42dbb5e96914c62462ff7281ec6e24727b3))
* client side fdv2 payload type ([#1778](https://github.com/launchdarkly-labs/js-core/issues/1778)) ([0b9fde5](https://github.com/launchdarkly-labs/js-core/commit/0b9fde5d88dc0816937f5fb0baa6ca205388e53f))
* **common:** remove non-spec fields from FDv2 GoodbyeObject ([#1341](https://github.com/launchdarkly-labs/js-core/issues/1341)) ([feb9aa7](https://github.com/launchdarkly-labs/js-core/commit/feb9aa7f6217bc9b3a9794bc71867e14112ea928))
* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* FDv2 - Support dynamic reconnect URL for streaming. Handle 'error' event types for SSE. ([#1252](https://github.com/launchdarkly-labs/js-core/issues/1252)) ([4ef6cdd](https://github.com/launchdarkly-labs/js-core/commit/4ef6cdd3f07a15e9a6b3b831defcf41d10e6334b))
* FDv2 -- cache initializer returns transfer-none on cache miss ([#1275](https://github.com/launchdarkly-labs/js-core/issues/1275)) ([7bf3c31](https://github.com/launchdarkly-labs/js-core/commit/7bf3c3122dc01146988d3722ff659f011967ea3d))
* FDv2 Only -- Adjust the behavior of initialization when only cache initializers are available. ([#1304](https://github.com/launchdarkly-labs/js-core/issues/1304)) ([9a2b25a](https://github.com/launchdarkly-labs/js-core/commit/9a2b25afd1507b2b6e42b85a32edea7a40be8bb0))
* Ignore FDv2 put-object and delete-object events with unsupported kinds ([#2109](https://github.com/launchdarkly-labs/js-core/issues/2109)) ([2729c04](https://github.com/launchdarkly-labs/js-core/commit/2729c046493ba4c84ce0f4abf5be0b369d86c68c))
* Keep JSDoc in sdk-client declarations and show inherited LDClient docs ([#2181](https://github.com/launchdarkly-labs/js-core/issues/2181)) ([09b5f99](https://github.com/launchdarkly-labs/js-core/commit/09b5f99ba0f605f1d809411cd2a8762189e947a7))
* migrate anonymous context namespace to general namespace ([#1312](https://github.com/launchdarkly-labs/js-core/issues/1312)) ([afbed0f](https://github.com/launchdarkly-labs/js-core/commit/afbed0f299808f21dd4a8aa5159fe8d31879e1b9))
* Preserve FDv2 protocol error listeners and stop misreporting server error frames ([#2028](https://github.com/launchdarkly-labs/js-core/issues/2028)) ([3d80bef](https://github.com/launchdarkly-labs/js-core/commit/3d80bef9f56872ed1c625ba1518aed2ebe30c1fd))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))
* **sdk-client-common:** `identify()` bootstrap does not set flagstore in FDv2 ([#1837](https://github.com/launchdarkly-labs/js-core/issues/1837)) ([574f816](https://github.com/launchdarkly-labs/js-core/commit/574f8164ed930423c44d82d4c1ad210387bfc5b9))
* **sdk-client:** `executeAfterTrack` ordering ([58e063b](https://github.com/launchdarkly-labs/js-core/commit/58e063bad4651e25beea644425bea23a20f4870f))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-sdk-common bumped from 2.32.2 to 2.33.0
</details>

<details><summary>js-sdk-common: 2.33.0</summary>

## [2.33.0](https://github.com/launchdarkly-labs/js-core/compare/js-sdk-common-v2.32.2...js-sdk-common-v2.33.0) (2026-11-10)


### Features

* add a reusable retry state controller for RETRY-conformant backoff ([#2045](https://github.com/launchdarkly-labs/js-core/issues/2045)) ([721b559](https://github.com/launchdarkly-labs/js-core/commit/721b559ff15bb13e3344921de9539e2663d0f0c8))
* Add experimental support for file-based overrides. ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Add optional file stats, watch error reporting, and the changed entry name to the platform filesystem interface ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Add optional streaming members to the platform fetch types ([#2092](https://github.com/launchdarkly-labs/js-core/issues/2092)) ([4137805](https://github.com/launchdarkly-labs/js-core/commit/4137805723e14f1f21c07b45039c4eeda9889519))
* add X-LaunchDarkly-Instance-Id header to server-node SDK (SDK-2358) ([#1377](https://github.com/launchdarkly-labs/js-core/issues/1377)) ([814dc0b](https://github.com/launchdarkly-labs/js-core/commit/814dc0bfd6b152385f3a758f9eeca37a0f9f08e8))
* **common:** add a shared `monotonicNow()` method ([#2083](https://github.com/launchdarkly-labs/js-core/issues/2083)) ([83edf68](https://github.com/launchdarkly-labs/js-core/commit/83edf68b96fdbde40a91b81cad62b7ec9637c5eb))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2059](https://github.com/launchdarkly-labs/js-core/issues/2059)) ([a80e7ee](https://github.com/launchdarkly-labs/js-core/commit/a80e7ee89736f69eb0d3b7080c03759dbb8de6a5))
* Migrate the Node.js server and client SDKs to @launchdarkly/eventsource through the platform fetch ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* Move FDv1 fallback directive parsing to the shared package ([#1981](https://github.com/launchdarkly-labs/js-core/issues/1981)) ([e7a3b66](https://github.com/launchdarkly-labs/js-core/commit/e7a3b6647caf3210c9cea40e7818f164537aa50f))
* Verify TLS certificates on streaming connections by default; a stream served by a private CA now requires tlsParams ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))


### Bug Fixes

* Allow polling and event delivery to connect through a proxy when a private CA is configured ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* Coalesce bursts of file change notifications into one file data reload ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* **common:** remove non-spec fields from FDv2 GoodbyeObject ([#1341](https://github.com/launchdarkly-labs/js-core/issues/1341)) ([feb9aa7](https://github.com/launchdarkly-labs/js-core/commit/feb9aa7f6217bc9b3a9794bc71867e14112ea928))
* Detect rename-based writes and recreated files in the file data source by watching the containing directories ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* explicit return types and TS6 source compatibility fixes ([#1418](https://github.com/launchdarkly-labs/js-core/issues/1418)) ([9c131a2](https://github.com/launchdarkly-labs/js-core/commit/9c131a2e731c97a7fd4cf7ec1fe11efbbf49d6fb))
* FDv2 - Support dynamic reconnect URL for streaming. Handle 'error' event types for SSE. ([#1252](https://github.com/launchdarkly-labs/js-core/issues/1252)) ([4ef6cdd](https://github.com/launchdarkly-labs/js-core/commit/4ef6cdd3f07a15e9a6b3b831defcf41d10e6334b))
* Handle flag keys that are names of built-in object members ([#2170](https://github.com/launchdarkly-labs/js-core/issues/2170)) ([4a18699](https://github.com/launchdarkly-labs/js-core/commit/4a18699619e9335e905d88431dbdd1aefeb16a66))
* Ignore FDv2 put-object and delete-object events with unsupported kinds ([#2109](https://github.com/launchdarkly-labs/js-core/issues/2109)) ([2729c04](https://github.com/launchdarkly-labs/js-core/commit/2729c046493ba4c84ce0f4abf5be0b369d86c68c))
* **js-client-sdk:** better handling for event batches over 64 kb ([3a6c08a](https://github.com/launchdarkly-labs/js-core/commit/3a6c08aa83b99f27dbbf08c6af458c675f1e1723))
* Keep non-string first arguments in log messages ([#2077](https://github.com/launchdarkly-labs/js-core/issues/2077)) ([990df31](https://github.com/launchdarkly-labs/js-core/commit/990df3140b5a1c45ced09aef793dc249e3b49776))
* Only redact anonymous contexts in custom events for server SDKs ([#1814](https://github.com/launchdarkly-labs/js-core/issues/1814)) ([5a3b3fb](https://github.com/launchdarkly-labs/js-core/commit/5a3b3fbc59e9a0b2d65221d65e54078ffa1bf433))
* Preserve FDv2 protocol error listeners and stop misreporting server error frames ([#2028](https://github.com/launchdarkly-labs/js-core/issues/2028)) ([3d80bef](https://github.com/launchdarkly-labs/js-core/commit/3d80bef9f56872ed1c625ba1518aed2ebe30c1fd))
* Re-establish the file data watch when a watched directory is deleted and created again ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Redact anonymous context attributes in migration op and custom events ([#1809](https://github.com/launchdarkly-labs/js-core/issues/1809)) ([c84ec48](https://github.com/launchdarkly-labs/js-core/commit/c84ec485e33ef27cc34610ec838b5466f3a5c96e))
* Report file data read and processing failures through the error handler instead of an unhandled promise rejection ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))
* Retry a failed file data reload and keep the last good data in effect ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* **server-node:** honor x-ld-fd-fallback directive in FDv2 initializer phase ([#1342](https://github.com/launchdarkly-labs/js-core/issues/1342)) ([a80eaca](https://github.com/launchdarkly-labs/js-core/commit/a80eacaafa6174e5f1b4fe21ba11534fdf1f92a8))
* Stop format() from hanging on a trailing percent sign ([#2056](https://github.com/launchdarkly-labs/js-core/issues/2056)) ([c5114ec](https://github.com/launchdarkly-labs/js-core/commit/c5114ecf5dc32826f260744b0e4aa5c4a7f633d6))
</details>

<details><summary>js-server-sdk-common: 2.27.0</summary>

## [2.27.0](https://github.com/launchdarkly-labs/js-core/compare/js-server-sdk-common-v2.26.4...js-server-sdk-common-v2.27.0) (2026-11-10)


### Features

* Add experimental support for file-based overrides. ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Add FDv2 persistent store write-back recovery ([#2011](https://github.com/launchdarkly-labs/js-core/issues/2011)) ([9a785cc](https://github.com/launchdarkly-labs/js-core/commit/9a785cc109b60f206803125871298f261db391dd))
* Add optional file stats, watch error reporting, and the changed entry name to the platform filesystem interface ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* add X-LaunchDarkly-Instance-Id header to server-node SDK (SDK-2358) ([#1377](https://github.com/launchdarkly-labs/js-core/issues/1377)) ([814dc0b](https://github.com/launchdarkly-labs/js-core/commit/814dc0bfd6b152385f3a758f9eeca37a0f9f08e8))
* **common:** add a shared `monotonicNow()` method ([#2083](https://github.com/launchdarkly-labs/js-core/issues/2083)) ([83edf68](https://github.com/launchdarkly-labs/js-core/commit/83edf68b96fdbde40a91b81cad62b7ec9637c5eb))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2059](https://github.com/launchdarkly-labs/js-core/issues/2059)) ([a80e7ee](https://github.com/launchdarkly-labs/js-core/commit/a80e7ee89736f69eb0d3b7080c03759dbb8de6a5))
* Migrate the Node.js server and client SDKs to @launchdarkly/eventsource through the platform fetch ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* Propagate store errors and the availability check through the persistence wrapper ([#2010](https://github.com/launchdarkly-labs/js-core/issues/2010)) ([a752f93](https://github.com/launchdarkly-labs/js-core/commit/a752f93c4233b98868fc8dd71a7c7282134860c2))
* **sdk-server-common:** add support for custom base uris in FDv2 datasources  ([#1827](https://github.com/launchdarkly-labs/js-core/issues/1827)) ([5d028c3](https://github.com/launchdarkly-labs/js-core/commit/5d028c36ab308973957dff226839026994b70fd2))
* Verify TLS certificates on streaming connections by default; a stream served by a private CA now requires tlsParams ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* warn that payload filtering has no effect with FDv2 ([#1984](https://github.com/launchdarkly-labs/js-core/issues/1984)) ([5e37aca](https://github.com/launchdarkly-labs/js-core/commit/5e37aca49398ff01aa0c71b75d106699a1461cd3))


### Bug Fixes

* ability to handle FDv1 `flagValues` shorthand map to FDv2FiledataInitializer ([#1811](https://github.com/launchdarkly-labs/js-core/issues/1811)) ([cbdaf6e](https://github.com/launchdarkly-labs/js-core/commit/cbdaf6ec020e0567c640ce73c9978c1252c7ff35))
* Allow polling and event delivery to connect through a proxy when a private CA is configured ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* Avoid querying a persistent store on every evaluation of an unknown flag ([#2169](https://github.com/launchdarkly-labs/js-core/issues/2169)) ([da1cd35](https://github.com/launchdarkly-labs/js-core/commit/da1cd35d196cafa2b29925aa65306ccc2201e865))
* Base the validity of the uninitialized all flags state on the override layer's flags ([#2132](https://github.com/launchdarkly-labs/js-core/issues/2132)) ([9cafac5](https://github.com/launchdarkly-labs/js-core/commit/9cafac5abf2933146a5d78636bb48b7f4f23de02))
* Coalesce bursts of file change notifications into one file data reload ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* custom featureStores in FDv2 does not get wrapped as TransactionalFeatureStore. ([#1812](https://github.com/launchdarkly-labs/js-core/issues/1812)) ([c687a97](https://github.com/launchdarkly-labs/js-core/commit/c687a9702db83d0b1093c8c794bee6bca89c856a))
* Detect rename-based writes and recreated files in the file data source by watching the containing directories ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Disable event processor background flush timers for edge clients ([#1797](https://github.com/launchdarkly-labs/js-core/issues/1797)) ([bac7f81](https://github.com/launchdarkly-labs/js-core/commit/bac7f81e07bcd0bbbf2abcfd15cb6ca7f3e512cb))
* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* explicit return types and TS6 source compatibility fixes ([#1418](https://github.com/launchdarkly-labs/js-core/issues/1418)) ([9c131a2](https://github.com/launchdarkly-labs/js-core/commit/9c131a2e731c97a7fd4cf7ec1fe11efbbf49d6fb))
* Handle flag keys that are names of built-in object members ([#2170](https://github.com/launchdarkly-labs/js-core/issues/2170)) ([4a18699](https://github.com/launchdarkly-labs/js-core/commit/4a18699619e9335e905d88431dbdd1aefeb16a66))
* Ignore FDv2 put-object and delete-object events with unsupported kinds ([#2109](https://github.com/launchdarkly-labs/js-core/issues/2109)) ([2729c04](https://github.com/launchdarkly-labs/js-core/commit/2729c046493ba4c84ce0f4abf5be0b369d86c68c))
* Keep a flag named __proto__ in file data, change events and persistent store reads ([#2174](https://github.com/launchdarkly-labs/js-core/issues/2174)) ([1ffb29b](https://github.com/launchdarkly-labs/js-core/commit/1ffb29b29362f951b10cb91cb04f68c6cccb2e6f))
* Log the cached-data evaluation warning only once per client ([#2015](https://github.com/launchdarkly-labs/js-core/issues/2015)) ([0bb2164](https://github.com/launchdarkly-labs/js-core/commit/0bb2164fb9e60817af3a5b11e714d14bc7681cdc))
* Make TestData valueForAll return its value when targeting is off ([#2177](https://github.com/launchdarkly-labs/js-core/issues/2177)) ([fc8c1f6](https://github.com/launchdarkly-labs/js-core/commit/fc8c1f641eadbec54f811e6bea27c6928f46b2eb))
* Notify overridden flags when the LaunchDarkly data they depend on changes ([#2108](https://github.com/launchdarkly-labs/js-core/issues/2108)) ([1c21ae9](https://github.com/launchdarkly-labs/js-core/commit/1c21ae9c1ad9c35a8962e73499187978c0df8d5f))
* Only redact anonymous contexts in custom events for server SDKs ([#1814](https://github.com/launchdarkly-labs/js-core/issues/1814)) ([5a3b3fb](https://github.com/launchdarkly-labs/js-core/commit/5a3b3fbc59e9a0b2d65221d65e54078ffa1bf433))
* **persistent-store:** add error logs for upsert ([#1985](https://github.com/launchdarkly-labs/js-core/issues/1985)) ([5ff1cf2](https://github.com/launchdarkly-labs/js-core/commit/5ff1cf240f6c197c38cc1caceabadf12b3c89ea5))
* Preserve FDv2 protocol error listeners and stop misreporting server error frames ([#2028](https://github.com/launchdarkly-labs/js-core/issues/2028)) ([3d80bef](https://github.com/launchdarkly-labs/js-core/commit/3d80bef9f56872ed1c625ba1518aed2ebe30c1fd))
* Prevent TestData from throwing for a flag named constructor or toString ([#2173](https://github.com/launchdarkly-labs/js-core/issues/2173)) ([4e58d1d](https://github.com/launchdarkly-labs/js-core/commit/4e58d1d08d20f46ba46bbdd92a1b52b3d665e3b7))
* Re-establish the file data watch when a watched directory is deleted and created again ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Report file data read and processing failures through the error handler instead of an unhandled promise rejection ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Retry a failed file data reload and keep the last good data in effect ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Return a malformed flag result instead of throwing for a definition the evaluator cannot read ([#2095](https://github.com/launchdarkly-labs/js-core/issues/2095)) ([22038e1](https://github.com/launchdarkly-labs/js-core/commit/22038e10bb69f2f7b43ffc256572354bd2343626))
* **sdk-server-common:** use subpath import for `semver` module ([#1885](https://github.com/launchdarkly-labs/js-core/issues/1885)) ([2de6c8c](https://github.com/launchdarkly-labs/js-core/commit/2de6c8cc39e6b7a4e4092af0731b2de124d56b94))
* Serialize flags and segments without modifying the stored objects ([#2080](https://github.com/launchdarkly-labs/js-core/issues/2080)) ([28d0738](https://github.com/launchdarkly-labs/js-core/commit/28d0738bddb7baeece0a7ded4962e71875801670))
* server sdk could send user agent headers under a different header name ([#1860](https://github.com/launchdarkly-labs/js-core/issues/1860)) ([669662a](https://github.com/launchdarkly-labs/js-core/commit/669662a304c10bcb2b683e0c7ea990f43679916b))
* **server-node:** honor x-ld-fd-fallback directive in FDv2 initializer phase ([#1342](https://github.com/launchdarkly-labs/js-core/issues/1342)) ([a80eaca](https://github.com/launchdarkly-labs/js-core/commit/a80eacaafa6174e5f1b4fe21ba11534fdf1f92a8))
* Treat a repeated override file path in a different case as a repeat on Windows ([#2134](https://github.com/launchdarkly-labs/js-core/issues/2134)) ([d331546](https://github.com/launchdarkly-labs/js-core/commit/d3315463a3142e1e90edf7589a0f77d8f53406b3))
* Warn when offline mode skips the override source, and ignore snapshots after close ([#2133](https://github.com/launchdarkly-labs/js-core/issues/2133)) ([612918c](https://github.com/launchdarkly-labs/js-core/commit/612918cf89b76b587fe681837f7919c9d1f311d6))
* Wire timeout option through to flag polling and event delivery requests ([#1760](https://github.com/launchdarkly-labs/js-core/issues/1760)) ([e18998e](https://github.com/launchdarkly-labs/js-core/commit/e18998eb339a7edc1e059c2f6832afe2739b0bd6))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-sdk-common bumped from 2.32.2 to 2.33.0
</details>

<details><summary>js-server-sdk-common-edge: 2.6.48</summary>

## [2.6.48](https://github.com/launchdarkly-labs/js-core/compare/js-server-sdk-common-edge-v2.6.47...js-server-sdk-common-edge-v2.6.48) (2026-11-10)


### Bug Fixes

* explicit return types and TS6 source compatibility fixes ([#1418](https://github.com/launchdarkly-labs/js-core/issues/1418)) ([9c131a2](https://github.com/launchdarkly-labs/js-core/commit/9c131a2e731c97a7fd4cf7ec1fe11efbbf49d6fb))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
</details>

<details><summary>node-client-sdk: 5.0.0</summary>

## [5.0.0](https://github.com/launchdarkly-labs/js-core/compare/node-client-sdk-v4.4.3...node-client-sdk-v5.0.0) (2026-11-10)


###   BREAKING CHANGES

* `identify()` resolves an identify result and no longer throws
* The on-disk persistent cache format changed; v3 cache data will not be read by v4 and the anonymous key will be regenerated on first identify.
* pre-release `@launchdarkly/node-client-sdk` as `0.1.0` ([#1757](https://github.com/launchdarkly-labs/js-core/issues/1757))

### BREAKING-CHANGE

* The package name changed from `launchdarkly-node-client-sdk` to `@launchdarkly/node-client-sdk`. ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))


### Features

* `identify()` resolves an identify result and no longer throws ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* Add eventSource factory and usePost options to the client-side SDK common ([#2032](https://github.com/launchdarkly-labs/js-core/issues/2032)) ([f514d5b](https://github.com/launchdarkly-labs/js-core/commit/f514d5bc1fd7c995ed63e7eae3ff4624889ea941))
* Add FDv2 data system support to NodeClient ([#1775](https://github.com/launchdarkly-labs/js-core/issues/1775)) ([3ea0f33](https://github.com/launchdarkly-labs/js-core/commit/3ea0f3398d25e8881775937a6ce2872242e4cbcc))
* Add useMobileKey option to NodeOptions ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2098](https://github.com/launchdarkly-labs/js-core/issues/2098)) ([0d5e30d](https://github.com/launchdarkly-labs/js-core/commit/0d5e30d1d9c904c1b34020075d397b06523a5c3a))
* enable FDv1 streaming extended-regime backoff for node-client and electron ([#2102](https://github.com/launchdarkly-labs/js-core/issues/2102)) ([567e3b3](https://github.com/launchdarkly-labs/js-core/commit/567e3b32629b4d1c75b93f7bcbfc3be3dc28d546))
* Evaluation, identify, and track hooks ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* Inspector support for flag and context state ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* Migrate the Node.js server and client SDKs to @launchdarkly/eventsource through the platform fetch ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* **node-client-sdk:** adding ability to override storage implementation ([#1753](https://github.com/launchdarkly-labs/js-core/issues/1753)) ([a04ec92](https://github.com/launchdarkly-labs/js-core/commit/a04ec9215e069b7195c6e7aba21c09b39c607837))
* **node-client-sdk:** adding support for mobile usage ([#1768](https://github.com/launchdarkly-labs/js-core/issues/1768)) ([71d47a7](https://github.com/launchdarkly-labs/js-core/commit/71d47a70d303df349592a1573eb927d983673782))
* Plugin extension surface with `applicationInfo` metadata ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* pre-release `@launchdarkly/node-client-sdk` as `0.1.0` ([#1757](https://github.com/launchdarkly-labs/js-core/issues/1757)) ([e14e6f9](https://github.com/launchdarkly-labs/js-core/commit/e14e6f91148e1c7b65756cb653a45ebad883d1d6))
* Runtime connection-mode control via `setConnectionMode` ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* Storage configuration with file-backed default and custom-implementation override ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* support client side secure mode with client side id ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* support wrapper header ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* TLS configuration via `tlsParams` ([4116d2f](https://github.com/launchdarkly-labs/js-core/commit/4116d2f4cee34d0c2b8041b2b2a93a2a61820471))
* Verify TLS certificates on streaming connections by default; a stream served by a private CA now requires tlsParams ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* wire fdv1-fallback capability into node-client, browser, and react-native contract-test entities ([#1858](https://github.com/launchdarkly-labs/js-core/issues/1858)) ([462c950](https://github.com/launchdarkly-labs/js-core/commit/462c95098d2143802939cd010cfacd39e26a1c22))


### Bug Fixes

* Allow polling and event delivery to connect through a proxy when a private CA is configured ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* **node-client-sdk:** adding docs to clarify FDv2 datasystem will ignore `initialConnectionMode` ([#1835](https://github.com/launchdarkly-labs/js-core/issues/1835)) ([b43c784](https://github.com/launchdarkly-labs/js-core/commit/b43c78460a738b38eabc8b72698ca86cf1faafd3))
* **node-client-sdk:** better handling for bad filesystem states ([#1799](https://github.com/launchdarkly-labs/js-core/issues/1799)) ([8f58b35](https://github.com/launchdarkly-labs/js-core/commit/8f58b3515f004070034561c804dcb7586471906b))
* **node-client-sdk:** correct sdk_metadata.json entry and restore userAgentBase ([#1840](https://github.com/launchdarkly-labs/js-core/issues/1840)) ([5da9ef6](https://github.com/launchdarkly-labs/js-core/commit/5da9ef63716d7b5aa24c2199149ea32ef8f76d57))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/eventsource bumped from 0.2.4 to 0.3.0
    * @launchdarkly/js-client-sdk-common bumped from 1.35.2 to 1.36.0
</details>

<details><summary>node-server-sdk: 9.17.0</summary>

## [9.17.0](https://github.com/launchdarkly-labs/js-core/compare/node-server-sdk-v9.16.4...node-server-sdk-v9.17.0) (2026-11-10)


### Features

* add a custom proxyAgent option to the Node server SDK ([#1438](https://github.com/launchdarkly-labs/js-core/issues/1438)) ([c74dae7](https://github.com/launchdarkly-labs/js-core/commit/c74dae74e01fa2f36ec91086f53658d4644d9c9f))
* Add experimental support for file-based overrides. ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Add optional file stats, watch error reporting, and the changed entry name to the platform filesystem interface ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* add X-LaunchDarkly-Instance-Id header to server-node SDK (SDK-2358) ([#1377](https://github.com/launchdarkly-labs/js-core/issues/1377)) ([814dc0b](https://github.com/launchdarkly-labs/js-core/commit/814dc0bfd6b152385f3a758f9eeca37a0f9f08e8))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2059](https://github.com/launchdarkly-labs/js-core/issues/2059)) ([a80e7ee](https://github.com/launchdarkly-labs/js-core/commit/a80e7ee89736f69eb0d3b7080c03759dbb8de6a5))
* Migrate the Node.js server and client SDKs to @launchdarkly/eventsource through the platform fetch ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* **sdk-server-common:** add support for custom base uris in FDv2 datasources  ([#1827](https://github.com/launchdarkly-labs/js-core/issues/1827)) ([5d028c3](https://github.com/launchdarkly-labs/js-core/commit/5d028c36ab308973957dff226839026994b70fd2))
* Verify TLS certificates on streaming connections by default; a stream served by a private CA now requires tlsParams ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))


### Bug Fixes

* add SOCKS proxy example and fixes warning logging and proxyAuth reporting ([#1786](https://github.com/launchdarkly-labs/js-core/issues/1786)) ([a5b42ca](https://github.com/launchdarkly-labs/js-core/commit/a5b42ca3bf7d0672bf303cf47036ea801f6b9093))
* Allow polling and event delivery to connect through a proxy when a private CA is configured ([10b57b0](https://github.com/launchdarkly-labs/js-core/commit/10b57b01ce348b216fd98e515740bc5d50830017))
* Coalesce bursts of file change notifications into one file data reload ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Detect rename-based writes and recreated files in the file data source by watching the containing directories ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* Re-establish the file data watch when a watched directory is deleted and created again ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Report file data read and processing failures through the error handler instead of an unhandled promise rejection ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Retry a failed file data reload and keep the last good data in effect ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* **sdk-client:** `executeAfterTrack` ordering ([58e063b](https://github.com/launchdarkly-labs/js-core/commit/58e063bad4651e25beea644425bea23a20f4870f))
* **sdk-server-common:** use subpath import for `semver` module ([#1885](https://github.com/launchdarkly-labs/js-core/issues/1885)) ([2de6c8c](https://github.com/launchdarkly-labs/js-core/commit/2de6c8cc39e6b7a4e4092af0731b2de124d56b94))
* **server-node:** honor x-ld-fd-fallback directive in FDv2 initializer phase ([#1342](https://github.com/launchdarkly-labs/js-core/issues/1342)) ([a80eaca](https://github.com/launchdarkly-labs/js-core/commit/a80eacaafa6174e5f1b4fe21ba11534fdf1f92a8))
* Wire timeout option through to flag polling and event delivery requests ([#1760](https://github.com/launchdarkly-labs/js-core/issues/1760)) ([e18998e](https://github.com/launchdarkly-labs/js-core/commit/e18998eb339a7edc1e059c2f6832afe2739b0bd6))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/eventsource bumped from 0.2.4 to 0.3.0
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
</details>

<details><summary>node-server-sdk-dynamodb: 6.5.0</summary>

## [6.5.0](https://github.com/launchdarkly-labs/js-core/compare/node-server-sdk-dynamodb-v6.4.7...node-server-sdk-dynamodb-v6.5.0) (2026-11-10)


### Features

* Report DynamoDB store errors and implement the availability check ([21e6e7d](https://github.com/launchdarkly-labs/js-core/commit/21e6e7d45cd0f137305cff60c4bf112da8362910))
* Update store peer dep floor to 9.14.1 to better support error reporting and recovery ([#2097](https://github.com/launchdarkly-labs/js-core/issues/2097)) ([1369fa4](https://github.com/launchdarkly-labs/js-core/commit/1369fa4a157fdc3bc175f96ce77d81877a453c22))


### Bug Fixes

* Avoid querying a persistent store on every evaluation of an unknown flag ([#2169](https://github.com/launchdarkly-labs/js-core/issues/2169)) ([da1cd35](https://github.com/launchdarkly-labs/js-core/commit/da1cd35d196cafa2b29925aa65306ccc2201e865))
* **node-server-sdk-dynamodb:** remove unnecessary ioredis package ([#1306](https://github.com/launchdarkly-labs/js-core/issues/1306)) ([5d6c86e](https://github.com/launchdarkly-labs/js-core/commit/5d6c86ec3d6c37abaccf3e88f62735113a0fe966))
* **persistent-store:** add error logs for upsert ([#1985](https://github.com/launchdarkly-labs/js-core/issues/1985)) ([5ff1cf2](https://github.com/launchdarkly-labs/js-core/commit/5ff1cf240f6c197c38cc1caceabadf12b3c89ea5))
* Prevent a hung DynamoDB request from permanently blocking store writes ([21e6e7d](https://github.com/launchdarkly-labs/js-core/commit/21e6e7d45cd0f137305cff60c4bf112da8362910))
* Retry unprocessed DynamoDB batch writes and report failures instead of dropping items ([21e6e7d](https://github.com/launchdarkly-labs/js-core/commit/21e6e7d45cd0f137305cff60c4bf112da8362910))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/node-server-sdk bumped from 9.16.4 to 9.17.0
  * peerDependencies
    * @launchdarkly/node-server-sdk bumped from >=9.14.1 to >=9.17.0
</details>

<details><summary>node-server-sdk-otel: 1.3.44</summary>

## [1.3.44](https://github.com/launchdarkly-labs/js-core/compare/node-server-sdk-otel-v1.3.43...node-server-sdk-otel-v1.3.44) (2026-11-10)


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/node-server-sdk bumped from 9.16.4 to 9.17.0
  * peerDependencies
    * @launchdarkly/node-server-sdk bumped from >=9.11.3 to >=9.17.0
</details>

<details><summary>node-server-sdk-redis: 4.5.0</summary>

## [4.5.0](https://github.com/launchdarkly-labs/js-core/compare/node-server-sdk-redis-v4.4.7...node-server-sdk-redis-v4.5.0) (2026-11-10)


### Features

* Report Redis store errors and implement the availability check ([a9d8d8b](https://github.com/launchdarkly-labs/js-core/commit/a9d8d8be11f95c3e9f107cd8c66dcec3529b8f06))
* Update store peer dep floor to 9.14.1 to better support error reporting and recovery ([#2097](https://github.com/launchdarkly-labs/js-core/issues/2097)) ([1369fa4](https://github.com/launchdarkly-labs/js-core/commit/1369fa4a157fdc3bc175f96ce77d81877a453c22))


### Bug Fixes

* Avoid querying a persistent store on every evaluation of an unknown flag ([#2169](https://github.com/launchdarkly-labs/js-core/issues/2169)) ([da1cd35](https://github.com/launchdarkly-labs/js-core/commit/da1cd35d196cafa2b29925aa65306ccc2201e865))
* **persistent-store:** add error logs for upsert ([#1985](https://github.com/launchdarkly-labs/js-core/issues/1985)) ([5ff1cf2](https://github.com/launchdarkly-labs/js-core/commit/5ff1cf240f6c197c38cc1caceabadf12b3c89ea5))
* Prevent a Redis outage from crashing the process through an unhandled watch rejection ([a9d8d8b](https://github.com/launchdarkly-labs/js-core/commit/a9d8d8be11f95c3e9f107cd8c66dcec3529b8f06))
* Prevent an interrupted write-back from being reported as successful ([a9d8d8b](https://github.com/launchdarkly-labs/js-core/commit/a9d8d8be11f95c3e9f107cd8c66dcec3529b8f06))
* Report write failures promptly during an extended Redis outage ([a9d8d8b](https://github.com/launchdarkly-labs/js-core/commit/a9d8d8be11f95c3e9f107cd8c66dcec3529b8f06))
* settle Redis getAll when HGETALL fails ([#2078](https://github.com/launchdarkly-labs/js-core/issues/2078)) ([bcfce79](https://github.com/launchdarkly-labs/js-core/commit/bcfce7938ee4504c0c49c83ec98384288eef53ee))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/node-server-sdk bumped from 9.16.4 to 9.17.0
  * peerDependencies
    * @launchdarkly/node-server-sdk bumped from >=9.14.1 to >=9.17.0
</details>

<details><summary>openfeature-cloudflare-server: 2.0.0</summary>

## [2.0.0](https://github.com/launchdarkly-labs/js-core/compare/openfeature-cloudflare-server-v1.2.0...openfeature-cloudflare-server-v2.0.0) (2026-11-10)


###   BREAKING CHANGES

* Promote @launchdarkly/openfeature-cloudflare-server to stable v1 ([#1873](https://github.com/launchdarkly-labs/js-core/issues/1873))

### Features

* Add an initialization timeout option to the OpenFeature Cloudflare provider ([#2182](https://github.com/launchdarkly-labs/js-core/issues/2182)) ([ba6ee3a](https://github.com/launchdarkly-labs/js-core/commit/ba6ee3a069adc950db6e59744f2599537445f8d3))
* Promote @launchdarkly/openfeature-cloudflare-server to stable v1 ([#1873](https://github.com/launchdarkly-labs/js-core/issues/1873)) ([4f9b349](https://github.com/launchdarkly-labs/js-core/commit/4f9b3496e81d5d2d552a4e36c870f913137703fd))


### Bug Fixes

* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/openfeature-js-server-common bumped from 2.2.3 to 3.0.0
  * devDependencies
    * @launchdarkly/cloudflare-server-sdk bumped from 2.7.51 to 2.7.52
  * peerDependencies
    * @launchdarkly/cloudflare-server-sdk bumped from ^2.7.0 to ^2.7.52
</details>

<details><summary>openfeature-js-server-common: 3.0.0</summary>

## [3.0.0](https://github.com/launchdarkly-labs/js-core/compare/openfeature-js-server-common-v2.2.3...openfeature-js-server-common-v3.0.0) (2026-11-10)


###   BREAKING CHANGES

* Map LaunchDarkly evaluation reasons to OpenFeature reasons ([#1887](https://github.com/launchdarkly-labs/js-core/issues/1887))
* Map the WRONG_TYPE error kind to TYPE_MISMATCH ([#1888](https://github.com/launchdarkly-labs/js-core/issues/1888))
* release `@launchdarkly/openfeature-js-server-common` ([#1754](https://github.com/launchdarkly-labs/js-core/issues/1754))

### Features

* Add experimental support for file-based overrides. ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Add optional file stats, watch error reporting, and the changed entry name to the platform filesystem interface ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Populate OpenFeature flag metadata from the evaluation reason ([#1869](https://github.com/launchdarkly-labs/js-core/issues/1869)) ([d5bdaeb](https://github.com/launchdarkly-labs/js-core/commit/d5bdaebb515a5357cbdc6da52b5b911bc4af7351))
* release `@launchdarkly/openfeature-js-server-common` ([#1754](https://github.com/launchdarkly-labs/js-core/issues/1754)) ([f83f6db](https://github.com/launchdarkly-labs/js-core/commit/f83f6db16b6c77f1cbc5cfeb4dfd47b7c17b71bf))
* Support zero and indefinite initialization waiting ([#2024](https://github.com/launchdarkly-labs/js-core/issues/2024)) ([8bfd257](https://github.com/launchdarkly-labs/js-core/commit/8bfd257bd561109faa5be0c1a6b6a7620bb2c66f))


### Bug Fixes

* Align OpenFeature context conversion log levels with the provider spec ([#2183](https://github.com/launchdarkly-labs/js-core/issues/2183)) ([c356b22](https://github.com/launchdarkly-labs/js-core/commit/c356b22c8a7226446afc13609b0ec4bfb1d86c0e))
* Coalesce bursts of file change notifications into one file data reload ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Detect rename-based writes and recreated files in the file data source by watching the containing directories ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Ignore non-string and empty keys in OpenFeature context conversion ([#1989](https://github.com/launchdarkly-labs/js-core/issues/1989)) ([6bf9c62](https://github.com/launchdarkly-labs/js-core/commit/6bf9c623ae74d7e0b58b7610bce1675df44a34fc))
* Map LaunchDarkly evaluation reasons to OpenFeature reasons ([#1887](https://github.com/launchdarkly-labs/js-core/issues/1887)) ([70291f4](https://github.com/launchdarkly-labs/js-core/commit/70291f4862384f18ef4e9bf11045c7f4df73a116))
* Map the WRONG_TYPE error kind to TYPE_MISMATCH ([#1888](https://github.com/launchdarkly-labs/js-core/issues/1888)) ([2d60942](https://github.com/launchdarkly-labs/js-core/commit/2d60942d15812fea1cf82be72101492422da813d))
* Re-establish the file data watch when a watched directory is deleted and created again ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Report file data read and processing failures through the error handler instead of an unhandled promise rejection ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Retry a failed file data reload and keep the last good data in effect ([9c0effe](https://github.com/launchdarkly-labs/js-core/commit/9c0effe9d614ce41cf72a3254e25822c32d9d2f2))
* Validate privateAttributes in OpenFeature context conversion ([#1990](https://github.com/launchdarkly-labs/js-core/issues/1990)) ([a65af44](https://github.com/launchdarkly-labs/js-core/commit/a65af447a734a0c8366f845b81b33a7ee47b4845))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-sdk-common bumped from 2.32.2 to 2.33.0
</details>

<details><summary>openfeature-node-server: 3.0.0</summary>

## [3.0.0](https://github.com/launchdarkly-labs/js-core/compare/openfeature-node-server-v2.1.7...openfeature-node-server-v3.0.0) (2026-11-10)


###   BREAKING CHANGES

* Map LaunchDarkly evaluation reasons to OpenFeature reasons ([#1887](https://github.com/launchdarkly-labs/js-core/issues/1887))

### Features

* openfeature-node-server migration ([#1767](https://github.com/launchdarkly-labs/js-core/issues/1767)) ([22fb0b2](https://github.com/launchdarkly-labs/js-core/commit/22fb0b230412e97e930cb6c7414e98beb37f587a))
* Populate OpenFeature flag metadata from the evaluation reason ([#1869](https://github.com/launchdarkly-labs/js-core/issues/1869)) ([d5bdaeb](https://github.com/launchdarkly-labs/js-core/commit/d5bdaebb515a5357cbdc6da52b5b911bc4af7351))
* Support zero and indefinite initialization waiting ([#2024](https://github.com/launchdarkly-labs/js-core/issues/2024)) ([8bfd257](https://github.com/launchdarkly-labs/js-core/commit/8bfd257bd561109faa5be0c1a6b6a7620bb2c66f))


### Bug Fixes

* Map LaunchDarkly evaluation reasons to OpenFeature reasons ([#1887](https://github.com/launchdarkly-labs/js-core/issues/1887)) ([70291f4](https://github.com/launchdarkly-labs/js-core/commit/70291f4862384f18ef4e9bf11045c7f4df73a116))
* **openfeature-node-server:** identify floor for node server sdk peer dep ([#1787](https://github.com/launchdarkly-labs/js-core/issues/1787)) ([d42203a](https://github.com/launchdarkly-labs/js-core/commit/d42203a9d32c1f0d8365a09471bf33712580719c))
* **openfeature-node-server:** updating public README and CHANGELOG ([#1782](https://github.com/launchdarkly-labs/js-core/issues/1782)) ([e55c1db](https://github.com/launchdarkly-labs/js-core/commit/e55c1db37857bae2fd6c556f31a0e04cb9988494))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/openfeature-js-server-common bumped from 2.2.3 to 3.0.0
  * devDependencies
    * @launchdarkly/node-server-sdk bumped from 9.16.4 to 9.17.0
  * peerDependencies
    * @launchdarkly/node-server-sdk bumped from ^9.0.0 to ^9.17.0
</details>

<details><summary>react-native-client-sdk: 10.24.0</summary>

## [10.24.0](https://github.com/launchdarkly-labs/js-core/compare/react-native-client-sdk-v10.23.4...react-native-client-sdk-v10.24.0) (2026-11-10)


### Features

* Add eventSource factory and usePost options to the client-side SDK common ([#2032](https://github.com/launchdarkly-labs/js-core/issues/2032)) ([f514d5b](https://github.com/launchdarkly-labs/js-core/commit/f514d5bc1fd7c995ed63e7eae3ff4624889ea941))
* Add experimental FDv2 support for React Native. ([#1243](https://github.com/launchdarkly-labs/js-core/issues/1243)) ([7ed2c08](https://github.com/launchdarkly-labs/js-core/commit/7ed2c085cd35d35ffd6f48becb5a60f03b07ad1c))
* conform FDv1 streaming and polling data sources to the RETRY spec ([#2098](https://github.com/launchdarkly-labs/js-core/issues/2098)) ([0d5e30d](https://github.com/launchdarkly-labs/js-core/commit/0d5e30d1d9c904c1b34020075d397b06523a5c3a))
* conform the React Native SDK streaming data source to the RETRY spec ([#2103](https://github.com/launchdarkly-labs/js-core/issues/2103)) ([8cc60e5](https://github.com/launchdarkly-labs/js-core/commit/8cc60e5acec595347026d54fabe35c6d82a89f33))
* Prepare FDv2 EAP for browser and React Native SDKs ([#1419](https://github.com/launchdarkly-labs/js-core/issues/1419)) ([6ee9c51](https://github.com/launchdarkly-labs/js-core/commit/6ee9c515fe9aaf999fd7f0eb722d6df9a2d208d8))
* **react-native:** adding debug override plugin support ([#1410](https://github.com/launchdarkly-labs/js-core/issues/1410)) ([99a96d2](https://github.com/launchdarkly-labs/js-core/commit/99a96d2d73a98264e551074f66fb5d10155042c6))
* **react-native:** no storage fallback to in-memory map ([#1281](https://github.com/launchdarkly-labs/js-core/issues/1281)) ([cc86eab](https://github.com/launchdarkly-labs/js-core/commit/cc86eabe18fd524472c7cf36847c0d757aecc6d1))
* wire fdv1-fallback capability into node-client, browser, and react-native contract-test entities ([#1858](https://github.com/launchdarkly-labs/js-core/issues/1858)) ([462c950](https://github.com/launchdarkly-labs/js-core/commit/462c95098d2143802939cd010cfacd39e26a1c22))


### Bug Fixes

* Honor urlBuilder on React Native EventSource reconnect ([#1420](https://github.com/launchdarkly-labs/js-core/issues/1420)) ([93bd3f8](https://github.com/launchdarkly-labs/js-core/commit/93bd3f84d1c824fe1bea94f7760c586349c3dc3e))
* **react-native:** `package.json` should declare esm format ([#1322](https://github.com/launchdarkly-labs/js-core/issues/1322)) ([149ae73](https://github.com/launchdarkly-labs/js-core/commit/149ae73c623cf7ccac6f7d7346059a80e8044280))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))
* **sdk-client:** `executeAfterTrack` ordering ([58e063b](https://github.com/launchdarkly-labs/js-core/commit/58e063bad4651e25beea644425bea23a20f4870f))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-client-sdk-common bumped from 1.35.2 to 1.36.0
</details>

<details><summary>react-sdk: 4.3.0</summary>

## [4.3.0](https://github.com/launchdarkly-labs/js-core/compare/react-sdk-v4.2.2...react-sdk-v4.3.0) (2026-11-10)


### Features

* add fetch-based eventsource entry point to the react sdk ([#2150](https://github.com/launchdarkly-labs/js-core/issues/2150)) ([a4f23b3](https://github.com/launchdarkly-labs/js-core/commit/a4f23b340f81cb768ac2279523c7f2859735f2ec))
* adding isomorphic provider to bridge client and server ([#1218](https://github.com/launchdarkly-labs/js-core/issues/1218)) ([d766f39](https://github.com/launchdarkly-labs/js-core/commit/d766f39c0d178cc66c80644c3cecddb6e7131c93))
* **js-client-sdk:** add ability to customize storage impl ([#1404](https://github.com/launchdarkly-labs/js-core/issues/1404)) ([77864cb](https://github.com/launchdarkly-labs/js-core/commit/77864cb04f737c8aab4476422a2a2422c7be978c))
* release-react-sdk-v4 ([#1238](https://github.com/launchdarkly-labs/js-core/issues/1238)) ([a0eb24d](https://github.com/launchdarkly-labs/js-core/commit/a0eb24d05e34237c852d039ead46f33e31a95c4c))


### Bug Fixes

* Bump vercel SDK to latest  ([#1832](https://github.com/launchdarkly-labs/js-core/issues/1832)) ([b0167a2](https://github.com/launchdarkly-labs/js-core/commit/b0167a20b3ac599a231946b03efd9f790cf27d39))
* **deps:** update dependency next to v16.2.11 [security] ([#1822](https://github.com/launchdarkly-labs/js-core/issues/1822)) ([19454cd](https://github.com/launchdarkly-labs/js-core/commit/19454cd5a2b9fc3729f05ab40f5091ba070a16b0))
* **deps:** update dependency next to v16.2.3 [security] ([#1263](https://github.com/launchdarkly-labs/js-core/issues/1263)) ([10f582a](https://github.com/launchdarkly-labs/js-core/commit/10f582a460342f6352735b1cd3f93af1f57ba303))
* **deps:** update dependency next to v16.2.6 [security] ([#1374](https://github.com/launchdarkly-labs/js-core/issues/1374)) ([24487f4](https://github.com/launchdarkly-labs/js-core/commit/24487f49d2f0b87d50af18d807b98a3dc5b11b8f))
* **react-sdk:** `basicLogger` was not re-exported causing compile time errors ([#1843](https://github.com/launchdarkly-labs/js-core/issues/1843)) ([459c891](https://github.com/launchdarkly-labs/js-core/commit/459c891a718ad52d2f34a7b6b9b53e3c858459cc))
* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))
* **sdk-client:** `executeAfterTrack` ordering ([58e063b](https://github.com/launchdarkly-labs/js-core/commit/58e063bad4651e25beea644425bea23a20f4870f))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-client-sdk bumped from 4.14.2 to 4.15.0
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
</details>

<details><summary>server-sdk-ai: 3.0.0</summary>

## [3.0.0](https://github.com/launchdarkly-labs/js-core/compare/server-sdk-ai-v2.0.20...server-sdk-ai-v3.0.0) (2026-11-10)


###   BREAKING CHANGES

* Make AgentGraph traversal topological ([#1830](https://github.com/launchdarkly-labs/js-core/issues/1830))
* Remove bedrock-specific tracker method ([#1385](https://github.com/launchdarkly-labs/js-core/issues/1385))
* Remove `LDAIClient.agent`  use `LDAIClient.agentConfig` instead
* Remove `LDAIClient.agents`  use `LDAIClient.agentConfigs` instead
* Remove `LDAIClient.createChat`  use `LDAIClient.createModel` instead
* Remove `LDAIClient.initChat`  use `LDAIClient.createModel` instead
* Remove `ChatResponse` type and the `api/chat` module  use `RunnerResult` from `api/model` instead
* Change `Judge.evaluateMessages` parameter type from `ChatResponse` to `RunnerResult` (method retained per AI SDK spec Requirement 1.1.3)
* Remove `evaluationMetricKeys` (plural) field from `LDAIJudgeConfig` and `LDAIJudgeConfigDefault`  use `evaluationMetricKey` (singular) instead
* Remove `LDAIConfigTracker.trackOpenAIMetrics`  use `tracker.trackMetricsOf(getAIMetricsFromResponse, fn)` from `@launchdarkly/server-sdk-ai-openai` instead
* Remove `LDAIConfigTracker.trackVercelAISDKGenerateTextMetrics`  use `tracker.trackMetricsOf(getAIMetricsFromResponse, fn)` from `@launchdarkly/server-sdk-ai-vercel` instead
* Remove `createOpenAiUsage` helper  use `getAIMetricsFromResponse` from `@launchdarkly/server-sdk-ai-openai` instead
* Remove `createVercelAISDKTokenUsage` helper  use `getAIMetricsFromResponse`  from `@launchdarkly/server-sdk-ai-vercel` instead
* Remove `LDAIClient.config`  use `LDAIClient.completionConfig` instead
* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366))
* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364))
* Use LDAIGraphMetricSummary for graph metric summary ([#1362](https://github.com/launchdarkly-labs/js-core/issues/1362))
* Flatten JudgeResponse and EvalScore into new LDJudgeResult ([#1284](https://github.com/launchdarkly-labs/js-core/issues/1284))
* Add per-execution runId, at-most-once tracking, and cross-process tracker resumption ([#1270](https://github.com/launchdarkly-labs/js-core/issues/1270))

### Features

* add Evaluator class for judge orchestration ([#1331](https://github.com/launchdarkly-labs/js-core/issues/1331)) ([54faa69](https://github.com/launchdarkly-labs/js-core/commit/54faa69aa28333f92d943de79307611fc05e2cbe))
* add ManagedAgent with evaluations support ([#1334](https://github.com/launchdarkly-labs/js-core/issues/1334)) ([7f09c46](https://github.com/launchdarkly-labs/js-core/commit/7f09c46cdec808ce9ebeb6487e6a2fa4fc817cbc))
* add ManagedGraphResult, GraphMetricSummary, and ManagedAgentGraph ([#1335](https://github.com/launchdarkly-labs/js-core/issues/1335)) ([09fa1db](https://github.com/launchdarkly-labs/js-core/commit/09fa1dbb134ea43ab8664b5e7903eb85883a0ac2))
* Add per-execution runId, at-most-once tracking, and cross-process tracker resumption ([#1270](https://github.com/launchdarkly-labs/js-core/issues/1270)) ([fc25ab7](https://github.com/launchdarkly-labs/js-core/commit/fc25ab7bd9577dbd1ea9826547793366a4e6814b))
* add region to model type ([#1423](https://github.com/launchdarkly-labs/js-core/issues/1423)) ([7db5df5](https://github.com/launchdarkly-labs/js-core/commit/7db5df587812e8d9b0140d2b389f16d341d55cd7))
* Add root-level tools map with customParameters to AI Config types ([#1295](https://github.com/launchdarkly-labs/js-core/issues/1295)) ([487182b](https://github.com/launchdarkly-labs/js-core/commit/487182b6a078b2aaf3868706d8f3c2709e8cc11c))
* Change `Judge.evaluateMessages` parameter type from `ChatResponse` to `RunnerResult` (method retained per AI SDK spec Requirement 1.1.3) ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Flatten JudgeResponse and EvalScore into new LDJudgeResult ([#1284](https://github.com/launchdarkly-labs/js-core/issues/1284)) ([aba1221](https://github.com/launchdarkly-labs/js-core/commit/aba1221d3b3d9f4eff44d805ed1c5e9f4d088e4a))
* Implement agent graph definitions ([#1282](https://github.com/launchdarkly-labs/js-core/issues/1282)) ([e7d08e5](https://github.com/launchdarkly-labs/js-core/commit/e7d08e5e3b84020e543fd54d40a8530ddc514f20))
* implements _template methods for fetching non-interpolated config ([#1774](https://github.com/launchdarkly-labs/js-core/issues/1774)) ([d808ca8](https://github.com/launchdarkly-labs/js-core/commit/d808ca8c0bc1abb1061de1e2ee989c929ac1cc53))
* introduce ManagedResult, RunnerResult, and LDAIMetricSummary ([#1332](https://github.com/launchdarkly-labs/js-core/issues/1332)) ([5040122](https://github.com/launchdarkly-labs/js-core/commit/5040122a5c6de88691820f02528550b983a14e58))
* Remove `ChatResponse` type and the `api/chat` module  use `RunnerResult` from `api/model` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `createOpenAiUsage` helper  use `getAIMetricsFromResponse` from `@launchdarkly/server-sdk-ai-openai` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `createVercelAISDKTokenUsage` helper  use `getAIMetricsFromResponse`  from `@launchdarkly/server-sdk-ai-vercel` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `evaluationMetricKeys` (plural) field from `LDAIJudgeConfig` and `LDAIJudgeConfigDefault`  use `evaluationMetricKey` (singular) instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIClient.agent`  use `LDAIClient.agentConfig` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIClient.agents`  use `LDAIClient.agentConfigs` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIClient.config`  use `LDAIClient.completionConfig` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIClient.createChat`  use `LDAIClient.createModel` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIClient.initChat`  use `LDAIClient.createModel` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIConfigTracker.trackOpenAIMetrics`  use `tracker.trackMetricsOf(getAIMetricsFromResponse, fn)` from `@launchdarkly/server-sdk-ai-openai` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove `LDAIConfigTracker.trackVercelAISDKGenerateTextMetrics`  use `tracker.trackMetricsOf(getAIMetricsFromResponse, fn)` from `@launchdarkly/server-sdk-ai-vercel` instead ([86951b0](https://github.com/launchdarkly-labs/js-core/commit/86951b0f66eed3f374d06c40e858dca04a837fda))
* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363)) ([ad66314](https://github.com/launchdarkly-labs/js-core/commit/ad66314e403b83976987c54da9c6c70308c25078))
* Remove bedrock-specific tracker method ([#1385](https://github.com/launchdarkly-labs/js-core/issues/1385)) ([f7dbee8](https://github.com/launchdarkly-labs/js-core/commit/f7dbee806a15e8b9d5a6b7b49a461e16e5e757fe))
* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366)) ([ff932b7](https://github.com/launchdarkly-labs/js-core/commit/ff932b74c10307519dc9f913a4330a5b7d79438d))
* Replace OpenAIProvider with Runner protocol implementation (AIC-2388) ([#1337](https://github.com/launchdarkly-labs/js-core/issues/1337)) ([e32a955](https://github.com/launchdarkly-labs/js-core/commit/e32a955c583db1bc382e2e0f3f459d459bc35984))
* **server-ai:** stamp modelKey and modelVersion on AI usage events (AIC-2858) ([#1794](https://github.com/launchdarkly-labs/js-core/issues/1794)) ([a91a1e7](https://github.com/launchdarkly-labs/js-core/commit/a91a1e7927262dcdbe1098b33095f529c48f7e8c))
* simplify evaluation schema to flat score/reasoning shape ([#1286](https://github.com/launchdarkly-labs/js-core/issues/1286)) ([c132e9f](https://github.com/launchdarkly-labs/js-core/commit/c132e9f44c8113cc5b795edfa6330f26c38081a6))
* Support fall back to model.parameters.tools when root tools absent ([#1330](https://github.com/launchdarkly-labs/js-core/issues/1330)) ([2c65c61](https://github.com/launchdarkly-labs/js-core/commit/2c65c61d1fd4df9b13d1e9b2f3bd055d4a77ec22))


### Bug Fixes

* Add support for graph metric tracking ([#1269](https://github.com/launchdarkly-labs/js-core/issues/1269)) ([034a89d](https://github.com/launchdarkly-labs/js-core/commit/034a89d3a8d8b718aecb459190f94f6e2ab14a3d))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364)) ([c90034b](https://github.com/launchdarkly-labs/js-core/commit/c90034b58a3b75d92269e7c485f38f1266208f08))
* Make AgentGraph traversal topological ([#1830](https://github.com/launchdarkly-labs/js-core/issues/1830)) ([d240b07](https://github.com/launchdarkly-labs/js-core/commit/d240b07bd584f282b8588bfe111c1361e09d2328))
* Make judge runners non-multi-turn ([#1383](https://github.com/launchdarkly-labs/js-core/issues/1383)) ([3d8f488](https://github.com/launchdarkly-labs/js-core/commit/3d8f488354a5ed590859c7fe96429a2ab9f79c01))
* Move ManagedAgentGraph alongside other managed types ([#1384](https://github.com/launchdarkly-labs/js-core/issues/1384)) ([22dd76d](https://github.com/launchdarkly-labs/js-core/commit/22dd76d61a830d7ad37ae0136b59d1971973b424))
* Remove pre-release caution note from server-ai README ([#1387](https://github.com/launchdarkly-labs/js-core/issues/1387)) ([0bafcbf](https://github.com/launchdarkly-labs/js-core/commit/0bafcbfc22d5c39c3664d38bdb47183824a068e5))
* **server-ai:** unpin peer depedency reference ([#1788](https://github.com/launchdarkly-labs/js-core/issues/1788)) ([dbc2bd5](https://github.com/launchdarkly-labs/js-core/commit/dbc2bd5d8af9bcd7e4ffdc3e439cb6e4c7985a38))
* Use LDAIGraphMetricSummary for graph metric summary ([#1362](https://github.com/launchdarkly-labs/js-core/issues/1362)) ([76a4bf2](https://github.com/launchdarkly-labs/js-core/commit/76a4bf278999c81b27ce1aa29a3c1cb42e113fbc))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
  * peerDependencies
    * @launchdarkly/js-server-sdk-common bumped from ^2.0.0 to ^2.27.0
</details>

<details><summary>server-sdk-ai-langchain: 0.9.0</summary>

## [0.9.0](https://github.com/launchdarkly-labs/js-core/compare/server-sdk-ai-langchain-v0.8.31...server-sdk-ai-langchain-v0.9.0) (2026-11-10)


###   BREAKING CHANGES

* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366))
* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364))

### Features

* Bump to LangChain 1.0 and drop community package requirement ([#1311](https://github.com/launchdarkly-labs/js-core/issues/1311)) ([f5a1c29](https://github.com/launchdarkly-labs/js-core/commit/f5a1c295e51ff07e9003109a873709ea14dad343))
* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363)) ([ad66314](https://github.com/launchdarkly-labs/js-core/commit/ad66314e403b83976987c54da9c6c70308c25078))
* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366)) ([ff932b7](https://github.com/launchdarkly-labs/js-core/commit/ff932b74c10307519dc9f913a4330a5b7d79438d))
* Replace LangChainProvider with Runner protocol implementation (AIC-2388) ([#1338](https://github.com/launchdarkly-labs/js-core/issues/1338)) ([113a0d2](https://github.com/launchdarkly-labs/js-core/commit/113a0d289ce764a3301140b2b14123ce5da9b42e))
* Support conversation history directly in AI Provider model runners ([#1371](https://github.com/launchdarkly-labs/js-core/issues/1371)) ([b246631](https://github.com/launchdarkly-labs/js-core/commit/b246631bfcaf7155dec52a1580cf4ffb329ebfaa))


### Bug Fixes

* **AIC-3497:** allow server-sdk-ai 2.x as a peer of the AI provider packages ([#2090](https://github.com/launchdarkly-labs/js-core/issues/2090)) ([aece398](https://github.com/launchdarkly-labs/js-core/commit/aece398d3fab8688bab99540f623b9c4b7f37935))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364)) ([c90034b](https://github.com/launchdarkly-labs/js-core/commit/c90034b58a3b75d92269e7c485f38f1266208f08))
* Make judge runners non-multi-turn ([#1383](https://github.com/launchdarkly-labs/js-core/issues/1383)) ([3d8f488](https://github.com/launchdarkly-labs/js-core/commit/3d8f488354a5ed590859c7fe96429a2ab9f79c01))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/server-sdk-ai bumped from ^2.0.20 to ^3.0.0
  * peerDependencies
    * @launchdarkly/server-sdk-ai bumped from ^1.1.1 || ^2.0.0 to ^3.0.0
</details>

<details><summary>server-sdk-ai-openai: 0.8.0</summary>

## [0.8.0](https://github.com/launchdarkly-labs/js-core/compare/server-sdk-ai-openai-v0.7.31...server-sdk-ai-openai-v0.8.0) (2026-11-10)


###   BREAKING CHANGES

* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366))
* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364))

### Features

* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363)) ([ad66314](https://github.com/launchdarkly-labs/js-core/commit/ad66314e403b83976987c54da9c6c70308c25078))
* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366)) ([ff932b7](https://github.com/launchdarkly-labs/js-core/commit/ff932b74c10307519dc9f913a4330a5b7d79438d))
* Replace OpenAIProvider with Runner protocol implementation (AIC-2388) ([#1337](https://github.com/launchdarkly-labs/js-core/issues/1337)) ([e32a955](https://github.com/launchdarkly-labs/js-core/commit/e32a955c583db1bc382e2e0f3f459d459bc35984))
* Support conversation history directly in AI Provider model runners ([#1371](https://github.com/launchdarkly-labs/js-core/issues/1371)) ([b246631](https://github.com/launchdarkly-labs/js-core/commit/b246631bfcaf7155dec52a1580cf4ffb329ebfaa))


### Bug Fixes

* **AIC-3497:** allow server-sdk-ai 2.x as a peer of the AI provider packages ([#2090](https://github.com/launchdarkly-labs/js-core/issues/2090)) ([aece398](https://github.com/launchdarkly-labs/js-core/commit/aece398d3fab8688bab99540f623b9c4b7f37935))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364)) ([c90034b](https://github.com/launchdarkly-labs/js-core/commit/c90034b58a3b75d92269e7c485f38f1266208f08))
* Make judge runners non-multi-turn ([#1383](https://github.com/launchdarkly-labs/js-core/issues/1383)) ([3d8f488](https://github.com/launchdarkly-labs/js-core/commit/3d8f488354a5ed590859c7fe96429a2ab9f79c01))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
    * @launchdarkly/server-sdk-ai bumped from ^2.0.20 to ^3.0.0
  * peerDependencies
    * @launchdarkly/server-sdk-ai bumped from ^1.1.1 || ^2.0.0 to ^3.0.0
</details>

<details><summary>server-sdk-ai-vercel: 0.8.0</summary>

## [0.8.0](https://github.com/launchdarkly-labs/js-core/compare/server-sdk-ai-vercel-v0.7.31...server-sdk-ai-vercel-v0.8.0) (2026-11-10)


###   BREAKING CHANGES

* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366))
* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364))

### Features

* Remove AIProvider deprecated methods and create*/init* aliases (AIC-2388) ([#1363](https://github.com/launchdarkly-labs/js-core/issues/1363)) ([ad66314](https://github.com/launchdarkly-labs/js-core/commit/ad66314e403b83976987c54da9c6c70308c25078))
* Rename LDAIMetrics.usage and LDAIGraphMetrics.usage to .tokens ([#1366](https://github.com/launchdarkly-labs/js-core/issues/1366)) ([ff932b7](https://github.com/launchdarkly-labs/js-core/commit/ff932b74c10307519dc9f913a4330a5b7d79438d))
* replace VercelProvider with Runner protocol implementation (AIC-2388) ([#1339](https://github.com/launchdarkly-labs/js-core/issues/1339)) ([d5a62de](https://github.com/launchdarkly-labs/js-core/commit/d5a62def46b683d4c2e7de0c16ee7fc82e40b66a))
* Support conversation history directly in AI Provider model runners ([#1371](https://github.com/launchdarkly-labs/js-core/issues/1371)) ([b246631](https://github.com/launchdarkly-labs/js-core/commit/b246631bfcaf7155dec52a1580cf4ffb329ebfaa))


### Bug Fixes

* add zod devDependency to Vercel provider (peer dep of ai v5) ([aab6226](https://github.com/launchdarkly-labs/js-core/commit/aab62262800dfc0b9d4c3c6f9ee71a3f63519959))
* **AIC-3497:** allow server-sdk-ai 2.x as a peer of the AI provider packages ([#2090](https://github.com/launchdarkly-labs/js-core/issues/2090)) ([aece398](https://github.com/launchdarkly-labs/js-core/commit/aece398d3fab8688bab99540f623b9c4b7f37935))
* Build judge input as string and strip legacy judge config messages ([#1364](https://github.com/launchdarkly-labs/js-core/issues/1364)) ([c90034b](https://github.com/launchdarkly-labs/js-core/commit/c90034b58a3b75d92269e7c485f38f1266208f08))
* Make judge runners non-multi-turn ([#1383](https://github.com/launchdarkly-labs/js-core/issues/1383)) ([3d8f488](https://github.com/launchdarkly-labs/js-core/commit/3d8f488354a5ed590859c7fe96429a2ab9f79c01))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @launchdarkly/server-sdk-ai bumped from ^2.0.20 to ^3.0.0
  * peerDependencies
    * @launchdarkly/server-sdk-ai bumped from ^1.1.1 || ^2.0.0 to ^3.0.0
</details>

<details><summary>shopify-oxygen-sdk: 0.3.0</summary>

## [0.3.0](https://github.com/launchdarkly-labs/js-core/compare/shopify-oxygen-sdk-v0.2.6...shopify-oxygen-sdk-v0.3.0) (2026-11-10)


### Features

* Add optional streaming members to the platform fetch types ([#2092](https://github.com/launchdarkly-labs/js-core/issues/2092)) ([4137805](https://github.com/launchdarkly-labs/js-core/commit/4137805723e14f1f21c07b45039c4eeda9889519))


### Bug Fixes

* enabling eslint `ban-types` rule and fixed string typing ([#1313](https://github.com/launchdarkly-labs/js-core/issues/1313)) ([f6d907f](https://github.com/launchdarkly-labs/js-core/commit/f6d907f1a65abd0b41827f3c827e6dad896b16b1))
* explicit return types and TS6 source compatibility fixes ([#1418](https://github.com/launchdarkly-labs/js-core/issues/1418)) ([9c131a2](https://github.com/launchdarkly-labs/js-core/commit/9c131a2e731c97a7fd4cf7ec1fe11efbbf49d6fb))
* **oxygen-sdk:** document event sending and align event sending logic with other edge sdks ([#1844](https://github.com/launchdarkly-labs/js-core/issues/1844)) ([86ed0ad](https://github.com/launchdarkly-labs/js-core/commit/86ed0adff8209d49725d6d10acb9f6b03c02239c))
* server sdk could send user agent headers under a different header name ([#1860](https://github.com/launchdarkly-labs/js-core/issues/1860)) ([669662a](https://github.com/launchdarkly-labs/js-core/commit/669662a304c10bcb2b683e0c7ea990f43679916b))
* **shopify:** standardizing the pre-release banner ([#1268](https://github.com/launchdarkly-labs/js-core/issues/1268)) ([82adddb](https://github.com/launchdarkly-labs/js-core/commit/82adddb56bcd752954a0107ff3983cf57d1bdb26))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-server-sdk-common bumped from 2.26.4 to 2.27.0
</details>

<details><summary>vercel-server-sdk: 1.3.75</summary>

## [1.3.75](https://github.com/launchdarkly-labs/js-core/compare/vercel-server-sdk-v1.3.74...vercel-server-sdk-v1.3.75) (2026-11-10)


### Bug Fixes

* Bump vercel SDK to latest  ([#1832](https://github.com/launchdarkly-labs/js-core/issues/1832)) ([b0167a2](https://github.com/launchdarkly-labs/js-core/commit/b0167a20b3ac599a231946b03efd9f790cf27d39))
* **sdk-server-common:** use subpath import for `semver` module ([#1885](https://github.com/launchdarkly-labs/js-core/issues/1885)) ([2de6c8c](https://github.com/launchdarkly-labs/js-core/commit/2de6c8cc39e6b7a4e4092af0731b2de124d56b94))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-server-sdk-common-edge bumped from 2.6.47 to 2.6.48
</details>

<details><summary>vue-client-sdk: 4.0.0</summary>

## [4.0.0](https://github.com/launchdarkly-labs/js-core/compare/vue-client-sdk-v3.0.11...vue-client-sdk-v4.0.0) (2026-11-10)


###   BREAKING CHANGES

* Implicit anonymous-user fallback removed; context is now required in LDVuePluginOptions and createLDProvider.

### Features

* Bootstrap support to eliminate initialization waterfall ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* createClient for programmatic client creation (BYO client pattern) ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* LDVueClient type extending base LDClient with Vue lifecycle helpers ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Multi-environment support via createLDVueInstanceKey ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Provider component API: createLDProvider, createLDProviderWithClient ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Provider slots for initialization states (default, initializing, failed) ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Reactive flag keys (MaybeRefOrGetter&lt;string&gt;) on all variation composables ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* startOptions for controlling initialization timeout ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Typed variation composables: useBoolVariation, useStringVariation, ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* useInitializationStatus replaces useLDReady with richer status object ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Variation detail composables for each type (useBoolVariationDetail, etc.) ([d3b97a8](https://github.com/launchdarkly-labs/js-core/commit/d3b97a8c3c8e00774b6edcba07f0d6542233a4a2))
* Wire packages/sdk/vue into release-please as an active prerelease ([#1850](https://github.com/launchdarkly-labs/js-core/issues/1850)) ([4f5ef29](https://github.com/launchdarkly-labs/js-core/commit/4f5ef292f873103db10e06df338c90ca5b791a7e))


### Bug Fixes

* Resolve types under node16/nodenext module resolution ([#2115](https://github.com/launchdarkly-labs/js-core/issues/2115)) ([ca1613c](https://github.com/launchdarkly-labs/js-core/commit/ca1613c20130b9308bafb8c98e0843d8d92fee01))
* **vue-sdk:** re-export `LDPlugin` from base impl ([#1897](https://github.com/launchdarkly-labs/js-core/issues/1897)) ([e21f484](https://github.com/launchdarkly-labs/js-core/commit/e21f4842f2f1f5e3223e35e26cb82bb171681f2f))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @launchdarkly/js-client-sdk bumped from 4.14.2 to 4.15.0
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).
# Changelog

## [18.0.0](https://github.com/npm/cacache/compare/v17.1.4...v18.0.0) (2023-08-14)

### ⚠️ BREAKING CHANGES

* support for node 14 has been removed

### Bug Fixes

* [`bdff8ca`](https://github.com/npm/cacache/commit/bdff8cab5bb6446599fb25b9a9f408d157db81be) [#219](https://github.com/npm/cacache/pull/219) use lru-cache named export (@lukekarrys)
* [`0db9bcb`](https://github.com/npm/cacache/commit/0db9bcbb58bce80384de2c0d384a5f1311fa5428) [#219](https://github.com/npm/cacache/pull/219) drop node14 support (@lukekarrys)

### Dependencies

* [`0850b54`](https://github.com/npm/cacache/commit/0850b5437e9e3b099575f629d6a69d6ab47eefde) [#219](https://github.com/npm/cacache/pull/219) bump lru-cache from 7.18.3 to 10.0.1

## [17.1.4](https://github.com/npm/cacache/compare/v17.1.3...v17.1.4) (2023-08-14)

### Dependencies

* [`4b82a42`](https://github.com/npm/cacache/commit/4b82a428bc6177732aec71cc33e414d09d59adcb) [#217](https://github.com/npm/cacache/pull/217) bump minipass from 5.0.0 to 7.0.3

## [17.1.3](https://github.com/npm/cacache/compare/v17.1.2...v17.1.3) (2023-05-18)

### Bug Fixes

* [`a0a5e58`](https://github.com/npm/cacache/commit/a0a5e581fb0405c2e4cbc9b3b8eb745eb8143a86) [#209](https://github.com/npm/cacache/pull/209) normalize win32 paths to use on glob expressions (#209) (@supita)

## [17.1.2](https://github.com/npm/cacache/compare/v17.1.1...v17.1.2) (2023-05-16)

### Bug Fixes

* [`bd846d0`](https://github.com/npm/cacache/commit/bd846d02205d21aa199798351cb427bcae53ea4a) [#206](https://github.com/npm/cacache/pull/206) catch eexists in moveOperations promise (#206) (@wraithgar)

## [17.1.1](https://github.com/npm/cacache/compare/v17.1.0...v17.1.1) (2023-05-16)

### Bug Fixes

* [`988d77a`](https://github.com/npm/cacache/commit/988d77aa7f71917f16d9f27210544029c15c8f98) [#203](https://github.com/npm/cacache/pull/203) deduplicate move operations (#203) (@wraithgar)

## [17.1.0](https://github.com/npm/cacache/compare/v17.0.7...v17.1.0) (2023-05-02)

### Features

* [`2e83cfc`](https://github.com/npm/cacache/commit/2e83cfc4013f37359ea7f49d23bc659b76f9f356) [#200](https://github.com/npm/cacache/pull/200) write: accept multiple integrity algorithms (#200) (@wraithgar)

### Bug Fixes

* [`62b2d8d`](https://github.com/npm/cacache/commit/62b2d8d06ae0a762d74a12bac17fc50a42731ee3) [#199](https://github.com/npm/cacache/pull/199) don't clobber time when verifying cache (#199) (@wraithgar)
* [`e227c50`](https://github.com/npm/cacache/commit/e227c5006a4cd9648ab684f1ea13ce19f9508a23) [#197](https://github.com/npm/cacache/pull/197) verify: allow for entries with multiple hashes (#197) (@wraithgar)

### Documentation

* [`1b3774e`](https://github.com/npm/cacache/commit/1b3774e5c6be2608ac8d9513f9a13307015f457a) [#201](https://github.com/npm/cacache/pull/201) update readme links (#201) (@wraithgar)

## [17.0.7](https://github.com/npm/cacache/compare/v17.0.6...v17.0.7) (2023-05-01)

### Bug Fixes

* [`265e4ae`](https://github.com/npm/cacache/commit/265e4aeb9b6cbfcd07c75059508b7617b5169d73) [#195](https://github.com/npm/cacache/pull/195) Trust the filesystem to move files (@wraithgar)

### Dependencies

* [`11fc035`](https://github.com/npm/cacache/commit/11fc0353cb748abeee76ecbce11b6c18d351fb19) [#195](https://github.com/npm/cacache/pull/195) remove promise-inflight

## [17.0.6](https://github.com/npm/cacache/compare/v17.0.5...v17.0.6) (2023-04-27)

### Dependencies

* [`46b8457`](https://github.com/npm/cacache/commit/46b845730cdba25e8d2da9a58a60c47ae7648863) [#191](https://github.com/npm/cacache/pull/191) bump glob from 9.3.5 to 10.2.2 (#191)
* [`5e9e825`](https://github.com/npm/cacache/commit/5e9e8251a1e83124113cc7e9edad5ea71dd789e7) [#182](https://github.com/npm/cacache/pull/182) bump minipass from 4.2.7 to 5.0.0 (#182)

## [17.0.5](https://github.com/npm/cacache/compare/v17.0.4...v17.0.5) (2023-03-21)

### Dependencies

* [`a6dd005`](https://github.com/npm/cacache/commit/a6dd005da900de139f575caab660046e88974e0a) [#176](https://github.com/npm/cacache/pull/176) bump glob from 8.1.0 to 9.3.1 (#176)

## [17.0.4](https://github.com/npm/cacache/compare/v17.0.3...v17.0.4) (2022-12-14)

### Dependencies

* [`fe71fab`](https://github.com/npm/cacache/commit/fe71fabaacadc8a06b8142141a1d0e63fbed537c) [#159](https://github.com/npm/cacache/pull/159) bump fs-minipass from 2.1.0 to 3.0.0

## [17.0.3](https://github.com/npm/cacache/compare/v17.0.2...v17.0.3) (2022-12-07)

### Dependencies

* [`0dc98f7`](https://github.com/npm/cacache/commit/0dc98f7ca0940ea010ef3ba5257887e36083b3a2) [#156](https://github.com/npm/cacache/pull/156) bump minipass from 3.3.6 to 4.0.0

## [17.0.2](https://github.com/npm/cacache/compare/v17.0.1...v17.0.2) (2022-11-04)

### Bug Fixes

* [`4a7382f`](https://github.com/npm/cacache/commit/4a7382f5e6c72c59587d45167346c1b6e81a3cde) [#152](https://github.com/npm/cacache/pull/152) replace @npmcli/move-file with @npmcli/fs (@lukekarrys)

## [17.0.1](https://github.com/npm/cacache/compare/v17.0.0...v17.0.1) (2022-10-17)

### Dependencies

* [`d3515de`](https://github.com/npm/cacache/commit/d3515dec8ee6305d564389f5e52363637666f718) [#146](https://github.com/npm/cacache/pull/146) bump unique-filename from 2.0.1 to 3.0.0
* [`e57ebd9`](https://github.com/npm/cacache/commit/e57ebd9edcd4ac93df7ccbe1eee66a7a2c41c0a7) [#143](https://github.com/npm/cacache/pull/143) bump ssri from 9.0.1 to 10.0.0
* [`9dd537a`](https://github.com/npm/cacache/commit/9dd537a5ab53f5f84e16ff9e69ebd9f28e3f8c54) [#144](https://github.com/npm/cacache/pull/144) bump @npmcli/move-file from 2.0.1 to 3.0.0

## [17.0.0](https://github.com/npm/cacache/compare/v16.1.3...v17.0.0) (2022-10-13)

### ⚠️ BREAKING CHANGES

* this module no longer attempts to change file ownership automatically
* this package is now async only, all synchronous methods have been removed
* `cacache` is now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

### Features

* [`479b135`](https://github.com/npm/cacache/commit/479b1352a72ea3a6bc403545e269d3add985c6ee) [#141](https://github.com/npm/cacache/pull/141) do not alter file ownership (#141) (@nlf)
* [`f57bb4d`](https://github.com/npm/cacache/commit/f57bb4d3ec6147843fac673c6578c3d231f336df) [#140](https://github.com/npm/cacache/pull/140) remove sync methods (#140) (@nlf)
* [`cfebcde`](https://github.com/npm/cacache/commit/cfebcdea59e3fc1ff33fbe4b3fa6f05aa765326f) [#133](https://github.com/npm/cacache/pull/133) postinstall for dependabot template-oss PR (@lukekarrys)

## [16.1.3](https://github.com/npm/cacache/compare/v16.1.2...v16.1.3) (2022-08-23)


### Dependencies

* bump unique-filename from 1.1.1 to 2.0.0 ([#123](https://github.com/npm/cacache/issues/123)) ([6235554](https://github.com/npm/cacache/commit/6235554e46d19a9d9af25f87aa797fb85efc9519))

## [16.1.2](https://github.com/npm/cacache/compare/v16.1.1...v16.1.2) (2022-08-15)


### Bug Fixes

* linting ([#121](https://github.com/npm/cacache/issues/121)) ([a683cff](https://github.com/npm/cacache/commit/a683cffdfd956e1a4ac0e5ccbfa30615192e1ea0))

## [16.1.1](https://github.com/npm/cacache/compare/v16.1.0...v16.1.1) (2022-06-02)


### Bug Fixes

* **read:** change lstat to stat to correctly evaluate file size ([#114](https://github.com/npm/cacache/issues/114)) ([e3a2928](https://github.com/npm/cacache/commit/e3a2928e053e19fb6e8e73946ffe3d212e402ba7))

## [16.1.0](https://github.com/npm/cacache/compare/v16.0.7...v16.1.0) (2022-05-17)


### Features

* allow external integrity/size source ([#110](https://github.com/npm/cacache/issues/110)) ([61785e1](https://github.com/npm/cacache/commit/61785e106765f4b44041de318f6e387d93759e60))


### Bug Fixes

* move to async functions where possible ([#106](https://github.com/npm/cacache/issues/106)) ([71d4389](https://github.com/npm/cacache/commit/71d4389ff8a35330c3fedce97761094e243d4faf))

### [16.0.7](https://github.com/npm/cacache/compare/v16.0.6...v16.0.7) (2022-04-27)


### Bug Fixes

* **put:** don't flush if an error happened ([e870016](https://github.com/npm/cacache/commit/e8700167e036f392e5554af2d582caa17e4e7237))
* remove disposer ([76ab648](https://github.com/npm/cacache/commit/76ab64857b6874bc54d542ddd483c526434c0b9b))
* remove fs.copyFile checks ([90776fd](https://github.com/npm/cacache/commit/90776fd4a6c5362ea56a979b9611bdf4391e1fd8))

### [16.0.6](https://github.com/npm/cacache/compare/v16.0.5...v16.0.6) (2022-04-21)


### Bug Fixes

* normalize win32 paths before globbing ([4bdd5d5](https://github.com/npm/cacache/commit/4bdd5d5ce21147d67a46b6d2e1ec65007b31705c))

### [16.0.5](https://github.com/npm/cacache/compare/v16.0.4...v16.0.5) (2022-04-20)


### Dependencies

* bump glob from 7.2.0 to 8.0.1 ([#98](https://github.com/npm/cacache/issues/98)) ([74a11f9](https://github.com/npm/cacache/commit/74a11f9f5a1543d593217078a5357707680e2bb1))

### [16.0.4](https://github.com/npm/cacache/compare/v16.0.3...v16.0.4) (2022-04-05)


### Dependencies

* bump @npmcli/move-file from 1.1.2 to 2.0.0 ([#94](https://github.com/npm/cacache/issues/94)) ([f3d64f6](https://github.com/npm/cacache/commit/f3d64f6c238f99433df260fe52081177bdedee86))
* bump ssri from 8.0.1 to 9.0.0 ([#95](https://github.com/npm/cacache/issues/95)) ([fb44f5f](https://github.com/npm/cacache/commit/fb44f5f6bf85f9ee45ba52eb63088b108eca076d))

### [16.0.3](https://github.com/npm/cacache/compare/v16.0.2...v16.0.3) (2022-03-22)


### Dependencies

* bump @npmcli/fs from 1.1.1 to 2.1.0 ([#88](https://github.com/npm/cacache/issues/88)) ([9c9c91c](https://github.com/npm/cacache/commit/9c9c91ce13b941a12c73b95940c5d0b4f4dbf3d0))
* update lru-cache requirement from ^7.5.1 to ^7.7.1 ([#87](https://github.com/npm/cacache/issues/87)) ([800079f](https://github.com/npm/cacache/commit/800079fc5fd18e624bcc53dae3b5f432033e1096))

### [16.0.2](https://www.github.com/npm/cacache/compare/v16.0.1...v16.0.2) (2022-03-16)


### Bug Fixes

* use lru-cache.clear ([#80](https://www.github.com/npm/cacache/issues/80)) ([a48e020](https://www.github.com/npm/cacache/commit/a48e020ca86d28a569578617cc4c7efb76aa8194))

### [16.0.1](https://www.github.com/npm/cacache/compare/v16.0.0...v16.0.1) (2022-03-15)


### Dependencies

* bump lru-cache from 6.0.0 to 7.5.1 ([#77](https://www.github.com/npm/cacache/issues/77)) ([6a3a886](https://www.github.com/npm/cacache/commit/6a3a8863f079aaccb623c4f8d933c485b82e0671))
* update glob requirement from ^7.1.4 to ^7.2.0 ([#74](https://www.github.com/npm/cacache/issues/74)) ([27f1a63](https://www.github.com/npm/cacache/commit/27f1a63cc14de34585330c7ad50f5ae00b3b5b54))
* update minipass requirement from ^3.1.1 to ^3.1.6 ([#76](https://www.github.com/npm/cacache/issues/76)) ([954a430](https://www.github.com/npm/cacache/commit/954a43056fd01ca3a359581dfe32cdfd0ada5f8d))

## [16.0.0](https://www.github.com/npm/cacache/compare/v15.3.0...v16.0.0) (2022-03-14)


### ⚠ BREAKING CHANGES

* this drops support for node10 and non-LTS versions of node12 and node14.

### Bug Fixes

* move files to lib ([cfa4a79](https://www.github.com/npm/cacache/commit/cfa4a7974e1a2b4c4d00613afe20b1925fbe639a))


### Dependencies

* @npmcli/template-oss@2.9.2 ([6e051a7](https://www.github.com/npm/cacache/commit/6e051a782e18288c51914562ae93b4ce52a81ad1))
* update @npmcli/move-file requirement from ^1.0.1 to ^1.1.2 ([#70](https://www.github.com/npm/cacache/issues/70)) ([ddf797a](https://www.github.com/npm/cacache/commit/ddf797a1906e2b285165e544d5ae29a4bb1514ef))
* update fs-minipass requirement from ^2.0.0 to ^2.1.0 ([#72](https://www.github.com/npm/cacache/issues/72)) ([07a5aa1](https://www.github.com/npm/cacache/commit/07a5aa17a8d2245d69f613f9351d4cf84865ade8))
* update minipass-pipeline requirement from ^1.2.2 to ^1.2.4 ([#69](https://www.github.com/npm/cacache/issues/69)) ([372d1a1](https://www.github.com/npm/cacache/commit/372d1a1533aaa8ea37c4cb98f99f40461c9bddac))
* update mkdirp requirement from ^1.0.3 to ^1.0.4 ([#73](https://www.github.com/npm/cacache/issues/73)) ([5fbd50f](https://www.github.com/npm/cacache/commit/5fbd50f1000e8065d754a7c8c89c1c9747532618))
* update tar requirement from ^6.0.2 to ^6.1.11 ([#71](https://www.github.com/npm/cacache/issues/71)) ([4d35625](https://www.github.com/npm/cacache/commit/4d3562565dc52fe51cc5de2fbffceddb63f65118))

## [15.2.0](https://github.com/npm/cacache/releases/v15.2.0) (2021-05-25)

* [8892a92](https://github.com/npm/cacache/commit/8892a92) add a validateEntry option to compact
* [460b951](https://github.com/npm/cacache/commit/460b951) allow fully deleting indexes

## [15.1.0](https://github.com/npm/cacache/compare/v15.0.6...v15.1.0) (2021-05-19)


### Features

* allow formatEntry to keep entries with no integrity value ([930f531](https://github.com/npm/cacache/commit/930f5313825a84277c531defe53696b8c9f4ef70)), closes [#53](https://github.com/npm/cacache/issues/53)
* expose index.insert, implement and expose index.compact ([c4efb74](https://github.com/npm/cacache/commit/c4efb7427cd40694933a46ef3eb59d32ce4d0eed))

### [15.0.6](https://github.com/npm/cacache/compare/v15.0.5...v15.0.6) (2021-03-22)

### [15.0.5](https://github.com/npm/cacache/compare/v15.0.4...v15.0.5) (2020-07-11)

### [15.0.4](https://github.com/npm/cacache/compare/v15.0.3...v15.0.4) (2020-06-03)


### Bug Fixes

* replace move-file dep with @npmcli/move-file ([bf88af0](https://github.com/npm/cacache/commit/bf88af04e50cca9b54041151139ffc1fd415e2dc)), closes [#37](https://github.com/npm/cacache/issues/37)

### [15.0.3](https://github.com/npm/cacache/compare/v15.0.2...v15.0.3) (2020-04-28)


### Bug Fixes

* actually remove move-concurrently dep ([29e6eec](https://github.com/npm/cacache/commit/29e6eec9fee73444ee09daf1c1be06ddd5fe57f6))

### [15.0.2](https://github.com/npm/cacache/compare/v15.0.1...v15.0.2) (2020-04-28)


### Bug Fixes

* tacks should be a dev dependency ([93ec158](https://github.com/npm/cacache/commit/93ec15852f0fdf1753ea7f75b4b8926daf8a7565))

## [15.0.1](https://github.com/npm/cacache/compare/v15.0.0...v15.0.1) (2020-04-27)

* **deps:** Use move-file instead of move-file-concurrently. ([92b125](https://github.com/npm/cacache/commit/92b1251a11b9848878b6c0d101b18bd8845acaa6))

## [15.0.0](https://github.com/npm/cacache/compare/v14.0.0...v15.0.0) (2020-02-18)


### ⚠ BREAKING CHANGES

* drop figgy-pudding and use canonical option names.

### Features

* remove figgy-pudding ([57d11bc](https://github.com/npm/cacache/commit/57d11bce34f979247d1057d258acc204c4944491))

## [14.0.0](https://github.com/npm/cacache/compare/v13.0.1...v14.0.0) (2020-01-28)


### ⚠ BREAKING CHANGES

* **deps:** bumps engines to >= 10

* **deps:** tar v6 and mkdirp v1 ([5a66e7a](https://github.com/npm/cacache/commit/5a66e7a))

### [13.0.1](https://github.com/npm/cacache/compare/v13.0.0...v13.0.1) (2019-09-30)


### Bug Fixes

* **fix-owner:** chownr.sync quits on non-root uid ([08801be](https://github.com/npm/cacache/commit/08801be))

## [13.0.0](https://github.com/npm/cacache/compare/v12.0.3...v13.0.0) (2019-09-25)


### ⚠ BREAKING CHANGES

* This subtly changes the streaming interface of
everything in cacache that streams, which is, well, everything in
cacache.  Most users will probably not notice, but any code that
depended on stream behavior always being deferred until next tick will
need to adjust.

The mississippi methods 'to', 'from', 'through', and so on, have been
replaced with their Minipass counterparts, and streaming interaction
with the file system is done via fs-minipass.

The following modules are of interest here:

- [minipass](http://npm.im/minipass) The core stream library.

- [fs-minipass](http://npm.im/fs-minipass)  Note that the 'WriteStream'
  class from fs-minipass is _not_ a Minipass stream, but rather a plain
  old EventEmitter that duck types as a Writable.

- [minipass-collect](http://npm.im/minipass-collect) Gather up all the
  data from a stream.  Cacache only uses Collect.PassThrough, which is a
  basic Minipass passthrough stream which emits a 'collect' event with
  the completed data just before the 'end' event.

- [minipass-pipeline](http://npm.im/minipass-pipeline) Connect one or
  more streams into a pipe chain.  Errors anywhere in the pipeline are
  proxied down the chain and then up to the Pipeline object itself.
  Writes go into the head, reads go to the tail.  Used in place of
  pump() and pumpify().

- [minipass-flush](http://npm.im/minipass-flush) A Minipass passthrough
  stream that defers its 'end' event until after a flush() method has
  completed (either calling the supplied callback, or returning a
  promise.)  Use in place of flush-write-stream (aka mississippi.to).

Streams from through2, concat-stream, and the behavior provided by
end-of-stream are all implemented in Minipass itself.

Features of interest to cacache, which make Minipass a particularly good
fit:

- All of the 'endish' events are normalized, so we can just listen on
  'end' and know that finish, prefinish, and close will be handled as
  well.
- Minipass doesn't waste time [containing
  zalgo](https://blog.izs.me/2013/08/designing-apis-for-asynchrony).
- Minipass has built-in support for promises that indicate the end or
  error: stream.promise(), stream.collect(), and stream.concat().
- With reliable and consistent timing guarantees, much less
  error-checking logic is required.  We can be more confident that an
  error is being thrown or emitted in the correct place, rather than in
  a callback which is deferred, resulting in a hung promise or
  uncaughtException.

The biggest downside of Minipass is that it lacks some of the internal
characteristics of node-core streams, which many community modules use
to identify streams.  They have no _writableState or _readableState
objects, or _read or _write methods.  As a result, the is-stream module
(at least, at the time of this commit) doesn't recognize Minipass
streams as readable or writable streams.

All in all, the changes required of downstream users should be minimal,
but are unlikely to be zero.  Hence the semver major change.

### Features

* replace all streams with Minipass streams ([f4c0962](https://github.com/npm/cacache/commit/f4c0962))
* **deps:** Add minipass and minipass-pipeline ([a6545a9](https://github.com/npm/cacache/commit/a6545a9))
* **promise:** converted .resolve to native promise, converted .map and .reduce to native ([220c56d](https://github.com/npm/cacache/commit/220c56d))
* **promise:** individually promisifing functions as needed ([74b939e](https://github.com/npm/cacache/commit/74b939e))
* **promise:** moved .reject from bluebird to native promise ([1d56da1](https://github.com/npm/cacache/commit/1d56da1))
* **promise:** removed .fromNode, removed .join ([9c457a0](https://github.com/npm/cacache/commit/9c457a0))
* **promise:** removed .map, replaced with p-map. removed .try ([cc3ee05](https://github.com/npm/cacache/commit/cc3ee05))
* **promise:** removed .tap ([0260f12](https://github.com/npm/cacache/commit/0260f12))
* **promise:** removed .using/.disposer ([5d832f3](https://github.com/npm/cacache/commit/5d832f3))
* **promise:** removed bluebird ([c21298c](https://github.com/npm/cacache/commit/c21298c))
* **promise:** removed bluebird specific .catch calls ([28aeeac](https://github.com/npm/cacache/commit/28aeeac))
* **promise:** replaced .reduce and .mapSeries ([478f5cb](https://github.com/npm/cacache/commit/478f5cb))

### [12.0.3](https://github.com/npm/cacache/compare/v12.0.2...v12.0.3) (2019-08-19)


### Bug Fixes

* do not chown if not running as root ([2d80af9](https://github.com/npm/cacache/commit/2d80af9))



### [12.0.2](https://github.com/npm/cacache/compare/v12.0.1...v12.0.2) (2019-07-19)



### [12.0.1](https://github.com/npm/cacache/compare/v12.0.0...v12.0.1) (2019-07-19)

* **deps** Abstracted out `lib/util/infer-owner.js` to
  [@npmcli/infer-owner](https://www.npmjs.com/package/@npmcli/infer-owner)
  so that it could be more easily used in other parts of the npm CLI.


## [12.0.0](https://github.com/npm/cacache/compare/v11.3.3...v12.0.0) (2019-07-15)


### Features

* infer uid/gid instead of accepting as options ([ac84d14](https://github.com/npm/cacache/commit/ac84d14))
* **i18n:** add another error message ([676cb32](https://github.com/npm/cacache/commit/676cb32))


### BREAKING CHANGES

* the uid gid options are no longer respected or
necessary.  As of this change, cacache will always match the cache
contents to the ownership of the cache directory (or its parent
directory), regardless of what the caller passes in.

Reasoning:

The number one reason to use a uid or gid option was to keep root-owned
files from causing problems in the cache.  In npm's case, this meant
that CLI's ./lib/command.js had to work out the appropriate uid and gid,
then pass it to the libnpmcommand module, which had to in turn pass the
uid and gid to npm-registry-fetch, which then passed it to
make-fetch-happen, which passed it to cacache.  (For package fetching,
pacote would be in that mix as well.)

Added to that, `cacache.rm()` will actually _write_ a file into the
cache index, but has no way to accept an option so that its call to
entry-index.js will write the index with the appropriate uid/gid.
Little ownership bugs were all over the place, and tricky to trace
through.  (Why should make-fetch-happen even care about accepting or
passing uids and gids?  It's an http library.)

This change allows us to keep the cache from having mixed ownership in
any situation.

Of course, this _does_ mean that if you have a root-owned but
user-writable folder (for example, `/tmp`), then the cache will try to
chown everything to root.

The solution is for the user to create a folder, make it user-owned, and
use that, rather than relying on cacache to create the root cache folder.

If we decide to restore the uid/gid opts, and use ownership inference
only when uid/gid are unset, then take care to also make rm take an
option object, and pass it through to entry-index.js.



### [11.3.3](https://github.com/npm/cacache/compare/v11.3.2...v11.3.3) (2019-06-17)


### Bug Fixes

* **audit:** npm audit fix ([200a6d5](https://github.com/npm/cacache/commit/200a6d5))
* **config:** Add ssri config 'error' option ([#146](https://github.com/npm/cacache/issues/146)) ([47de8f5](https://github.com/npm/cacache/commit/47de8f5))
* **deps:** npm audit fix ([481a7dc](https://github.com/npm/cacache/commit/481a7dc))
* **standard:** standard --fix ([7799149](https://github.com/npm/cacache/commit/7799149))
* **write:** avoid another cb never called situation ([5156561](https://github.com/npm/cacache/commit/5156561))



<a name="11.3.2"></a>
## [11.3.2](https://github.com/npm/cacache/compare/v11.3.1...v11.3.2) (2018-12-21)


### Bug Fixes

* **get:** make sure to handle errors in the .then ([b10bcd0](https://github.com/npm/cacache/commit/b10bcd0))



<a name="11.3.1"></a>
## [11.3.1](https://github.com/npm/cacache/compare/v11.3.0...v11.3.1) (2018-11-05)


### Bug Fixes

* **get:** export hasContent.sync properly ([d76c920](https://github.com/npm/cacache/commit/d76c920))



<a name="11.3.0"></a>
# [11.3.0](https://github.com/npm/cacache/compare/v11.2.0...v11.3.0) (2018-11-05)


### Features

* **get:** add sync API for reading ([db1e094](https://github.com/npm/cacache/commit/db1e094))



<a name="11.2.0"></a>
# [11.2.0](https://github.com/npm/cacache/compare/v11.1.0...v11.2.0) (2018-08-08)


### Features

* **read:** add sync support to other internal read.js fns ([fe638b6](https://github.com/npm/cacache/commit/fe638b6))



<a name="11.1.0"></a>
# [11.1.0](https://github.com/npm/cacache/compare/v11.0.3...v11.1.0) (2018-08-01)


### Features

* **read:** add sync support for low-level content read ([b43af83](https://github.com/npm/cacache/commit/b43af83))



<a name="11.0.3"></a>
## [11.0.3](https://github.com/npm/cacache/compare/v11.0.2...v11.0.3) (2018-08-01)


### Bug Fixes

* **config:** add ssri config options ([#136](https://github.com/npm/cacache/issues/136)) ([10d5d9a](https://github.com/npm/cacache/commit/10d5d9a))
* **perf:** refactor content.read to avoid lstats ([c5ac10e](https://github.com/npm/cacache/commit/c5ac10e))
* **test:** oops when removing safe-buffer ([1950490](https://github.com/npm/cacache/commit/1950490))



<a name="11.0.2"></a>
## [11.0.2](https://github.com/npm/cacache/compare/v11.0.1...v11.0.2) (2018-05-07)


### Bug Fixes

* **verify:** size param no longer lost in a verify ([#131](https://github.com/npm/cacache/issues/131)) ([c614a19](https://github.com/npm/cacache/commit/c614a19)), closes [#130](https://github.com/npm/cacache/issues/130)



<a name="11.0.1"></a>
## [11.0.1](https://github.com/npm/cacache/compare/v11.0.0...v11.0.1) (2018-04-10)



<a name="11.0.0"></a>
# [11.0.0](https://github.com/npm/cacache/compare/v10.0.4...v11.0.0) (2018-04-09)


### Features

* **opts:** use figgy-pudding for opts ([#128](https://github.com/npm/cacache/issues/128)) ([33d4eed](https://github.com/npm/cacache/commit/33d4eed))


### meta

* drop support for node@4 ([529f347](https://github.com/npm/cacache/commit/529f347))


### BREAKING CHANGES

* node@4 is no longer supported



<a name="10.0.4"></a>
## [10.0.4](https://github.com/npm/cacache/compare/v10.0.3...v10.0.4) (2018-02-16)



<a name="10.0.3"></a>
## [10.0.3](https://github.com/npm/cacache/compare/v10.0.2...v10.0.3) (2018-02-16)


### Bug Fixes

* **content:** rethrow aggregate errors as ENOENT ([fa918f5](https://github.com/npm/cacache/commit/fa918f5))



<a name="10.0.2"></a>
## [10.0.2](https://github.com/npm/cacache/compare/v10.0.1...v10.0.2) (2018-01-07)


### Bug Fixes

* **ls:** deleted entries could cause a premature stream EOF ([347dc36](https://github.com/npm/cacache/commit/347dc36))



<a name="10.0.1"></a>
## [10.0.1](https://github.com/npm/cacache/compare/v10.0.0...v10.0.1) (2017-11-15)


### Bug Fixes

* **move-file:** actually use the fallback to `move-concurrently` (#110) ([073fbe1](https://github.com/npm/cacache/commit/073fbe1))



<a name="10.0.0"></a>
# [10.0.0](https://github.com/npm/cacache/compare/v9.3.0...v10.0.0) (2017-10-23)


### Features

* **license:** relicense to ISC (#111) ([fdbb4e5](https://github.com/npm/cacache/commit/fdbb4e5))


### Performance Improvements

* more copyFile benchmarks ([63787bb](https://github.com/npm/cacache/commit/63787bb))


### BREAKING CHANGES

* **license:** the license has been changed from CC0-1.0 to ISC.



<a name="9.3.0"></a>
# [9.3.0](https://github.com/npm/cacache/compare/v9.2.9...v9.3.0) (2017-10-07)


### Features

* **copy:** added cacache.get.copy api for fast copies (#107) ([067b5f6](https://github.com/npm/cacache/commit/067b5f6))



<a name="9.2.9"></a>
## [9.2.9](https://github.com/npm/cacache/compare/v9.2.8...v9.2.9) (2017-06-17)



<a name="9.2.8"></a>
## [9.2.8](https://github.com/npm/cacache/compare/v9.2.7...v9.2.8) (2017-06-05)


### Bug Fixes

* **ssri:** bump ssri for bugfix ([c3232ea](https://github.com/npm/cacache/commit/c3232ea))



<a name="9.2.7"></a>
## [9.2.7](https://github.com/npm/cacache/compare/v9.2.6...v9.2.7) (2017-06-05)


### Bug Fixes

* **content:** make verified content completely read-only (#96) ([4131196](https://github.com/npm/cacache/commit/4131196))



<a name="9.2.6"></a>
## [9.2.6](https://github.com/npm/cacache/compare/v9.2.5...v9.2.6) (2017-05-31)


### Bug Fixes

* **node:** update ssri to prevent old node 4 crash ([5209ffe](https://github.com/npm/cacache/commit/5209ffe))



<a name="9.2.5"></a>
## [9.2.5](https://github.com/npm/cacache/compare/v9.2.4...v9.2.5) (2017-05-25)


### Bug Fixes

* **deps:** fix lockfile issues and bump ssri ([84e1d7e](https://github.com/npm/cacache/commit/84e1d7e))



<a name="9.2.4"></a>
## [9.2.4](https://github.com/npm/cacache/compare/v9.2.3...v9.2.4) (2017-05-24)


### Bug Fixes

* **deps:** bumping deps ([bbccb12](https://github.com/npm/cacache/commit/bbccb12))



<a name="9.2.3"></a>
## [9.2.3](https://github.com/npm/cacache/compare/v9.2.2...v9.2.3) (2017-05-24)


### Bug Fixes

* **rm:** stop crashing if content is missing on rm ([ac90bc0](https://github.com/npm/cacache/commit/ac90bc0))



<a name="9.2.2"></a>
## [9.2.2](https://github.com/npm/cacache/compare/v9.2.1...v9.2.2) (2017-05-14)


### Bug Fixes

* **i18n:** lets pretend this didn't happen ([519b4ee](https://github.com/npm/cacache/commit/519b4ee))



<a name="9.2.1"></a>
## [9.2.1](https://github.com/npm/cacache/compare/v9.2.0...v9.2.1) (2017-05-14)


### Bug Fixes

* **docs:** fixing translation messup ([bb9e4f9](https://github.com/npm/cacache/commit/bb9e4f9))



<a name="9.2.0"></a>
# [9.2.0](https://github.com/npm/cacache/compare/v9.1.0...v9.2.0) (2017-05-14)


### Features

* **i18n:** add Spanish translation for API ([531f9a4](https://github.com/npm/cacache/commit/531f9a4))



<a name="9.1.0"></a>
# [9.1.0](https://github.com/npm/cacache/compare/v9.0.0...v9.1.0) (2017-05-14)


### Features

* **i18n:** Add Spanish translation and i18n setup (#91) ([323b90c](https://github.com/npm/cacache/commit/323b90c))



<a name="9.0.0"></a>
# [9.0.0](https://github.com/npm/cacache/compare/v8.0.0...v9.0.0) (2017-04-28)


### Bug Fixes

* **memoization:** actually use the LRU ([0e55dc9](https://github.com/npm/cacache/commit/0e55dc9))


### Features

* **memoization:** memoizers can be injected through opts.memoize (#90) ([e5614c7](https://github.com/npm/cacache/commit/e5614c7))


### BREAKING CHANGES

* **memoization:** If you were passing an object to opts.memoize, it will now be used as an injected memoization object. If you were only passing booleans and other non-objects through that option, no changes are needed.



<a name="8.0.0"></a>
# [8.0.0](https://github.com/npm/cacache/compare/v7.1.0...v8.0.0) (2017-04-22)


### Features

* **read:** change hasContent to return {sri, size} (#88) ([bad6c49](https://github.com/npm/cacache/commit/bad6c49)), closes [#87](https://github.com/npm/cacache/issues/87)


### BREAKING CHANGES

* **read:** hasContent now returns an object with `{sri, size}` instead of `sri`. Use `result.sri` anywhere that needed the old return value.



<a name="7.1.0"></a>
# [7.1.0](https://github.com/npm/cacache/compare/v7.0.5...v7.1.0) (2017-04-20)


### Features

* **size:** handle content size info (#49) ([91230af](https://github.com/npm/cacache/commit/91230af))



<a name="7.0.5"></a>
## [7.0.5](https://github.com/npm/cacache/compare/v7.0.4...v7.0.5) (2017-04-18)


### Bug Fixes

* **integrity:** new ssri with fixed integrity stream ([6d13e8e](https://github.com/npm/cacache/commit/6d13e8e))
* **write:** wrap stuff in promises to improve errors ([3624fc5](https://github.com/npm/cacache/commit/3624fc5))



<a name="7.0.4"></a>
## [7.0.4](https://github.com/npm/cacache/compare/v7.0.3...v7.0.4) (2017-04-15)


### Bug Fixes

* **fix-owner:** throw away ENOENTs on chownr ([d49bbcd](https://github.com/npm/cacache/commit/d49bbcd))



<a name="7.0.3"></a>
## [7.0.3](https://github.com/npm/cacache/compare/v7.0.2...v7.0.3) (2017-04-05)


### Bug Fixes

* **read:** fixing error message for integrity verification failures ([9d4f0a5](https://github.com/npm/cacache/commit/9d4f0a5))



<a name="7.0.2"></a>
## [7.0.2](https://github.com/npm/cacache/compare/v7.0.1...v7.0.2) (2017-04-03)


### Bug Fixes

* **integrity:** use EINTEGRITY error code and update ssri ([8dc2e62](https://github.com/npm/cacache/commit/8dc2e62))



<a name="7.0.1"></a>
## [7.0.1](https://github.com/npm/cacache/compare/v7.0.0...v7.0.1) (2017-04-03)


### Bug Fixes

* **docs:** fix header name conflict in readme ([afcd456](https://github.com/npm/cacache/commit/afcd456))



<a name="7.0.0"></a>
# [7.0.0](https://github.com/npm/cacache/compare/v6.3.0...v7.0.0) (2017-04-03)


### Bug Fixes

* **test:** fix content.write tests when running in docker ([d2e9b6a](https://github.com/npm/cacache/commit/d2e9b6a))


### Features

* **integrity:** subresource integrity support (#78) ([b1e731f](https://github.com/npm/cacache/commit/b1e731f))


### BREAKING CHANGES

* **integrity:** The entire API has been overhauled to use SRI hashes instead of digest/hashAlgorithm pairs. SRI hashes follow the Subresource Integrity standard and support strings and objects compatible with [`ssri`](https://npm.im/ssri).

* This change bumps the index version, which will invalidate all previous index entries. Content entries will remain intact, and existing caches will automatically reuse any content from before this breaking change.

* `cacache.get.info()`, `cacache.ls()`, and `cacache.ls.stream()` will now return objects that looks like this:

```
{
  key: String,
  integrity: '<algorithm>-<base64hash>',
  path: ContentPath,
  time: Date<ms>,
  metadata: Any
}
```

* `opts.digest` and `opts.hashAlgorithm` are obsolete for any API calls that used them.

* Anywhere `opts.digest` was accepted, `opts.integrity` is now an option. Any valid SRI hash is accepted here -- multiple hash entries will be resolved according to the standard: first, the "strongest" hash algorithm will be picked, and then each of the entries for that algorithm will be matched against the content. Content will be validated if *any* of the entries match (so, a single integrity string can be used for multiple "versions" of the same document/data).

* `put.byDigest()`, `put.stream.byDigest`, `get.byDigest()` and `get.stream.byDigest()` now expect an SRI instead of a `digest` + `opts.hashAlgorithm` pairing.

* `get.hasContent()` now expects an integrity hash instead of a digest. If content exists, it will return the specific single integrity hash that was found in the cache.

* `verify()` has learned to handle integrity-based caches, and forgotten how to handle old-style cache indices due to the format change.

* `cacache.rm.content()` now expects an integrity hash instead of a hex digest.



<a name="6.3.0"></a>
# [6.3.0](https://github.com/npm/cacache/compare/v6.2.0...v6.3.0) (2017-04-01)


### Bug Fixes

* **fixOwner:** ignore EEXIST race condition from mkdirp ([4670e9b](https://github.com/npm/cacache/commit/4670e9b))
* **index:** ignore index removal races when inserting ([b9d2fa2](https://github.com/npm/cacache/commit/b9d2fa2))
* **memo:** use lru-cache for better mem management (#75) ([d8ac5aa](https://github.com/npm/cacache/commit/d8ac5aa))


### Features

* **dependencies:** Switch to move-concurrently (#77) ([dc6482d](https://github.com/npm/cacache/commit/dc6482d))



<a name="6.2.0"></a>
# [6.2.0](https://github.com/npm/cacache/compare/v6.1.2...v6.2.0) (2017-03-15)


### Bug Fixes

* **index:** additional bucket entry verification with checksum (#72) ([f8e0f25](https://github.com/npm/cacache/commit/f8e0f25))
* **verify:** return fixOwner.chownr promise ([6818521](https://github.com/npm/cacache/commit/6818521))


### Features

* **tmp:** safe tmp dir creation/management util (#73) ([c42da71](https://github.com/npm/cacache/commit/c42da71))



<a name="6.1.2"></a>
## [6.1.2](https://github.com/npm/cacache/compare/v6.1.1...v6.1.2) (2017-03-13)


### Bug Fixes

* **index:** set default hashAlgorithm ([d6eb2f0](https://github.com/npm/cacache/commit/d6eb2f0))



<a name="6.1.1"></a>
## [6.1.1](https://github.com/npm/cacache/compare/v6.1.0...v6.1.1) (2017-03-13)


### Bug Fixes

* **coverage:** bumping coverage for verify (#71) ([0b7faf6](https://github.com/npm/cacache/commit/0b7faf6))
* **deps:** glob should have been a regular dep :< ([0640bc4](https://github.com/npm/cacache/commit/0640bc4))



<a name="6.1.0"></a>
# [6.1.0](https://github.com/npm/cacache/compare/v6.0.2...v6.1.0) (2017-03-12)


### Bug Fixes

* **coverage:** more coverage for content reads (#70) ([ef4f70a](https://github.com/npm/cacache/commit/ef4f70a))
* **tests:** use safe-buffer because omfg (#69) ([6ab8132](https://github.com/npm/cacache/commit/6ab8132))


### Features

* **rm:** limited rm.all and fixed bugs (#66) ([d5d25ba](https://github.com/npm/cacache/commit/d5d25ba)), closes [#66](https://github.com/npm/cacache/issues/66)
* **verify:** tested, working cache verifier/gc (#68) ([45ad77a](https://github.com/npm/cacache/commit/45ad77a))



<a name="6.0.2"></a>
## [6.0.2](https://github.com/npm/cacache/compare/v6.0.1...v6.0.2) (2017-03-11)


### Bug Fixes

* **index:** segment cache items with another subbucket (#64) ([c3644e5](https://github.com/npm/cacache/commit/c3644e5))



<a name="6.0.1"></a>
## [6.0.1](https://github.com/npm/cacache/compare/v6.0.0...v6.0.1) (2017-03-05)


### Bug Fixes

* **docs:** Missed spots in README ([8ffb7fa](https://github.com/npm/cacache/commit/8ffb7fa))



<a name="6.0.0"></a>
# [6.0.0](https://github.com/npm/cacache/compare/v5.0.3...v6.0.0) (2017-03-05)


### Bug Fixes

* **api:** keep memo cache mostly-internal ([2f72d0a](https://github.com/npm/cacache/commit/2f72d0a))
* **content:** use the rest of the string, not the whole string ([fa8f3c3](https://github.com/npm/cacache/commit/fa8f3c3))
* **deps:** removed `format-number@2.0.2` ([1187791](https://github.com/npm/cacache/commit/1187791))
* **deps:** removed inflight@1.0.6 ([0d1819c](https://github.com/npm/cacache/commit/0d1819c))
* **deps:** rimraf@2.6.1 ([9efab6b](https://github.com/npm/cacache/commit/9efab6b))
* **deps:** standard@9.0.0 ([4202cba](https://github.com/npm/cacache/commit/4202cba))
* **deps:** tap@10.3.0 ([aa03088](https://github.com/npm/cacache/commit/aa03088))
* **deps:** weallcontribute@1.0.8 ([ad4f4dc](https://github.com/npm/cacache/commit/ad4f4dc))
* **docs:** add security note to hashKey ([03f81ba](https://github.com/npm/cacache/commit/03f81ba))
* **hashes:** change default hashAlgorithm to sha512 ([ea00ba6](https://github.com/npm/cacache/commit/ea00ba6))
* **hashes:** missed a spot for hashAlgorithm defaults ([45997d8](https://github.com/npm/cacache/commit/45997d8))
* **index:** add length header before JSON for verification ([fb8cb4d](https://github.com/npm/cacache/commit/fb8cb4d))
* **index:** change index filenames to sha1s of keys ([bbc5fca](https://github.com/npm/cacache/commit/bbc5fca))
* **index:** who cares about race conditions anyway ([b1d3888](https://github.com/npm/cacache/commit/b1d3888))
* **perf:** bulk-read get+read for massive speed ([d26cdf9](https://github.com/npm/cacache/commit/d26cdf9))
* **perf:** use bulk file reads for index reads ([79a8891](https://github.com/npm/cacache/commit/79a8891))
* **put-stream:** remove tmp file on stream insert error ([65f6632](https://github.com/npm/cacache/commit/65f6632))
* **put-stream:** robustified and predictibilized ([daf9e08](https://github.com/npm/cacache/commit/daf9e08))
* **put-stream:** use new promise API for moves ([1d36013](https://github.com/npm/cacache/commit/1d36013))
* **readme:** updated to reflect new default hashAlgo ([c60a2fa](https://github.com/npm/cacache/commit/c60a2fa))
* **verify:** tiny typo fix ([db22d05](https://github.com/npm/cacache/commit/db22d05))


### Features

* **api:** converted external api ([7bf032f](https://github.com/npm/cacache/commit/7bf032f))
* **cacache:** exported clearMemoized() utility ([8d2c5b6](https://github.com/npm/cacache/commit/8d2c5b6))
* **cache:** add versioning to content and index ([31bc549](https://github.com/npm/cacache/commit/31bc549))
* **content:** collate content files into subdirs ([c094d9f](https://github.com/npm/cacache/commit/c094d9f))
* **deps:** `@npmcorp/move@1.0.0` ([bdd00bf](https://github.com/npm/cacache/commit/bdd00bf))
* **deps:** `bluebird@3.4.7` ([3a17aff](https://github.com/npm/cacache/commit/3a17aff))
* **deps:** `promise-inflight@1.0.1` ([a004fe6](https://github.com/npm/cacache/commit/a004fe6))
* **get:** added memoization support for get ([c77d794](https://github.com/npm/cacache/commit/c77d794))
* **get:** export hasContent ([2956ec3](https://github.com/npm/cacache/commit/2956ec3))
* **index:** add hashAlgorithm and format insert ret val ([b639746](https://github.com/npm/cacache/commit/b639746))
* **index:** collate index files into subdirs ([e8402a5](https://github.com/npm/cacache/commit/e8402a5))
* **index:** promisify entry index ([cda3335](https://github.com/npm/cacache/commit/cda3335))
* **memo:** added memoization lib ([da07b92](https://github.com/npm/cacache/commit/da07b92))
* **memo:** export memoization api ([954b1b3](https://github.com/npm/cacache/commit/954b1b3))
* **move-file:** add move fallback for weird errors ([5cf4616](https://github.com/npm/cacache/commit/5cf4616))
* **perf:** bulk content write api ([51b536e](https://github.com/npm/cacache/commit/51b536e))
* **put:** added memoization support to put ([b613a70](https://github.com/npm/cacache/commit/b613a70))
* **read:** switched to promises ([a869362](https://github.com/npm/cacache/commit/a869362))
* **rm:** added memoization support to rm ([4205cf0](https://github.com/npm/cacache/commit/4205cf0))
* **rm:** switched to promises ([a000d24](https://github.com/npm/cacache/commit/a000d24))
* **util:** promise-inflight ownership fix requests ([9517cd7](https://github.com/npm/cacache/commit/9517cd7))
* **util:** use promises for api ([ae204bb](https://github.com/npm/cacache/commit/ae204bb))
* **verify:** converted to Promises ([f0b3974](https://github.com/npm/cacache/commit/f0b3974))


### BREAKING CHANGES

* cache: index/content directories are now versioned. Previous caches are no longer compatible and cannot be migrated.
* util: fix-owner now uses Promises instead of callbacks
* index: Previously-generated index entries are no longer compatible and the index must be regenerated.
* index: The index format has changed and previous caches are no longer compatible. Existing caches will need to be regenerated.
* hashes: Default hashAlgorithm changed from sha1 to sha512. If you
rely on the prior setting, pass `opts.hashAlgorithm` in explicitly.
* content: Previously-generated content directories are no longer compatible
and must be regenerated.
* verify: API is now promise-based
* read: Switches to a Promise-based API and removes callback stuff
* rm: Switches to a Promise-based API and removes callback stuff
* index: this changes the API to work off promises instead of callbacks
* api: this means we are going all in on promises now

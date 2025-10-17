# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.4.1](https://github.com/alibaba/lowcode-engine/compare/v1.4.0...v1.4.1) (2025-10-17)

**Note:** Version bump only for package @epoch/lowcode-plugin-outline-pane





# 1.4.0 (2025-10-17)


### Bug Fixes

* expandable state not changed when node added/removed ([37dffae](https://github.com/alibaba/lowcode-engine/commit/37dffae1b8925a94888a8abba7e8bae9baf11a03))
* **filter:**  unique key prop warning ([06e6920](https://github.com/alibaba/lowcode-engine/commit/06e6920602bdf21b6e1ffe5cfa3dfe4856e7c57e))
* fix cant change the panel tree item title with prop api ([80fc976](https://github.com/alibaba/lowcode-engine/commit/80fc9766b19a762dd5d773cbb12cda128e79a942))
* fix outline-tree initialization failed ([a2d5c6f](https://github.com/alibaba/lowcode-engine/commit/a2d5c6fd90ca0226bbbfea01a4b28c8b8d307a78))
* fix outlinePane treeView render only once ([8b44ed4](https://github.com/alibaba/lowcode-engine/commit/8b44ed44295aa66105c9799fcd41f360c411e324))
* fix plugin-outline-pane condition tag not update ([48ddc4d](https://github.com/alibaba/lowcode-engine/commit/48ddc4db59a92f7da8852a261a6274290df2d44a))
* fix that the outline tree does not respond to modal addition/deletion related operations ([f1ff1a0](https://github.com/alibaba/lowcode-engine/commit/f1ff1a07065160a61f103b249c108709976c9589))
* fix the problem that the outline pane tree cannot be expanded ([76ec15f](https://github.com/alibaba/lowcode-engine/commit/76ec15f5b77aa484cefcecc0de430d0b6c8a7bc9))
* fixed an issue where the outline tree was not displayed correctly when deleting a node ([06aaef7](https://github.com/alibaba/lowcode-engine/commit/06aaef777dbdd45850c26e9a8a4b808cdf9ae03f))
* Optimize the initialization method for masterPaneController ([#2333](https://github.com/alibaba/lowcode-engine/issues/2333)) ([14390f0](https://github.com/alibaba/lowcode-engine/commit/14390f000d93f7fc2e1f09e54d3d972a39593ca5))
* **outline-pane:** hover invalid ([f7ba053](https://github.com/alibaba/lowcode-engine/commit/f7ba053476302b5b87d01a856e1ab98076591a3a))
* **outline-pane:** tree does not change when doc.importSchema call ([7eed096](https://github.com/alibaba/lowcode-engine/commit/7eed0966e9dded8c9024525771bf0d986e6d49c8))
* **outline-pane:** when dialog is dragged, the outline pane is not displayed visible state ([a3b9d6f](https://github.com/alibaba/lowcode-engine/commit/a3b9d6ff48995e5580fe42b2507388a2e3ae03e2))
* **outline:** fix view change bugs in workspace mode ([a25aad4](https://github.com/alibaba/lowcode-engine/commit/a25aad4975231706a9e47ba3e62e17034ce18846))
* **plugin-outline-pane:** fix text display errors and improve internationalization ([e6e5ea8](https://github.com/alibaba/lowcode-engine/commit/e6e5ea8a104534eb6300641b6b6d0be035db37f0))
* the action of history would not update outline tree ([2d98f1c](https://github.com/alibaba/lowcode-engine/commit/2d98f1c9b5d8c8bbda5100ddecb83ceb08943b36))
* trigger onFilterResultChanged when filtered ([e1f3a11](https://github.com/alibaba/lowcode-engine/commit/e1f3a11c4197317fd9a520ca014b78905096b46f))
* 新元素无法在大纲树拖拽 ([3d41fd5](https://github.com/alibaba/lowcode-engine/commit/3d41fd5d0783048a7cfb54c6f80d058856153d25))


### Features

* add APIs for plugin-outline-pane which will be splitted in near future ([7b58b6a](https://github.com/alibaba/lowcode-engine/commit/7b58b6a6d755395ba80f4857d617a0d3841084f1))
* add createIntl to common.utils, and fix misuse of zh_CN ([84e0c1f](https://github.com/alibaba/lowcode-engine/commit/84e0c1f09609d81716274af2f94c676e68ab8f15))
* add get advanced api for ComponentMeta ([810ccbd](https://github.com/alibaba/lowcode-engine/commit/810ccbd03ef6ce5e4159c3e52aa7efad7073a67e))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add some features ([18d1a4f](https://github.com/alibaba/lowcode-engine/commit/18d1a4fe1d952bcd4715e693def09fee94da49a5))
* add theme color document & optimize some theme colors ([79b9a6e](https://github.com/alibaba/lowcode-engine/commit/79b9a6efa57d1a30559ea8476bbb380b5957d968))
* add types for shell, and move functions in types to utils ([55c3fc9](https://github.com/alibaba/lowcode-engine/commit/55c3fc9e58d566edeabd1daa489ac83ba6b787d1))
* canvas.activeTracker add targer prop ([2b3d96c](https://github.com/alibaba/lowcode-engine/commit/2b3d96cedada3f3c3f91f16129aadee466052b9b))
* disable behaviors according to components in outline-tree ([7bef507](https://github.com/alibaba/lowcode-engine/commit/7bef50762c2032ce640aedcc10a16739e9471885))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* fix the problem of plugin outline tree in workspace mode ([631b566](https://github.com/alibaba/lowcode-engine/commit/631b5669327436b8fe7870bd474d2690a265ace5))
* optimize outline tree performance and ts definition ([eeb6719](https://github.com/alibaba/lowcode-engine/commit/eeb6719a1ff1defff3b91a2f1455d0b7daaa252d))
* **outline-pane:** export OutlinePaneContext ([5b14230](https://github.com/alibaba/lowcode-engine/commit/5b1423068e5630975cba21460a58b46702810dee))
* **outline-pane:** suport registry in workspace level ([029fd1c](https://github.com/alibaba/lowcode-engine/commit/029fd1ce67739e85dd669c61ebfedf52199c2d11))
* outline-plugin-pane support overflow-x scroll & delete node ([#2376](https://github.com/alibaba/lowcode-engine/issues/2376)) ([15f5675](https://github.com/alibaba/lowcode-engine/commit/15f5675ddd75b453249ec388164767a0412444d9))
* **shell:** add editor-view model ([358dde4](https://github.com/alibaba/lowcode-engine/commit/358dde43a4a6097abc71fd47e708cca7af105acf))
* support online tree title extra ([778ba32](https://github.com/alibaba/lowcode-engine/commit/778ba32a14d47ba8e57b78de4f815246484e6a6c))
* update modals visible state in outline pane ([c78dd80](https://github.com/alibaba/lowcode-engine/commit/c78dd80c289495799f76709d7dde60b170b3a56e))
* update Outline Tree to Component Tree ([82d82b9](https://github.com/alibaba/lowcode-engine/commit/82d82b9d0596f75080d4bde1bfea5ef86a47ad19))
* update the ts definition of the shell module ([9cec5d8](https://github.com/alibaba/lowcode-engine/commit/9cec5d833c224665bd41f74b20b9014327c6abfa))
* use "ric-shim" replace "window.requestIdleCallback" fix [#829](https://github.com/alibaba/lowcode-engine/issues/829) ([80be82a](https://github.com/alibaba/lowcode-engine/commit/80be82af6a4db316a0171ef75c13900a5c782aad))
* workspace window add onSave api ([b984ef7](https://github.com/alibaba/lowcode-engine/commit/b984ef72d28f98a6e7a72ea3d051dc254f402749))
* 大纲树支持节点过滤 ([f30db20](https://github.com/alibaba/lowcode-engine/commit/f30db20606f5f2fdac0017305b1dda7ab2258c4b))
* 梳理 api 中 model 相关文档, 优化相关 api 实现 ([8d2fe15](https://github.com/alibaba/lowcode-engine/commit/8d2fe15a3f64f05853867137872c20de31cbe79b))

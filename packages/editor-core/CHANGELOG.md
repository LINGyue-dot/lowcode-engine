# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.4.1](https://github.com/alibaba/lowcode-engine/compare/v1.4.0...v1.4.1) (2025-10-17)

**Note:** Version bump only for package @epoch/lowcode-editor-core





# 1.4.0 (2025-10-17)


### Bug Fixes

* 🐛 修复数据源引擎请求处理器映射严格模式下被过滤的问题 ([75626d8](https://github.com/alibaba/lowcode-engine/commit/75626d877db017b8862b1d5e64d75f3af7ff667a))
* componentList in remote component desc not written into asset ([29b9184](https://github.com/alibaba/lowcode-engine/commit/29b91846fb22f01a94b6f1be282b93095eeb6403))
* declare parameter appHelper for valid engine options ([058a842](https://github.com/alibaba/lowcode-engine/commit/058a84226af8ca19d8c7d63599d80d0cdf70281c))
* designer/loadIncrementalAssets await Sequential ([#841](https://github.com/alibaba/lowcode-engine/issues/841)) ([8232424](https://github.com/alibaba/lowcode-engine/commit/823242469743d235923b3b946ec7d2db70887ead))
* fix lint issues in shell ([8537eff](https://github.com/alibaba/lowcode-engine/commit/8537eff8934490e037cc33cc9889e2dfb119c720))
* fix misused doc urls ([16a8857](https://github.com/alibaba/lowcode-engine/commit/16a88578634b9da2f04698df5ca5a5e69151bb97))
* fix monitor utils incorrect assignment method ([bf280c6](https://github.com/alibaba/lowcode-engine/commit/bf280c6fa1e46d084fc8f20323164816fad4076f))
* fix setter hooks error ([8a3a0b8](https://github.com/alibaba/lowcode-engine/commit/8a3a0b824162e25a930711c6fef511b4b369e897))
* fix tooltip being covered by other elements ([#1717](https://github.com/alibaba/lowcode-engine/issues/1717)) ([95a1137](https://github.com/alibaba/lowcode-engine/commit/95a1137b466b73d7dabe9a453e2016bd0c51322c))
* fix workspace api ts defined ([6d4ca29](https://github.com/alibaba/lowcode-engine/commit/6d4ca29466640164082274ea791ae2055136c3f9))
* fixed focusNodeSelector configuration not taking effect ([9beae9c](https://github.com/alibaba/lowcode-engine/commit/9beae9c3269901bf03a29033121c7d480571bce5))
* make insertAfter & insertBefore work ([70fd372](https://github.com/alibaba/lowcode-engine/commit/70fd3720d098d6e227acb9281ee22feee66b9c0b))
* **material:** when the assets exist, use onChangeAssets api, the callback is called immediately ([c458b1b](https://github.com/alibaba/lowcode-engine/commit/c458b1b2ec657d98d60638678fe718ea0e908820))
* missing engine options config info ([9ccded0](https://github.com/alibaba/lowcode-engine/commit/9ccded006ef44cd538abaa140250e519243bf090))
* remove as Type ([5d042dd](https://github.com/alibaba/lowcode-engine/commit/5d042dd53371ed01fe9b3e8b32fdaf952e167f83))


### Features

* 🎸 设计态支持数据源引擎配置 ([04631f8](https://github.com/alibaba/lowcode-engine/commit/04631f813782dbf6d175f51c40ccc75ca4c099d2))
* add commonUI API ([be0456f](https://github.com/alibaba/lowcode-engine/commit/be0456fb398c731c4492fbca83aebc8ed9e9f3f3))
* add config.workspaceEmptyComponent ([aa1bb1c](https://github.com/alibaba/lowcode-engine/commit/aa1bb1c0d720d972e64049f92358456b14069310))
* add createIntl to common.utils, and fix misuse of zh_CN ([84e0c1f](https://github.com/alibaba/lowcode-engine/commit/84e0c1f09609d81716274af2f94c676e68ab8f15))
* add hideComponentAction config ([c24c3d8](https://github.com/alibaba/lowcode-engine/commit/c24c3d8ae59e4ee9cf17c5816f088463aedb5a44))
* add hotkey in workspace plugins ([8414425](https://github.com/alibaba/lowcode-engine/commit/841442574080d6399d549a1a974c71d5b4a572f0))
* add shell config model ([b319286](https://github.com/alibaba/lowcode-engine/commit/b319286c4896e34844e6f21a552874f0f70d0742))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add some features ([18d1a4f](https://github.com/alibaba/lowcode-engine/commit/18d1a4fe1d952bcd4715e693def09fee94da49a5))
* add theme color document & optimize some theme colors ([79b9a6e](https://github.com/alibaba/lowcode-engine/commit/79b9a6efa57d1a30559ea8476bbb380b5957d968))
* add types for engineConfig and put it to types ([5de97c1](https://github.com/alibaba/lowcode-engine/commit/5de97c10c8b308ebb63040f385853c8fa5c1bcaa))
* add types for shell, and move functions in types to utils ([55c3fc9](https://github.com/alibaba/lowcode-engine/commit/55c3fc9e58d566edeabd1daa489ac83ba6b787d1))
* added thisRequiredInJSE API to control whether JSExpression expression access context must use this ([#702](https://github.com/alibaba/lowcode-engine/issues/702)) ([da7f77e](https://github.com/alibaba/lowcode-engine/commit/da7f77ee91b3bf441a4a57614872df32d6a1d041))
* assets.components support reference field ([#1355](https://github.com/alibaba/lowcode-engine/issues/1355)) ([f9dcbaf](https://github.com/alibaba/lowcode-engine/commit/f9dcbaf61824df2a1901758d3ef15e6a1b865be5))
* **command:** add command apis ([b3880e9](https://github.com/alibaba/lowcode-engine/commit/b3880e9a96c70d750f8f8487913bf6329cdcfb92))
* **common-ui:** add HelpTip ([ce72fc1](https://github.com/alibaba/lowcode-engine/commit/ce72fc1b16912312ab9fb2a38bba811dbea7ef13))
* **common:** add common.utils.intl API ([a7d3996](https://github.com/alibaba/lowcode-engine/commit/a7d3996fa2eaccd883eb554677d6c15af6134978))
* **engine:** add context menu ([1b00c61](https://github.com/alibaba/lowcode-engine/commit/1b00c61a32027084e531a0ffacb2a9a2020fbcbf))
* **event:** add event.prependListener api ([f7c1f1e](https://github.com/alibaba/lowcode-engine/commit/f7c1f1e716c855c3e8725cb5acd4ea124a841713))
* export nodeChildrenSymbol && remove some unnecessary editor.set ([e83adce](https://github.com/alibaba/lowcode-engine/commit/e83adcee815eea73b6b1ed4f43f4d684c11818ca))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* mark the loaded remote description descriptions to reduce loading ([a389ec1](https://github.com/alibaba/lowcode-engine/commit/a389ec184ce88cac229a2e9129103ec8a6f0e367))
* pass e to customizeIgnoreSelectors ([900b239](https://github.com/alibaba/lowcode-engine/commit/900b2394323e85f0dce5df83dfc773f96da23e24))
* removed Rax packages, discontinuing support for Rax ([31a031c](https://github.com/alibaba/lowcode-engine/commit/31a031ce4e4cc22c377aa9d1ce961c5df4cad58b))
* requestHandlersMap should be optional ([ee7160e](https://github.com/alibaba/lowcode-engine/commit/ee7160ea3c625d421c07730ef51711b8f14392a0))
* **setter:** add field ts ([6e89d4d](https://github.com/alibaba/lowcode-engine/commit/6e89d4d605760d376fedf350b99f24bc11770ec5))
* support for hiding settings tabs when there is only one item ([#669](https://github.com/alibaba/lowcode-engine/issues/669)) ([cbd95a1](https://github.com/alibaba/lowcode-engine/commit/cbd95a1778415406670f37507ce957af6b3ecd4a))
* support for NotFoundComponent design state is optional ([#1013](https://github.com/alibaba/lowcode-engine/issues/1013)) ([d3c891e](https://github.com/alibaba/lowcode-engine/commit/d3c891e2a46d138e31c81a7f9b804a8240154df5))
* support PanelDock icon pointer cursor is always pointer ([a645af7](https://github.com/alibaba/lowcode-engine/commit/a645af7e0b0ce439548f5573102d8c22f35c4fc0))
* support the use of events in workspace mode to communicate in different views ([163416f](https://github.com/alibaba/lowcode-engine/commit/163416fcfe291e133551cd75e484cc3ea6d0edc8))
* sync utils/constants ([#506](https://github.com/alibaba/lowcode-engine/issues/506)) ([2871b5b](https://github.com/alibaba/lowcode-engine/commit/2871b5ba4c3dbf1ed76bf4d6359fb457190a9b22))
* update setter types ([aab8a3a](https://github.com/alibaba/lowcode-engine/commit/aab8a3a10ec1612164de76aec81f196d5e395dc5))
* update skeleton ts defined ([21f74f0](https://github.com/alibaba/lowcode-engine/commit/21f74f0cc1566c0a69b7420f3603b16cd8331931))
* workspace add some features ([ee80fb1](https://github.com/alibaba/lowcode-engine/commit/ee80fb12b864f2ddd657fe1503e57f755697d07a))
* **workspace:** add enableAutoOpenFirstWindow config and onWindowRendererReady function ([9b50bc7](https://github.com/alibaba/lowcode-engine/commit/9b50bc700e18e02d590d7a77591809cdbad8a160))
* **workspace:** add multi foces-tracker in workspace mode ([7b61817](https://github.com/alibaba/lowcode-engine/commit/7b6181719e28b3b56e71f84266a550d14f8d9bba))
* 大纲树支持节点过滤 ([f30db20](https://github.com/alibaba/lowcode-engine/commit/f30db20606f5f2fdac0017305b1dda7ab2258c4b))

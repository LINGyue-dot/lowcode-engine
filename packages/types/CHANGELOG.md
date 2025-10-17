# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.4.1](https://github.com/alibaba/lowcode-engine/compare/v1.4.0...v1.4.1) (2025-10-17)

**Note:** Version bump only for package @epoch/lowcode-types





# 1.4.0 (2025-10-17)


### Bug Fixes

* attr name in IPublicTypePanelDockConfig should not be optional ([9a68f0f](https://github.com/alibaba/lowcode-engine/commit/9a68f0f27c062b637ace824eca7ccaa6ed9573b6))
* **canvas:** clipboard init error ([adb9f6b](https://github.com/alibaba/lowcode-engine/commit/adb9f6b090a71052ece0b10d3b6e48125c8799e8))
* change autorun params to IPublicModelSettingField ([4f7a0b9](https://github.com/alibaba/lowcode-engine/commit/4f7a0b984c50b133807352a953437dcac757fa40))
* change the return result type to Promise ([a1a50f2](https://github.com/alibaba/lowcode-engine/commit/a1a50f25704a56e045d6d645eea4179c25ee60ac))
* compatible with SlotSchema which doesn't have title / name / params ([3fe9882](https://github.com/alibaba/lowcode-engine/commit/3fe9882f9d5ef9302ee0265facb26ba1e58cccad))
* **context-menu:** fix context menu bugs ([c381b85](https://github.com/alibaba/lowcode-engine/commit/c381b85f0a48b215414e72c76864aa8b435fd443))
* designer/loadIncrementalAssets await Sequential ([#841](https://github.com/alibaba/lowcode-engine/issues/841)) ([8232424](https://github.com/alibaba/lowcode-engine/commit/823242469743d235923b3b946ec7d2db70887ead))
* error when dragging in outline view ([b7d32fe](https://github.com/alibaba/lowcode-engine/commit/b7d32fe8a1943a80915427eddd7af6cb5f9b342b))
* fix composeTitle returns redundant icons ([ed252fa](https://github.com/alibaba/lowcode-engine/commit/ed252fa13577301c4d66ed7cb54959874c21981f))
* fix lint issues in shell ([8537eff](https://github.com/alibaba/lowcode-engine/commit/8537eff8934490e037cc33cc9889e2dfb119c720))
* fix misused doc urls ([16a8857](https://github.com/alibaba/lowcode-engine/commit/16a88578634b9da2f04698df5ca5a5e69151bb97))
* fix onChangeNodeVisible & onChangeNodeChildren cannot be triggered successfully in some cases ([9444752](https://github.com/alibaba/lowcode-engine/commit/9444752a65d20b7a514a271236620d32b10aa796))
* fix setter hooks error ([8a3a0b8](https://github.com/alibaba/lowcode-engine/commit/8a3a0b824162e25a930711c6fef511b4b369e897))
* fix some ts error ([d8014c9](https://github.com/alibaba/lowcode-engine/commit/d8014c9d1ab310317ad6fafb8fbba2c475d0491d))
* fix the problem of crash caused by infinite loop in antd scene ([73acf6f](https://github.com/alibaba/lowcode-engine/commit/73acf6f112de22feb0ccea8033e6adf3b25c0e4b))
* fix the problem that the props value appears when the name is 0 ([affdfbb](https://github.com/alibaba/lowcode-engine/commit/affdfbbb1cc336361b26be6ffb043bbec6017164))
* fix ts error ([4433b2e](https://github.com/alibaba/lowcode-engine/commit/4433b2ee78590e39113efa22044ffe10154d5c8c))
* fix workspace api ts defined ([6d4ca29](https://github.com/alibaba/lowcode-engine/commit/6d4ca29466640164082274ea791ae2055136c3f9))
* lerna version to 4.0.0 ([731dc58](https://github.com/alibaba/lowcode-engine/commit/731dc58649ffa68a528c7b97e770f03e4252c2c8))
* **lowcode-types:** allow `template` field in supports.events ([0dc8120](https://github.com/alibaba/lowcode-engine/commit/0dc8120f80b50e0f2cff9bea1de21f036b54bc53))
* make isJSExpression more robust ([01ce70c](https://github.com/alibaba/lowcode-engine/commit/01ce70c06c2d7a3a71d62fe01639638918f53641))
* **material:** when the assets exist, use onChangeAssets api, the callback is called immediately ([c458b1b](https://github.com/alibaba/lowcode-engine/commit/c458b1b2ec657d98d60638678fe718ea0e908820))
* project.exportSchema should export componentsMap of all documents ([969a130](https://github.com/alibaba/lowcode-engine/commit/969a130b373fb028f8051e96cb9d79f1de0a2a1c))
* remove as Type ([5d042dd](https://github.com/alibaba/lowcode-engine/commit/5d042dd53371ed01fe9b3e8b32fdaf952e167f83))
* **shell/model:** fix lint issues in shell/model ([4fd3af1](https://github.com/alibaba/lowcode-engine/commit/4fd3af10c5b0e444b3cfb9758ee022cfcff96f7a))
* solve ut failure for code-generator ([becdfec](https://github.com/alibaba/lowcode-engine/commit/becdfecd5ab2410ee48bcbfbb137aaf41668a441))
* **types:** fix lint issues for node-children, and optimize related docs ([02b4a5e](https://github.com/alibaba/lowcode-engine/commit/02b4a5eaa9e1ae48b9f37a94d8c35ecb22345b4f))
* **types:** rrror declaration of the children prop ([951d1cb](https://github.com/alibaba/lowcode-engine/commit/951d1cb103fa46c0e7926d6138657c7d10cc4f88))
* when the component is configured in a loop, the key value changes and renders error ([5db418e](https://github.com/alibaba/lowcode-engine/commit/5db418efe41f8421a644d54926db6ce8d2164eed))


### Features

* add APIs for plugin-outline-pane which will be splitted in near future ([7b58b6a](https://github.com/alibaba/lowcode-engine/commit/7b58b6a6d755395ba80f4857d617a0d3841084f1))
* add common.utils.executeTransaction API to change multi nodes ([e818d84](https://github.com/alibaba/lowcode-engine/commit/e818d84c8b22ae112498e5b2bf419dc07b91fc29))
* add commonUI API ([be0456f](https://github.com/alibaba/lowcode-engine/commit/be0456fb398c731c4492fbca83aebc8ed9e9f3f3))
* add componentMeta?.advanced?.callbacks?.onSelectHook api ([03495ba](https://github.com/alibaba/lowcode-engine/commit/03495ba9efd2c7b950b52756022c2ca2807dc085))
* add document-model shell return types ([cb2e050](https://github.com/alibaba/lowcode-engine/commit/cb2e05046f417422d9da98a9e255e9f49a895d6d))
* add get advanced api for ComponentMeta ([810ccbd](https://github.com/alibaba/lowcode-engine/commit/810ccbd03ef6ce5e4159c3e52aa7efad7073a67e))
* add getDOMNode api definition in node module ([9648331](https://github.com/alibaba/lowcode-engine/commit/964833128b92aafe3266f5096b3d83e7af261372))
* add hideComponentAction config ([c24c3d8](https://github.com/alibaba/lowcode-engine/commit/c24c3d8ae59e4ee9cf17c5816f088463aedb5a44))
* add IPublicTypeSkeletonConfig type ([0eac230](https://github.com/alibaba/lowcode-engine/commit/0eac230905e153e8fc43231eb6417efed69e5b83))
* add resource layer layout in workspace mode ([6482609](https://github.com/alibaba/lowcode-engine/commit/6482609ac140b62ddd2b0469f187e0b9b775583b))
* add reverse api to node-children model ([1f09b63](https://github.com/alibaba/lowcode-engine/commit/1f09b639fb8b4f7be897aef2649e1f44f191a20a))
* add setConfig method for project ([3d51fe0](https://github.com/alibaba/lowcode-engine/commit/3d51fe00bfced9af6f06cd6defdb67e3ebc76e3f))
* add shell config model ([b319286](https://github.com/alibaba/lowcode-engine/commit/b319286c4896e34844e6f21a552874f0f70d0742))
* add simulatorRender shell ([cfc22f7](https://github.com/alibaba/lowcode-engine/commit/cfc22f7ecc666ae8258013634c3aa17958299b90))
* add skeleton item model ([239bb29](https://github.com/alibaba/lowcode-engine/commit/239bb29de1853c87f687a4355df76179a09d5ae5))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add types for engineConfig and put it to types ([5de97c1](https://github.com/alibaba/lowcode-engine/commit/5de97c10c8b308ebb63040f385853c8fa5c1bcaa))
* add types for shell, and move functions in types to utils ([55c3fc9](https://github.com/alibaba/lowcode-engine/commit/55c3fc9e58d566edeabd1daa489ac83ba6b787d1))
* added apis support resource tree in workspace mode ([ea08173](https://github.com/alibaba/lowcode-engine/commit/ea08173af0b40d1af90c0445328614c000696682))
* added detailed definition of some skeleton.add parameters ([c905aa2](https://github.com/alibaba/lowcode-engine/commit/c905aa27c3ace6e756987d1437f8086c4d8fa0a3))
* added export of propSymbol and prop classes ([0e18fee](https://github.com/alibaba/lowcode-engine/commit/0e18feeb6e551010eff1d07bbd557971e3086970))
* added features in workspace mode ([33fd6bf](https://github.com/alibaba/lowcode-engine/commit/33fd6bf6426f3300a1e95c80b3021fed26656872))
* added onChangeViewType event to window model ([0184dcd](https://github.com/alibaba/lowcode-engine/commit/0184dcd9384a3145dff92e96bca2de414c02d99d))
* added workspace api to support registration of multiple resources ([dae09e3](https://github.com/alibaba/lowcode-engine/commit/dae09e3bcb21b420a88a5e5256320ad50ab1ac2d))
* assets.components support reference field ([#1355](https://github.com/alibaba/lowcode-engine/issues/1355)) ([f9dcbaf](https://github.com/alibaba/lowcode-engine/commit/f9dcbaf61824df2a1901758d3ef15e6a1b865be5))
* canvas.activeTracker add targer prop ([2b3d96c](https://github.com/alibaba/lowcode-engine/commit/2b3d96cedada3f3c3f91f16129aadee466052b9b))
* canvas.activeTracker.target returns add null ([62288a1](https://github.com/alibaba/lowcode-engine/commit/62288a139f6fc550e91c9ffbf0cc7fc1c6e64188))
* **command:** add command apis ([b3880e9](https://github.com/alibaba/lowcode-engine/commit/b3880e9a96c70d750f8f8487913bf6329cdcfb92))
* **command:** update default commands ([80bb710](https://github.com/alibaba/lowcode-engine/commit/80bb7102b65ccfc24399e372cff5f3fbaf8258a4))
* **common-ui:** add HelpTip ([ce72fc1](https://github.com/alibaba/lowcode-engine/commit/ce72fc1b16912312ab9fb2a38bba811dbea7ef13))
* **common:** add common.utils.intl API ([a7d3996](https://github.com/alibaba/lowcode-engine/commit/a7d3996fa2eaccd883eb554677d6c15af6134978))
* **context-menu:** add context-menu css theme, help config, ts define ([844ca78](https://github.com/alibaba/lowcode-engine/commit/844ca783d720e5d8829a8e8e54314c97997ec275))
* **engine:** add context menu ([1b00c61](https://github.com/alibaba/lowcode-engine/commit/1b00c61a32027084e531a0ffacb2a9a2020fbcbf))
* **event:** add event.prependListener api ([f7c1f1e](https://github.com/alibaba/lowcode-engine/commit/f7c1f1e716c855c3e8725cb5acd4ea124a841713))
* extract simulator type ([980957f](https://github.com/alibaba/lowcode-engine/commit/980957f3adabaef76fd7e42a9162661904f4db36))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* fix designer:entry ts errors ([4d4a8a6](https://github.com/alibaba/lowcode-engine/commit/4d4a8a6d6f94bfcfe9af0409a3a54b22a89f2d26))
* fix prop module issue and ts type definition ([7c16bb1](https://github.com/alibaba/lowcode-engine/commit/7c16bb1f9cc08be8d1a40ae2e694f1d3a68a20ff))
* lowCode components support project schema ([f6537f5](https://github.com/alibaba/lowcode-engine/commit/f6537f536f965ebffb2af50c99d1147f7276373d))
* make asset support es module ([d56ed6b](https://github.com/alibaba/lowcode-engine/commit/d56ed6bff172f3833f5321073310fac5d54bd247))
* material spec add ignoreDefaultValue field to component property description ([9597b1c](https://github.com/alibaba/lowcode-engine/commit/9597b1c3768699c7de90359156e713b2bf474a31))
* **material:** material apis add refreshComponentMetasMap function ([aef10fc](https://github.com/alibaba/lowcode-engine/commit/aef10fca0dc73b99ebea76d51ea5dd3d719604ee))
* modify the usage of resource registration ([7d526d1](https://github.com/alibaba/lowcode-engine/commit/7d526d1e836356cc820a7c9aca5981929ced0793))
* **node:** add getRGL api ([857685a](https://github.com/alibaba/lowcode-engine/commit/857685a3b412c0155a22f1da4c0a95138544df0b))
* optimize outline tree performance and ts definition ([eeb6719](https://github.com/alibaba/lowcode-engine/commit/eeb6719a1ff1defff3b91a2f1455d0b7daaa252d))
* optimize ts definition ([88961aa](https://github.com/alibaba/lowcode-engine/commit/88961aa6409c52ebd7af67efd5134baf3c8ab424))
* optimized lowcode types ([122f0b3](https://github.com/alibaba/lowcode-engine/commit/122f0b30a03a34f07ab5e748011ba6cb0cad4ecc))
* plugin add get\getAll\has\delete api ([0a24273](https://github.com/alibaba/lowcode-engine/commit/0a2427354b447a6c479ee950548b49b868cce1ab))
* remove IPublicTypeFieldExtraProps.virtual definition ([5738394](https://github.com/alibaba/lowcode-engine/commit/5738394a2e04d44e4b1d3db6b6b314b17699334a))
* removed Rax packages, discontinuing support for Rax ([31a031c](https://github.com/alibaba/lowcode-engine/commit/31a031ce4e4cc22c377aa9d1ce961c5df4cad58b))
* **setter:** add field ts ([6e89d4d](https://github.com/alibaba/lowcode-engine/commit/6e89d4d605760d376fedf350b99f24bc11770ec5))
* **shell:** add editor-view model ([358dde4](https://github.com/alibaba/lowcode-engine/commit/358dde43a4a6097abc71fd47e708cca7af105acf))
* skeleton item add visible prop ([e578f82](https://github.com/alibaba/lowcode-engine/commit/e578f82272affec3871b580ad68787c55da0dab0))
* **skeleton:** add onDisableWidget & onEnableWidget APIs ([e79f686](https://github.com/alibaba/lowcode-engine/commit/e79f68611a4779e30a9bd455dd1d8e20275823f6))
* **skeleton:** add registerConfigTransducer API ([a3fef9c](https://github.com/alibaba/lowcode-engine/commit/a3fef9c13d39ac1b35b200cf0f711cf7c7c233d8))
* **skeleton:** add skeleton.getPanel api ([0eeee1f](https://github.com/alibaba/lowcode-engine/commit/0eeee1feee3268ca5f970250fda1cfb52725191f))
* **skeleton:** Add TS defs for modules & optimize Tabs display with array contents ([16713f4](https://github.com/alibaba/lowcode-engine/commit/16713f4b848f3648fa93c82d70007fbec4e8a816))
* support PanelDock icon pointer cursor is always pointer ([a645af7](https://github.com/alibaba/lowcode-engine/commit/a645af7e0b0ce439548f5573102d8c22f35c4fc0))
* support webview type resource in workspace mode ([36d1d3b](https://github.com/alibaba/lowcode-engine/commit/36d1d3bef1d613c06219bab63e578d1939da1c56))
* the advanced.autoruns parameter uses a shell wrapper ([5cf3959](https://github.com/alibaba/lowcode-engine/commit/5cf395957cd2079b103426967b4446813883f8ff))
* the event supplements the dispose function as the return value ([69ab81a](https://github.com/alibaba/lowcode-engine/commit/69ab81a14719db266723b185de46a7047890a11a))
* **types:** add IPublicTypeInstanceOf to prop-types ([9108e8c](https://github.com/alibaba/lowcode-engine/commit/9108e8cfabdb442064f43be0533538ebbaff7f4a))
* update IPublicTypeComponentMetadata interface ([3fea312](https://github.com/alibaba/lowcode-engine/commit/3fea312906686f2c6d79da9e9f6e9a27c99a7896))
* update props ts defined ([8c073c3](https://github.com/alibaba/lowcode-engine/commit/8c073c3c95585ea426d28dbe43d9b58021b74115))
* update setter types ([aab8a3a](https://github.com/alibaba/lowcode-engine/commit/aab8a3a10ec1612164de76aec81f196d5e395dc5))
* update skeleton ts defined ([21f74f0](https://github.com/alibaba/lowcode-engine/commit/21f74f0cc1566c0a69b7420f3603b16cd8331931))
* update the ts definition of the shell module ([9cec5d8](https://github.com/alibaba/lowcode-engine/commit/9cec5d833c224665bd41f74b20b9014327c6abfa))
* update ts defined ([de95b87](https://github.com/alibaba/lowcode-engine/commit/de95b87b1e2ef1a7bd90b52e7f3cf8ca22a5f999))
* update types define ([4d03610](https://github.com/alibaba/lowcode-engine/commit/4d03610fd3b6d056fa7ce35f127cf7a90f99dd6c))
* **utils|types:** add esmodule support for component meta resources ([#2603](https://github.com/alibaba/lowcode-engine/issues/2603)) ([e3611dc](https://github.com/alibaba/lowcode-engine/commit/e3611dcf06a0a24b691fab00734ce4cecb501f25))
* **utils:** add workspace utils ([ad044f4](https://github.com/alibaba/lowcode-engine/commit/ad044f49ed9064fe1afa5195f68759a76bda5f5e))
* when field rendering error, output error log ([14d294c](https://github.com/alibaba/lowcode-engine/commit/14d294c92c662d00350e87d8cf6ec57beee325f6))
* workspace add some features ([ee80fb1](https://github.com/alibaba/lowcode-engine/commit/ee80fb12b864f2ddd657fe1503e57f755697d07a))
* workspace mode supports webview type views ([1f8d91f](https://github.com/alibaba/lowcode-engine/commit/1f8d91f85f2e98d39b1a7a571310af1112998f75))
* workspace window add onSave api ([b984ef7](https://github.com/alibaba/lowcode-engine/commit/b984ef72d28f98a6e7a72ea3d051dc254f402749))
* **workspace:** add config for resource shell model ([c3d75b2](https://github.com/alibaba/lowcode-engine/commit/c3d75b27da5c9f1b800d2aee4befc30477b16a29))
* **workspace:** add editorViews to resourceTypeList api ([c838dc7](https://github.com/alibaba/lowcode-engine/commit/c838dc70eb71e4aaae37494baf7f3a1d3fec8340))
* **workspace:** add enableAutoOpenFirstWindow config and onWindowRendererReady function ([9b50bc7](https://github.com/alibaba/lowcode-engine/commit/9b50bc700e18e02d590d7a77591809cdbad8a160))
* **workspace:** add resourceTypeList api ([#2148](https://github.com/alibaba/lowcode-engine/issues/2148)) ([dc029c2](https://github.com/alibaba/lowcode-engine/commit/dc029c252a5a135ffbce17c66040f72ea4b7fe00))
* **workspace:** resource supports the init lifecycle and initializes plugins ([0d388a3](https://github.com/alibaba/lowcode-engine/commit/0d388a30766c556c5fe3abc57a6db4322b0588c9))
* **workspace:** update openEditorWindow api ([899ffa1](https://github.com/alibaba/lowcode-engine/commit/899ffa15541164c31e2e3688344639046df282ec))
* **workspace:** update removeEditorWindow api ([547bbf4](https://github.com/alibaba/lowcode-engine/commit/547bbf4ddc0377c15f3e348d49d86eaa49de17ca))
* 梳理 api 中 model 相关文档, 优化相关 api 实现 ([8d2fe15](https://github.com/alibaba/lowcode-engine/commit/8d2fe15a3f64f05853867137872c20de31cbe79b))
* 资产包支持一个package从另一个package异步导出 ([#1150](https://github.com/alibaba/lowcode-engine/issues/1150)) ([8a83fc9](https://github.com/alibaba/lowcode-engine/commit/8a83fc9b5c0bca17bc3be5f1d7907ce5c886999d))





## [1.0.55](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.54...v1.0.55) (2021-06-17)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.54](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.53...v1.0.54) (2021-06-08)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.53](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.52...v1.0.53) (2021-06-07)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.52](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.51...v1.0.52) (2021-06-07)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.51](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.49...v1.0.51) (2021-06-03)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.49](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.48...v1.0.49) (2021-05-20)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.48](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.48-beta.4...v1.0.48) (2021-05-17)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.48-beta.4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.48-beta.3...v1.0.48-beta.4) (2021-05-14)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.48-beta.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.48-beta.2...v1.0.48-beta.3) (2021-05-13)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.48-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.48-beta.1...v1.0.48-beta.2) (2021-05-12)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.48-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.48-beta.0...v1.0.48-beta.1) (2021-05-12)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.48-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.47...v1.0.48-beta.0) (2021-05-11)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.47](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.47-beta.1...v1.0.47) (2021-04-28)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.47-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.47-beta.0...v1.0.47-beta.1) (2021-04-28)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.47-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.46...v1.0.47-beta.0) (2021-04-28)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.46](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.46-beta.0...v1.0.46) (2021-04-27)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.46-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.45...v1.0.46-beta.0) (2021-04-25)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.45](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.45-beta.1...v1.0.45) (2021-04-23)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.45-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.45-beta.0...v1.0.45-beta.1) (2021-04-22)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.45-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.44...v1.0.45-beta.0) (2021-04-21)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.44](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.44-beta.2...v1.0.44) (2021-04-14)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.44-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.44-beta.1...v1.0.44-beta.2) (2021-04-14)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.44-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.44-beta.0...v1.0.44-beta.1) (2021-04-14)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.44-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.43...v1.0.44-beta.0) (2021-04-13)


### Bug Fixes

* componentsMap 中加入低代码组件信息 ([b7c1183](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/b7c11834602d8e4ea84d2dea035a3abf97b33d5c))





## [1.0.43](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.43-beta.0...v1.0.43) (2021-04-13)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.43-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.42...v1.0.43-beta.0) (2021-04-13)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.42](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.42-beta.1...v1.0.42) (2021-04-06)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.42-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.42-beta.0...v1.0.42-beta.1) (2021-04-06)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.42-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.41...v1.0.42-beta.0) (2021-04-06)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.41](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.41-beta.1...v1.0.41) (2021-04-06)


### Bug Fixes

* bypass dataSource ([3cb331d](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/3cb331dcbeee62959ef0b1614c6c3cb2bd3c1a3e))





## [1.0.41-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.41-beta.1...v1.0.41-beta.2) (2021-04-06)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.41-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.41-beta.0...v1.0.41-beta.1) (2021-04-06)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.41-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.40...v1.0.41-beta.0) (2021-04-02)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.40](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.40-beta.1...v1.0.40) (2021-03-31)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.40-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.40-beta.0...v1.0.40-beta.1) (2021-03-31)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.40-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.39-beta.5...v1.0.40-beta.0) (2021-03-31)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.39-beta.5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.39-beta.4...v1.0.39-beta.5) (2021-03-31)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.39-beta.4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.39-beta.3...v1.0.39-beta.4) (2021-03-30)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.39-beta.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.39-beta.2...v1.0.39-beta.3) (2021-03-22)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.39-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.39-beta.1...v1.0.39-beta.2) (2021-03-22)


### Bug Fixes

* renderer-core 在非设计渲染态时, 不应处理 hidden 属性 ([7857096](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7857096c0f56308195cc9e27de4f549eee72a10e))





## [1.0.39-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.38-beta.3...v1.0.39-beta.1) (2021-03-12)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.39-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.38-beta.3...v1.0.39-beta.0) (2021-03-12)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.38-beta.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.38-beta.1...v1.0.38-beta.3) (2021-03-11)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.38-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.38-beta.1...v1.0.38-beta.2) (2021-03-11)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.38-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.38-beta.0...v1.0.38-beta.1) (2021-03-09)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.38-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37...v1.0.38-beta.0) (2021-03-08)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.37](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.6...v1.0.37) (2021-03-05)

**Note:** Version bump only for package @ali/lowcode-types







**Note:** Version bump only for package @ali/lowcode-types





## [1.0.37](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.6...v1.0.37) (2021-03-05)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.37-beta.6](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.3...v1.0.37-beta.6) (2021-03-03)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.37-beta.5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.4...v1.0.37-beta.5) (2021-02-24)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.37-beta.4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.3...v1.0.37-beta.4) (2021-02-24)

**Note:** Version bump only for package @ali/lowcode-types





## [1.0.37-beta.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.2...v1.0.37-beta.3) (2021-02-24)

**Note:** Version bump only for package @ali/lowcode-types





<a name="1.0.37-beta.2"></a>
## [1.0.37-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.37-beta.1...v1.0.37-beta.2) (2021-02-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.37-beta.1"></a>
## [1.0.37-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.36...v1.0.37-beta.1) (2021-02-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.36"></a>
## [1.0.36](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.36-beta.0...v1.0.36) (2021-02-04)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.36-beta.0"></a>
## [1.0.36-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.35...v1.0.36-beta.0) (2021-02-04)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.35"></a>
## [1.0.35](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.35-beta.1...v1.0.35) (2021-02-03)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.35-beta.1"></a>
## [1.0.35-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.35-beta.0...v1.0.35-beta.1) (2021-02-03)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.35-beta.0"></a>
## [1.0.35-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.33...v1.0.35-beta.0) (2021-02-01)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.33"></a>
## [1.0.33](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.33-beta.1...v1.0.33) (2021-01-29)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.33-beta.1"></a>
## [1.0.33-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.33-beta.0...v1.0.33-beta.1) (2021-01-28)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.33-beta.0"></a>
## [1.0.33-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.32...v1.0.33-beta.0) (2021-01-28)


### Bug Fixes

* 修复从其他页面粘贴过来的 modal 位置不对 ([158b6a6](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/158b6a6))




<a name="1.0.32"></a>
## [1.0.32](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.32-beta.2...v1.0.32) (2021-01-26)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.32-beta.2"></a>
## [1.0.32-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.32-beta.0...v1.0.32-beta.2) (2021-01-26)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.32-beta.0"></a>
## [1.0.32-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.31...v1.0.32-beta.0) (2021-01-25)


### Features

* meta 增加 hideSelectTools ([e7287d4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/e7287d4))
* metadata 增加 canHovering 配置 ([88e128e](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/88e128e))
* 增加 plugin 的 autoInit 注册方式 ([4f9be73](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/4f9be73))




<a name="1.0.31"></a>
## [1.0.31](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.31-beta.1...v1.0.31) (2021-01-15)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.31-beta.1"></a>
## [1.0.31-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30...v1.0.31-beta.1) (2021-01-15)


### Bug Fixes

* 延迟加载内置 setter ([99cbdd5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/99cbdd5))




<a name="1.0.31-beta.0"></a>
## [1.0.31-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30...v1.0.31-beta.0) (2021-01-15)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30"></a>
## [1.0.30](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.17...v1.0.30) (2021-01-14)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.17"></a>
## [1.0.30-beta.17](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.16...v1.0.30-beta.17) (2021-01-14)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.16"></a>
## [1.0.30-beta.16](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.14...v1.0.30-beta.16) (2021-01-14)


### Features

* 将 typings 在顶层导出 ([d2aed7d](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/d2aed7d))




<a name="1.0.30-beta.15"></a>
## [1.0.30-beta.15](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.14...v1.0.30-beta.15) (2021-01-13)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.14"></a>
## [1.0.30-beta.14](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.13...v1.0.30-beta.14) (2021-01-13)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.13"></a>
## [1.0.30-beta.13](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.12...v1.0.30-beta.13) (2021-01-13)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.12"></a>
## [1.0.30-beta.12](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.11...v1.0.30-beta.12) (2021-01-13)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.11"></a>
## [1.0.30-beta.11](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.10...v1.0.30-beta.11) (2021-01-12)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.10"></a>
## [1.0.30-beta.10](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.9...v1.0.30-beta.10) (2021-01-12)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.9"></a>
## [1.0.30-beta.9](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.8...v1.0.30-beta.9) (2021-01-11)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.8"></a>
## [1.0.30-beta.8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.7...v1.0.30-beta.8) (2021-01-11)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.7"></a>
## [1.0.30-beta.7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.30-beta.6...v1.0.30-beta.7) (2021-01-11)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.30-beta.6"></a>
## [1.0.30-beta.6](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.29...v1.0.30-beta.6) (2021-01-09)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.29"></a>
## [1.0.29](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.28-beta.2...v1.0.29) (2021-01-05)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.28-beta.2"></a>
## [1.0.28-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.28-beta.1...v1.0.28-beta.2) (2021-01-04)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.28-beta.1"></a>
## [1.0.28-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.27...v1.0.28-beta.1) (2021-01-04)


### Features

* 🎸 utils 的定义中增加对于 function 类型的支持 ([29b1daf](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/29b1daf))
* 支持新版的 plugin 机制 ([1e8fc63](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/1e8fc63))




<a name="1.0.28-beta.0"></a>
## [1.0.28-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.27...v1.0.28-beta.0) (2021-01-04)


### Features

* 🎸 utils 的定义中增加对于 function 类型的支持 ([29b1daf](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/29b1daf))
* 支持新版的 plugin 机制 ([1e8fc63](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/1e8fc63))




<a name="1.0.27"></a>
## [1.0.27](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.27-beta.2...v1.0.27) (2020-12-24)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.27-beta.2"></a>
## [1.0.27-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.27-beta.1...v1.0.27-beta.2) (2020-12-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.27-beta.1"></a>
## [1.0.27-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.27-beta.0...v1.0.27-beta.1) (2020-12-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.27-beta.0"></a>
## [1.0.27-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.26...v1.0.27-beta.0) (2020-12-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.26"></a>
## [1.0.26](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.26-beta.1...v1.0.26) (2020-12-22)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.26-beta.1"></a>
## [1.0.26-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.26-beta.0...v1.0.26-beta.1) (2020-12-22)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.26-beta.0"></a>
## [1.0.26-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.25-beta.1...v1.0.26-beta.0) (2020-12-22)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.25-beta.1"></a>
## [1.0.25-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.24-beta.4...v1.0.25-beta.1) (2020-12-15)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.24-beta.4"></a>
## [1.0.24-beta.4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.24-beta.3...v1.0.24-beta.4) (2020-12-14)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.24-beta.3"></a>
## [1.0.24-beta.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.24-beta.2...v1.0.24-beta.3) (2020-12-11)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.24-beta.2"></a>
## [1.0.24-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.24-beta.1...v1.0.24-beta.2) (2020-12-10)


### Bug Fixes

* 删除无用代码, 解决 ts 编译报错 ([1f241ea](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/1f241ea))




<a name="1.0.24-beta.1"></a>
## [1.0.24-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.24-beta.0...v1.0.24-beta.1) (2020-12-09)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.24-beta.0"></a>
## [1.0.24-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.23...v1.0.24-beta.0) (2020-12-09)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.23"></a>
## [1.0.23](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.23-beta.2...v1.0.23) (2020-12-08)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.23-beta.5"></a>
## [1.0.23-beta.5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.23-beta.4...v1.0.23-beta.5) (2020-12-08)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.23-beta.4"></a>
## [1.0.23-beta.4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.23-beta.3...v1.0.23-beta.4) (2020-12-08)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.23-beta.3"></a>
## [1.0.23-beta.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.23-beta.2...v1.0.23-beta.3) (2020-12-08)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.23-beta.2"></a>
## [1.0.23-beta.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v1.0.23-beta.1...v1.0.23-beta.2) (2020-12-08)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.23-beta.1"></a>
## [1.0.23-beta.1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-29...v1.0.23-beta.1) (2020-12-07)


### Bug Fixes

* 🐛 use lowcode types ([b11425b](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/b11425b))
* 🐛 根据低代码规范,数据源的配置中isInit和 type 都是有默认值的,所以应该是可选的 ([4baf0b4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/4baf0b4))
* datasource版本错误问题 ([a247878](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/a247878))
* fix test result ([7f6fbe8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7f6fbe8))
* JSExpression 增加 compiled ([9f51e39](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/9f51e39))
* miniAppBuildType config(temp) ([584b4c2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/584b4c2))
* typo of onResizeEnd and remove ([8df5f05](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8df5f05))
* will fetch 按照协议修改 ([b9bf800](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/b9bf800))


### Features

* 🎸 urlParams 类型的数据源不需要 options, 所以 options 改成可选为好 ([8114c6f](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8114c6f))
* 🎸 按照中后台搭建协议规范文档补充 JSFunction 的定义和数据源定义中一些字段 ([8b1d0c7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8b1d0c7))
* 🎸 根据低代码协议文档, 完善UtilsMap的定义 ([7fe4bc0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7fe4bc0))
* 🎸 根据低代码协议文档, 将 BlockSchema 也改成继承自 ContainerSchema ([7901c8e](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7901c8e))
* 🎸 补充规范中定义的 JSFunction 类型 ([9e32525](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/9e32525))
* split datasource types ([fd80698](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/fd80698))
* update datasource engine ([cf3c7db](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/cf3c7db))
* 合入 trunk-vision 代码 ([ea6bc7a](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ea6bc7a))
* 调整 datasource-handlers ([2b9bcb5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/2b9bcb5))




<a name="1.0.23-beta.0"></a>
## [1.0.23-beta.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-29...v1.0.23-beta.0) (2020-12-07)


### Bug Fixes

* 🐛 use lowcode types ([b11425b](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/b11425b))
* 🐛 根据低代码规范,数据源的配置中isInit和 type 都是有默认值的,所以应该是可选的 ([4baf0b4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/4baf0b4))
* datasource版本错误问题 ([a247878](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/a247878))
* fix test result ([7f6fbe8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7f6fbe8))
* JSExpression 增加 compiled ([9f51e39](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/9f51e39))
* miniAppBuildType config(temp) ([584b4c2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/584b4c2))
* typo of onResizeEnd and remove ([8df5f05](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8df5f05))
* will fetch 按照协议修改 ([b9bf800](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/b9bf800))


### Features

* 🎸 urlParams 类型的数据源不需要 options, 所以 options 改成可选为好 ([8114c6f](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8114c6f))
* 🎸 按照中后台搭建协议规范文档补充 JSFunction 的定义和数据源定义中一些字段 ([8b1d0c7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8b1d0c7))
* 🎸 根据低代码协议文档, 完善UtilsMap的定义 ([7fe4bc0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7fe4bc0))
* 🎸 根据低代码协议文档, 将 BlockSchema 也改成继承自 ContainerSchema ([7901c8e](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7901c8e))
* 🎸 补充规范中定义的 JSFunction 类型 ([9e32525](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/9e32525))
* split datasource types ([fd80698](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/fd80698))
* update datasource engine ([cf3c7db](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/cf3c7db))
* 合入 trunk-vision 代码 ([ea6bc7a](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ea6bc7a))
* 调整 datasource-handlers ([2b9bcb5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/2b9bcb5))




<a name="1.0.20"></a>
## [1.0.20](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.19...@ali/lowcode-types@1.0.20) (2020-11-16)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.19"></a>
## [1.0.19](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.18...@ali/lowcode-types@1.0.19) (2020-11-10)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.18"></a>
## [1.0.18](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.17...@ali/lowcode-types@1.0.18) (2020-11-10)


### Bug Fixes

* typo of onResizeEnd and remove ([8df5f05](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8df5f05))




<a name="1.0.17"></a>
## [1.0.17](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.16...@ali/lowcode-types@1.0.17) (2020-11-05)


### Bug Fixes

* datasource版本错误问题 ([a247878](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/a247878))


### Features

* split datasource types ([fd80698](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/fd80698))




<a name="1.0.16"></a>
## [1.0.16](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.15...@ali/lowcode-types@1.0.16) (2020-11-05)
* 低成本方案支持绝对布局容器 ([a6067e8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/a6067e8))



<a name="0.12.1-18"></a>
## [0.12.1-18](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-17...v0.12.1-18) (2020-10-17)



<a name="0.12.1-17"></a>
## [0.12.1-17](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-16...v0.12.1-17) (2020-10-14)



<a name="0.12.1-16"></a>
## [0.12.1-16](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-15...v0.12.1-16) (2020-10-12)



<a name="0.12.1-15"></a>
## [0.12.1-15](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-1...v0.12.1-15) (2020-10-12)



<a name="0.12.1-14"></a>
## [0.12.1-14](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-13...v0.12.1-14) (2020-10-10)



<a name="0.12.1-13"></a>
## [0.12.1-13](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-12...v0.12.1-13) (2020-09-28)



<a name="0.12.1-12"></a>
## [0.12.1-12](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-11...v0.12.1-12) (2020-09-28)



<a name="0.12.1-11"></a>
## [0.12.1-11](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-10...v0.12.1-11) (2020-09-27)



<a name="0.12.1-10"></a>
## [0.12.1-10](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-9...v0.12.1-10) (2020-09-27)



<a name="0.12.1-9"></a>
## [0.12.1-9](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-8...v0.12.1-9) (2020-09-27)



<a name="0.12.1-8"></a>
## [0.12.1-8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-7...v0.12.1-8) (2020-09-27)



<a name="0.12.1-7"></a>
## [0.12.1-7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-2...v0.12.1-7) (2020-09-27)




<a name="0.13.1-11"></a>
## [0.13.1-11](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-10...v0.13.1-11) (2020-11-02)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-10"></a>
## [0.13.1-10](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-9...v0.13.1-10) (2020-10-26)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-9"></a>
## [0.13.1-9](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-7...v0.13.1-9) (2020-10-26)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-8"></a>
## [0.13.1-8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-7...v0.13.1-8) (2020-10-26)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-7"></a>
## [0.13.1-7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-6...v0.13.1-7) (2020-10-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-6"></a>
## [0.13.1-6](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-5...v0.13.1-6) (2020-10-22)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-5"></a>
## [0.13.1-5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-4...v0.13.1-5) (2020-10-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-4"></a>
## [0.13.1-4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-3...v0.13.1-4) (2020-10-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-3"></a>
## [0.13.1-3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-2...v0.13.1-3) (2020-10-19)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-2"></a>
## [0.13.1-2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.13.1-1...v0.13.1-2) (2020-10-19)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.1-1"></a>
## [0.13.1-1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-3...v0.13.1-1) (2020-10-12)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.12.1-3"></a>
## [0.12.1-3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/v0.12.1-2...v0.12.1-3) (2020-10-12)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.15"></a>
## [1.0.15](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.14...@ali/lowcode-types@1.0.15) (2020-11-05)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.14"></a>
## [1.0.14](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.13...@ali/lowcode-types@1.0.14) (2020-11-04)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.13"></a>
## [1.0.13](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.12...@ali/lowcode-types@1.0.13) (2020-11-04)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.13"></a>
## [1.0.13](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.12...@ali/lowcode-types@1.0.13) (2020-11-02)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.12"></a>
## [1.0.12](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.11...@ali/lowcode-types@1.0.12) (2020-10-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.11"></a>
## [1.0.11](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.10...@ali/lowcode-types@1.0.11) (2020-10-19)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.10"></a>
## [1.0.10](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.9...@ali/lowcode-types@1.0.10) (2020-09-29)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.9"></a>
## [1.0.9](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.8...@ali/lowcode-types@1.0.9) (2020-09-28)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.8"></a>
## [1.0.8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.8-0...@ali/lowcode-types@1.0.8) (2020-09-28)


### Bug Fixes

* 🐛 根据低代码规范,数据源的配置中isInit和 type 都是有默认值的,所以应该是可选的 ([4baf0b4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/4baf0b4))
* 🐛 use lowcode types ([b11425b](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/b11425b))
* fix test result ([7f6fbe8](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7f6fbe8))
* miniAppBuildType config(temp) ([584b4c2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/584b4c2))
* currentPage.id 返回 formUuid ([775725d](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/775725d))
* fix NextTable callback function ([ce77375](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ce77375))
* panel visible time ([18ac1fa](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/18ac1fa))
* supports ([371b84c](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/371b84c))
* 低代码组件 props 显示 object 问题 ([116498e](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/116498e))
* 修复 slot 获取初始值异常的 bug ([63b19f1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/63b19f1))
* 修复判断动态 setter 的逻辑 ([d195d7f](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/d195d7f))
* 兼容事件绑定 ([f4c07af](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/f4c07af))
* 可以降级到历史的 JSBlock 格式 ([af1746b](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/af1746b))
* 合并master分支 ([bd2c6ad](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/bd2c6ad))


### Features

* 🎸 按照中后台搭建协议规范文档补充 JSFunction 的定义和数据源定义中一些字段 ([8b1d0c7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8b1d0c7))
* 🎸 补充规范中定义的 JSFunction 类型 ([9e32525](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/9e32525))
* 🎸 根据低代码协议文档, 将 BlockSchema 也改成继承自 ContainerSchema ([7901c8e](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7901c8e))
* 🎸 根据低代码协议文档, 完善UtilsMap的定义 ([7fe4bc0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/7fe4bc0))
* 🎸 urlParams 类型的数据源不需要 options, 所以 options 改成可选为好 ([8114c6f](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/8114c6f))
* 🎸 增加icon相关的判断函数 ([89064f5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/89064f5))
* add filter reducer ([17c6ed3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/17c6ed3))
* merge live mode ([92c3039](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/92c3039))
* show value state ([bd49e50](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/bd49e50))
* support plaintext liveediting ([ea62f12](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ea62f12))
* support prop.autorun ([c0a5235](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/c0a5235))
* 修复状态切换失效 ([2e3f60d](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/2e3f60d))
* 编辑器 hooks 能力实现 ([f3ac23b](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/f3ac23b))




<a name="1.0.8-0"></a>
## [1.0.8-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.19...@ali/lowcode-types@1.0.8-0) (2020-09-09)


### Bug Fixes

* 合并master分支 ([bd2c6ad](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/bd2c6ad))
* fix NextTable callback function ([ce77375](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ce77375))




<a name="0.8.19"></a>
## [0.8.19](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.18...@ali/lowcode-types@0.8.19) (2020-09-03)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.18"></a>
## [0.8.18](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.17...@ali/lowcode-types@0.8.18) (2020-09-03)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.17"></a>
## [0.8.17](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.16...@ali/lowcode-types@0.8.17) (2020-08-24)
<a name="1.0.7-0"></a>
## [1.0.7-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.6-0...@ali/lowcode-types@1.0.7-0) (2020-09-02)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.6-0"></a>
## [1.0.6-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.17...@ali/lowcode-types@1.0.6-0) (2020-09-02)


### Bug Fixes

* 合并master分支 ([bd2c6ad](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/bd2c6ad))
* fix NextTable callback function ([ce77375](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ce77375))




<a name="1.0.5-0"></a>
## [1.0.5-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.4-0...@ali/lowcode-types@1.0.5-0) (2020-08-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.4-0"></a>
## [1.0.4-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.3-0...@ali/lowcode-types@1.0.4-0) (2020-08-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.3-0"></a>
## [1.0.3-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.2-0...@ali/lowcode-types@1.0.3-0) (2020-08-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.2-0"></a>
## [1.0.2-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@1.0.1-0...@ali/lowcode-types@1.0.2-0) (2020-08-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.1-0"></a>
## [1.0.1-0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.16...@ali/lowcode-types@1.0.1-0) (2020-08-20)




**Note:** Version bump only for package @ali/lowcode-types

<a name="1.0.0"></a>
# [1.0.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.13.0...@ali/lowcode-types@1.0.0) (2020-08-17)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.13.0"></a>
# [0.13.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.12.0...@ali/lowcode-types@0.13.0) (2020-08-17)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.12.0"></a>
# [0.12.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.10.0...@ali/lowcode-types@0.12.0) (2020-08-17)
<a name="0.8.16"></a>
## [0.8.16](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.15...@ali/lowcode-types@0.8.16) (2020-08-19)


### Bug Fixes

* currentPage.id 返回 formUuid ([775725d](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/775725d))




<a name="0.8.15"></a>
## [0.8.15](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.14...@ali/lowcode-types@0.8.15) (2020-08-17)


### Bug Fixes

* 修复判断动态 setter 的逻辑 ([d195d7f](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/d195d7f))




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.11.0"></a>
# [0.11.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.10.0...@ali/lowcode-types@0.11.0) (2020-08-17)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.10.0"></a>
# [0.10.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.9.0...@ali/lowcode-types@0.10.0) (2020-08-16)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.9.0"></a>
# [0.9.0](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.14...@ali/lowcode-types@0.9.0) (2020-08-14)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.14"></a>
## [0.8.14](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.13...@ali/lowcode-types@0.8.14) (2020-08-04)


### Bug Fixes

* 修复 slot 获取初始值异常的 bug ([63b19f1](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/63b19f1))




<a name="0.8.13"></a>
## [0.8.13](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.12...@ali/lowcode-types@0.8.13) (2020-07-21)


### Bug Fixes

* 兼容事件绑定 ([f4c07af](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/f4c07af))




<a name="0.8.12"></a>
## [0.8.12](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.11...@ali/lowcode-types@0.8.12) (2020-07-21)


### Bug Fixes

* 可以降级到历史的 JSBlock 格式 ([af1746b](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/af1746b))




<a name="0.8.11"></a>
## [0.8.11](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.10...@ali/lowcode-types@0.8.11) (2020-07-13)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.10"></a>
## [0.8.10](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.9...@ali/lowcode-types@0.8.10) (2020-07-12)


### Bug Fixes

* 低代码组件 props 显示 object 问题 ([116498e](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/116498e))




<a name="0.8.9"></a>
## [0.8.9](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.7...@ali/lowcode-types@0.8.9) (2020-06-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.7"></a>
## [0.8.7](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.6...@ali/lowcode-types@0.8.7) (2020-06-23)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.6"></a>
## [0.8.6](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.5...@ali/lowcode-types@0.8.6) (2020-06-15)


### Features

* support prop.autorun ([c0a5235](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/c0a5235))




<a name="0.8.5"></a>
## [0.8.5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.4...@ali/lowcode-types@0.8.5) (2020-05-18)




**Note:** Version bump only for package @ali/lowcode-types

<a name="0.8.4"></a>
## [0.8.4](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.3...@ali/lowcode-types@0.8.4) (2020-05-15)


### Features

* add filter reducer ([17c6ed3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/17c6ed3))




<a name="0.8.3"></a>
## [0.8.3](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.2...@ali/lowcode-types@0.8.3) (2020-05-13)


### Bug Fixes

* panel visible time ([18ac1fa](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/18ac1fa))
* supports ([371b84c](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/371b84c))


### Features

* show value state ([bd49e50](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/bd49e50))
* support plaintext liveediting ([ea62f12](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/ea62f12))




<a name="0.8.2"></a>
## [0.8.2](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/compare/@ali/lowcode-types@0.8.1...@ali/lowcode-types@0.8.2) (2020-05-07)


### Features

* 🎸 增加icon相关的判断函数 ([89064f5](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/89064f5))
* 修复状态切换失效 ([2e3f60d](https://gitlab.alibaba-inc.com/ali-lowcode/ali-lowcode-engine/commit/2e3f60d))




<a name="0.8.1"></a>
## 0.8.1 (2020-04-27)




**Note:** Version bump only for package @ali/lowcode-types

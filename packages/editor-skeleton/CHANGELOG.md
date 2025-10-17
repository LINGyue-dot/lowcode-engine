# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.4.1](https://github.com/alibaba/lowcode-engine/compare/v1.4.0...v1.4.1) (2025-10-17)

**Note:** Version bump only for package @epoch/lowcode-editor-skeleton





# 1.4.0 (2025-10-17)


### Bug Fixes

* add some unconfigured i18n text ([56e9f04](https://github.com/alibaba/lowcode-engine/commit/56e9f04221283b501a35ca78e76974a556b5ebdd))
* addon-combine affect metadata unexpectedly ([fc5fbc6](https://github.com/alibaba/lowcode-engine/commit/fc5fbc63a04a32bc887754f32e74c76149d74b05))
* defaultValue should be evaluated inspite of condition result is falsy, fixes [#1045](https://github.com/alibaba/lowcode-engine/issues/1045) ([fcfce3c](https://github.com/alibaba/lowcode-engine/commit/fcfce3cbeb5a53600c40aea07ffef19c9c9591c4))
* delete the defaultValue configuration outside the loop ([acf7449](https://github.com/alibaba/lowcode-engine/commit/acf7449ca231d45e8ed7e1d9416817ea11b1266f))
* **editor-skeleton:** fix missing i18n ([be309cb](https://github.com/alibaba/lowcode-engine/commit/be309cba0178010a14ef8dca5169f3ad900832e7))
* fix build error due to ts definition ([93e9b6e](https://github.com/alibaba/lowcode-engine/commit/93e9b6ee009f02e9eca6b22ecef5df65af117501))
* fix composeTitle returns redundant icons ([ed252fa](https://github.com/alibaba/lowcode-engine/commit/ed252fa13577301c4d66ed7cb54959874c21981f))
* fix left-pane cant hidden when iframe click ([412cb16](https://github.com/alibaba/lowcode-engine/commit/412cb16628222d529fc67ac1180598c6d51e3900))
* fix loop configuration auto fill empty array issue ([d087092](https://github.com/alibaba/lowcode-engine/commit/d087092fd712eff0556adacda692d3ff6f2f9f22))
* fix outline-pane invisible occasionally when dragging tree node ([031c7f2](https://github.com/alibaba/lowcode-engine/commit/031c7f25f10a6cfebfc7929c9226f4e4167a359f))
* fix responsive invalidation caused by upgrading build-plugin-component ([c7c7d93](https://github.com/alibaba/lowcode-engine/commit/c7c7d93e1a0f64d201f04e75039602e7d10174e3))
* fix the problem of crash caused by infinite loop in antd scene ([73acf6f](https://github.com/alibaba/lowcode-engine/commit/73acf6f112de22feb0ccea8033e6adf3b25c0e4b))
* fix the problem of white screen in custom initialization method ([da1450e](https://github.com/alibaba/lowcode-engine/commit/da1450ea1abc52f34d9329deeddeca28be187189))
* fix ts error ([4433b2e](https://github.com/alibaba/lowcode-engine/commit/4433b2ee78590e39113efa22044ffe10154d5c8c))
* leaf should be type of ShellNode other than InnerNode ([5bb8cf5](https://github.com/alibaba/lowcode-engine/commit/5bb8cf5d12d38d70b69fa28deb2f8aa0afa9b9b9))
* logger is not defined error in transformStringToFunction ([b4c20b1](https://github.com/alibaba/lowcode-engine/commit/b4c20b181fb19827a6f5c5492a3a6cc804fe74d4))
* remove `class` prop ([e3e5123](https://github.com/alibaba/lowcode-engine/commit/e3e5123b3173cd0999ace99278e904391baa3aa4))
* supportVariable SHOULD take precedence over supportVariableGlobally ([#1997](https://github.com/alibaba/lowcode-engine/issues/1997)) ([503793f](https://github.com/alibaba/lowcode-engine/commit/503793fdfc4ccc76fe190fad4ba841f86496037d))
* use the outer documentation url of unique key, fixes [#868](https://github.com/alibaba/lowcode-engine/issues/868) ([d770007](https://github.com/alibaba/lowcode-engine/commit/d770007ff8c39e6cf527e07a7d6468dbb88c776d))
* variable binding lost after modify the mock value ([ef95b56](https://github.com/alibaba/lowcode-engine/commit/ef95b5683273d8302bde1582de8afe3d87a808d8))
* 兼容 setters 为空的情况 ([56b459a](https://github.com/alibaba/lowcode-engine/commit/56b459a017a8350a911ef20f0166d1e62b6390e4))
* 增加必要的方法 ([1b38a81](https://github.com/alibaba/lowcode-engine/commit/1b38a812653656aa02100a3b1b2a581188d1b3ef))
* 左侧抽屉固定模式层级不足 ([c657cee](https://github.com/alibaba/lowcode-engine/commit/c657cee0694e3126dee89588a2aa17c4e118f786))


### Features

* add createIntl to common.utils, and fix misuse of zh_CN ([84e0c1f](https://github.com/alibaba/lowcode-engine/commit/84e0c1f09609d81716274af2f94c676e68ab8f15))
* add function return for event setter ([c6d65db](https://github.com/alibaba/lowcode-engine/commit/c6d65dbdc17cfc2ea652e7a09d7aa266afbf4b97))
* add more props for popup ([c11bceb](https://github.com/alibaba/lowcode-engine/commit/c11bceb2cea9548947b724a179518ac0ea280b62))
* add skeleton item model ([239bb29](https://github.com/alibaba/lowcode-engine/commit/239bb29de1853c87f687a4355df76179a09d5ae5))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add theme color document & optimize some theme colors ([79b9a6e](https://github.com/alibaba/lowcode-engine/commit/79b9a6efa57d1a30559ea8476bbb380b5957d968))
* add types for shell, and move functions in types to utils ([55c3fc9](https://github.com/alibaba/lowcode-engine/commit/55c3fc9e58d566edeabd1daa489ac83ba6b787d1))
* add warning message when adding duplicate skeleton ([e415ff6](https://github.com/alibaba/lowcode-engine/commit/e415ff67820697fb6ce2c0a5a7ff22bc9ac0bd7d))
* added detailed definition of some skeleton.add parameters ([c905aa2](https://github.com/alibaba/lowcode-engine/commit/c905aa27c3ace6e756987d1437f8086c4d8fa0a3))
* added features in workspace mode ([33fd6bf](https://github.com/alibaba/lowcode-engine/commit/33fd6bf6426f3300a1e95c80b3021fed26656872))
* added workspace api to support registration of multiple resources ([dae09e3](https://github.com/alibaba/lowcode-engine/commit/dae09e3bcb21b420a88a5e5256320ad50ab1ac2d))
* change loop sertter config, set defaultValue prop to JsonSetter ([aa6b9c8](https://github.com/alibaba/lowcode-engine/commit/aa6b9c8f7a5353771af9f46216310f044e57c533))
* **common-ui:** add HelpTip ([ce72fc1](https://github.com/alibaba/lowcode-engine/commit/ce72fc1b16912312ab9fb2a38bba811dbea7ef13))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* fix designer:entry ts errors ([4d4a8a6](https://github.com/alibaba/lowcode-engine/commit/4d4a8a6d6f94bfcfe9af0409a3a54b22a89f2d26))
* get editor from this or params ([70120a0](https://github.com/alibaba/lowcode-engine/commit/70120a033af95e4d09f3c152c7a6464c5b2ec683))
* material spec add ignoreDefaultValue field to component property description ([9597b1c](https://github.com/alibaba/lowcode-engine/commit/9597b1c3768699c7de90359156e713b2bf474a31))
* refine nesting drawer ([4c032d0](https://github.com/alibaba/lowcode-engine/commit/4c032d0d0ead9731c038bd62dccc4a7d96435183))
* refine pop drawer ([abf8fae](https://github.com/alibaba/lowcode-engine/commit/abf8fae3ef4d62b5688362e1b98f1b508a207029))
* **setter:** add field ts ([6e89d4d](https://github.com/alibaba/lowcode-engine/commit/6e89d4d605760d376fedf350b99f24bc11770ec5))
* **skeleton:** add registerConfigTransducer API ([a3fef9c](https://github.com/alibaba/lowcode-engine/commit/a3fef9c13d39ac1b35b200cf0f711cf7c7c233d8))
* **skeleton:** Add TS defs for modules & optimize Tabs display with array contents ([16713f4](https://github.com/alibaba/lowcode-engine/commit/16713f4b848f3648fa93c82d70007fbec4e8a816))
* support for hiding settings tabs when there is only one item ([#669](https://github.com/alibaba/lowcode-engine/issues/669)) ([cbd95a1](https://github.com/alibaba/lowcode-engine/commit/cbd95a1778415406670f37507ce957af6b3ecd4a))
* support PanelDock icon pointer cursor is always pointer ([a645af7](https://github.com/alibaba/lowcode-engine/commit/a645af7e0b0ce439548f5573102d8c22f35c4fc0))
* update setter types ([aab8a3a](https://github.com/alibaba/lowcode-engine/commit/aab8a3a10ec1612164de76aec81f196d5e395dc5))
* update skeleton ts defined ([21f74f0](https://github.com/alibaba/lowcode-engine/commit/21f74f0cc1566c0a69b7420f3603b16cd8331931))
* when field rendering error, output error log ([14d294c](https://github.com/alibaba/lowcode-engine/commit/14d294c92c662d00350e87d8cf6ec57beee325f6))
* workspace mode supports webview type views ([1f8d91f](https://github.com/alibaba/lowcode-engine/commit/1f8d91f85f2e98d39b1a7a571310af1112998f75))
* **workspace:** add multi foces-tracker in workspace mode ([7b61817](https://github.com/alibaba/lowcode-engine/commit/7b6181719e28b3b56e71f84266a550d14f8d9bba))
* **workspace:** add workspace.skeleton api ([1072ff3](https://github.com/alibaba/lowcode-engine/commit/1072ff36fb6be0743ae199e9a48eeaa38bd8e0d1))
* 大纲树支持节点过滤 ([f30db20](https://github.com/alibaba/lowcode-engine/commit/f30db20606f5f2fdac0017305b1dda7ab2258c4b))

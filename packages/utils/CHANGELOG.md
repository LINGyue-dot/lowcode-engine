# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.4.0 (2025-10-17)


### Bug Fixes

* add protection logic for node-helper.ts when using callbacks ([810ef47](https://github.com/alibaba/lowcode-engine/commit/810ef478e5796d50f1cf52eedb0603a714a4f5a9))
* change typescript type export to export type ([50e4a03](https://github.com/alibaba/lowcode-engine/commit/50e4a03b7d810131ce413cc057b43d4a726f1ebe))
* **context-menu:** fix context menu bugs ([c381b85](https://github.com/alibaba/lowcode-engine/commit/c381b85f0a48b215414e72c76864aa8b435fd443))
* **context-menu:** fix context menu bugs ([8f0291f](https://github.com/alibaba/lowcode-engine/commit/8f0291fc3e58eaec2d786ff8e1854657208d5bde))
* delete unused typescript types ([63f5d2c](https://github.com/alibaba/lowcode-engine/commit/63f5d2ca3e0bda92898fd0df28c9500707812082))
* fix css resources with parameters not loading correctly ([f859752](https://github.com/alibaba/lowcode-engine/commit/f85975211814147d40ae5330a76cb21cb6c66916))
* fix isJSFunction lacks the judgment of the old version of the protocol ([8c7f57a](https://github.com/alibaba/lowcode-engine/commit/8c7f57a12055cdde917ab145d5483cd7d7bf98c5))
* fix issues with build-components ([a4c93c4](https://github.com/alibaba/lowcode-engine/commit/a4c93c43b9ee955e632e068063a032d5dd4aff55))
* fix low-code component rendering problems: 1. thisRequiredInJSE does not take effect 2. jsx components cannot obtain source components ([5dd4625](https://github.com/alibaba/lowcode-engine/commit/5dd462544fbbbccfa97165f2bcfeed8629fab2a3))
* fix object being wrappedReactClass ([a0b51d7](https://github.com/alibaba/lowcode-engine/commit/a0b51d7407ff4943205643dd99e79251b9e308e4))
* fix some ts error ([d8014c9](https://github.com/alibaba/lowcode-engine/commit/d8014c9d1ab310317ad6fafb8fbba2c475d0491d))
* Fix the conversion failure of some props expressions under Slot props of low-code components ([7db5461](https://github.com/alibaba/lowcode-engine/commit/7db5461706c739fac673b2466bc2fda7661242e4))
* fix the performance issue of batch call executeTransaction ([407294d](https://github.com/alibaba/lowcode-engine/commit/407294dff3d6c8845c0b77eef17a24175850b16e))
* fix ts error ([4433b2e](https://github.com/alibaba/lowcode-engine/commit/4433b2ee78590e39113efa22044ffe10154d5c8c))
* fix workspace api ts defined ([6d4ca29](https://github.com/alibaba/lowcode-engine/commit/6d4ca29466640164082274ea791ae2055136c3f9))
* lowcode component exec lifecycle has error ([f99a47e](https://github.com/alibaba/lowcode-engine/commit/f99a47e502080134454795f5e361cfa4fba3f03b))
* make the color of the logger more highlighted ([7a40aff](https://github.com/alibaba/lowcode-engine/commit/7a40aff277bba2969242a2d5780dd6e032714cd7))
* some spell error ([f50410a](https://github.com/alibaba/lowcode-engine/commit/f50410ae7a51b6c4d7ad18f4146c462beb2cfb51))
* supportVariable SHOULD take precedence over supportVariableGlobally ([#1997](https://github.com/alibaba/lowcode-engine/issues/1997)) ([503793f](https://github.com/alibaba/lowcode-engine/commit/503793fdfc4ccc76fe190fad4ba841f86496037d))
* **utils:** isReactComponent not including react.memo ([6160056](https://github.com/alibaba/lowcode-engine/commit/6160056139a044e6b32b2ab0573694fef7f38453))
* 修复 forwardRef 组件的错误无法捕获 ([ca6fe7c](https://github.com/alibaba/lowcode-engine/commit/ca6fe7c335b5035eba18a8681a4bb7a5ccac83b3))


### Features

* add common.utils.executeTransaction API to change multi nodes ([e818d84](https://github.com/alibaba/lowcode-engine/commit/e818d84c8b22ae112498e5b2bf419dc07b91fc29))
* add common.utils.executeTransaction API to change multi nodes ([7bf7ca4](https://github.com/alibaba/lowcode-engine/commit/7bf7ca428d9537398168d3307d448232d5ee11de))
* add createIntl to common.utils, and fix misuse of zh_CN ([84e0c1f](https://github.com/alibaba/lowcode-engine/commit/84e0c1f09609d81716274af2f94c676e68ab8f15))
* add get advanced api for ComponentMeta ([810ccbd](https://github.com/alibaba/lowcode-engine/commit/810ccbd03ef6ce5e4159c3e52aa7efad7073a67e))
* add getDOMNode api definition in node module ([9648331](https://github.com/alibaba/lowcode-engine/commit/964833128b92aafe3266f5096b3d83e7af261372))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add some features ([18d1a4f](https://github.com/alibaba/lowcode-engine/commit/18d1a4fe1d952bcd4715e693def09fee94da49a5))
* add types for shell, and move functions in types to utils ([55c3fc9](https://github.com/alibaba/lowcode-engine/commit/55c3fc9e58d566edeabd1daa489ac83ba6b787d1))
* assetLoader loda scripts with async=false ([f6ad4a1](https://github.com/alibaba/lowcode-engine/commit/f6ad4a157df8c0ff7db327f4770f454998693d9a))
* **context-menu:** add context-menu css theme, help config, ts define ([844ca78](https://github.com/alibaba/lowcode-engine/commit/844ca783d720e5d8829a8e8e54314c97997ec275))
* **context-menu:** update context-menu docs, details, styles ([bb5d7dd](https://github.com/alibaba/lowcode-engine/commit/bb5d7ddf827be5e72707cd1e5ccdf09f6ae16cc1))
* **engine:** add context menu ([1b00c61](https://github.com/alibaba/lowcode-engine/commit/1b00c61a32027084e531a0ffacb2a9a2020fbcbf))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* lowCode components support project schema ([f6537f5](https://github.com/alibaba/lowcode-engine/commit/f6537f536f965ebffb2af50c99d1147f7276373d))
* optimize context menu details ([3627ae3](https://github.com/alibaba/lowcode-engine/commit/3627ae326a5b46e669d921e5b98e237a44e9bdea))
* update the ts definition of the shell module ([9cec5d8](https://github.com/alibaba/lowcode-engine/commit/9cec5d833c224665bd41f74b20b9014327c6abfa))
* **utils|types:** add esmodule support for component meta resources ([#2603](https://github.com/alibaba/lowcode-engine/issues/2603)) ([e3611dc](https://github.com/alibaba/lowcode-engine/commit/e3611dcf06a0a24b691fab00734ce4cecb501f25))
* **utils:** add workspace utils ([ad044f4](https://github.com/alibaba/lowcode-engine/commit/ad044f49ed9064fe1afa5195f68759a76bda5f5e))
* **utils:** cursor 不使用 less ([c50a082](https://github.com/alibaba/lowcode-engine/commit/c50a0823db7630f20ad29d66d3f63a836285cd27))
* **utils:** move checkPropTypes to utils module ([0e65f02](https://github.com/alibaba/lowcode-engine/commit/0e65f021169aa9ddc9016cfa2929bcfd15fd605e))
* 资产包支持一个package从另一个package异步导出 ([#1150](https://github.com/alibaba/lowcode-engine/issues/1150)) ([8a83fc9](https://github.com/alibaba/lowcode-engine/commit/8a83fc9b5c0bca17bc3be5f1d7907ce5c886999d))
* 资产包支持一个package从另一个package异步导出 ([#1150](https://github.com/alibaba/lowcode-engine/issues/1150)) ([6b78157](https://github.com/alibaba/lowcode-engine/commit/6b78157b211d6eabf60297b9ce980a3e10cc8272))


### Reverts

* Revert "fix: delete unused typescript types" ([141e195](https://github.com/alibaba/lowcode-engine/commit/141e19593184d18cb9cac7f7a62b8188059eac4e))

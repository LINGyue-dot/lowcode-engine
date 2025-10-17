# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.4.1](https://github.com/alibaba/lowcode-engine/compare/v1.4.0...v1.4.1) (2025-10-17)

**Note:** Version bump only for package @epoch/lowcode-renderer-core





# 1.4.0 (2025-10-17)


### Bug Fixes

* coding style update ([b786c8f](https://github.com/alibaba/lowcode-engine/commit/b786c8fcaad1376d1d4d1316f75e283418f93913))
* component cannot be redisplayed by configuration after rendering is closed ([c54f369](https://github.com/alibaba/lowcode-engine/commit/c54f369e1860d818479dda9d6429f851c0b08fa6))
* default FaultComponent can not get componentName ([#2385](https://github.com/alibaba/lowcode-engine/issues/2385)) ([4128654](https://github.com/alibaba/lowcode-engine/commit/4128654347d06406a385a724028f90640cbfb07c))
* designer i18n locale is not correct ([6753bf6](https://github.com/alibaba/lowcode-engine/commit/6753bf660b3a3b9c66684f8f8cdd125d35a1d857))
* do not parse props when condition is false or loop data is empty ([#2477](https://github.com/alibaba/lowcode-engine/issues/2477)) ([cf2f5c2](https://github.com/alibaba/lowcode-engine/commit/cf2f5c29bce5917e56e774843266f1b5801fd1c3))
* executeLifeCycleMethod return bug in renderer ([f75b9ae](https://github.com/alibaba/lowcode-engine/commit/f75b9ae61cdc46618038b3fe43e6744aa8d56f5c))
* fix dataSource needs to be compatible due to empty schema ([98bc477](https://github.com/alibaba/lowcode-engine/commit/98bc477d80dbf7993f89befdb42762d78a55fb1b))
* fix displayName spell mistake ([2b2bcbd](https://github.com/alibaba/lowcode-engine/commit/2b2bcbdaebde6a3ce974072f586386ef7ef3497c))
* fix lint issues for renderer-core/renderer/base ([d85437d](https://github.com/alibaba/lowcode-engine/commit/d85437d4af1043371e27dfde98cecf914b93a126))
* fix lint issues for renderer-core/renderer/base ([4b59190](https://github.com/alibaba/lowcode-engine/commit/4b59190c7f9d518bc7efac44b7eeee73f1b5d177))
* fix low-code component rendering problems: 1. thisRequiredInJSE does not take effect 2. jsx components cannot obtain source components ([5dd4625](https://github.com/alibaba/lowcode-engine/commit/5dd462544fbbbccfa97165f2bcfeed8629fab2a3))
* fix misused doc urls ([16a8857](https://github.com/alibaba/lowcode-engine/commit/16a88578634b9da2f04698df5ca5a5e69151bb97))
* fix render module state expression initialization exception ([5bd68ee](https://github.com/alibaba/lowcode-engine/commit/5bd68ee6b448fa58b022870b3f8175d8b77febde))
* fix rendering failure when children is number 0 ([30f8066](https://github.com/alibaba/lowcode-engine/commit/30f8066332b277335b67b681da9fe263d9a15e38))
* Fix the conversion failure of some props expressions under Slot props of low-code components ([7db5461](https://github.com/alibaba/lowcode-engine/commit/7db5461706c739fac673b2466bc2fda7661242e4))
* fix the leaf hoc component fails to monitor Node changes, and modify the logic for get node ([6ee6b07](https://github.com/alibaba/lowcode-engine/commit/6ee6b07a10ba4aac583def52d8ff1fa78d111d0b))
* fix the leaf hoc component fails to monitor Node changes, and modify the logic for get node ([f400172](https://github.com/alibaba/lowcode-engine/commit/f4001728259047b09db75d76a8c3ef1e1bcb4e0a))
* fix the problem caused by props.children is [] by default in leaf ([723eb3d](https://github.com/alibaba/lowcode-engine/commit/723eb3d4d73f92d0720d0ae5208f2d37326b8677))
* Fix the rendering error caused by incorrect key value when configuring the loop ([1026763](https://github.com/alibaba/lowcode-engine/commit/1026763dc5a77d4395a1e86e5a0084ab4fb4230c))
* fix the unit test failure problem caused by thisRequiredInJSE modification ([c2c59b7](https://github.com/alibaba/lowcode-engine/commit/c2c59b7ff72ba06156bbcdb952262739d6188209))
* fix unnecessary props calculation ([f1fed75](https://github.com/alibaba/lowcode-engine/commit/f1fed75f39be8289ede1ec558b04428a69e25b5f))
* fix utils under appHelper will not be updated when props.appHelper is updated ([dc0cf5f](https://github.com/alibaba/lowcode-engine/commit/dc0cf5f62c7671d6743d225fac63691f58027009))
* fixed an issue where materials would be rendered multiple times ([9d187cc](https://github.com/alibaba/lowcode-engine/commit/9d187ccb7de55857e861d3fc881c610506872d03))
* fixed string trim issue ([058e184](https://github.com/alibaba/lowcode-engine/commit/058e184b21b15bcf512d796aea825b69756db537))
* fixed the issue that thisRequiredInJSE did not take effect in some scenarios ([7e5a919](https://github.com/alibaba/lowcode-engine/commit/7e5a919f9352397f11741fd911495996469c0256))
* fixed the problem caused by component list being overwritten by Hoc ([11ee97c](https://github.com/alibaba/lowcode-engine/commit/11ee97c6dafe1ecb60402488ad72b722005cda55))
* hoc 组件缓存 ([7677ad0](https://github.com/alibaba/lowcode-engine/commit/7677ad0166f479fa78c78dfb6d69fb8a3617cbd9))
* import schema 之后 cache 判断错误([#2596](https://github.com/alibaba/lowcode-engine/issues/2596)) ([95a48e0](https://github.com/alibaba/lowcode-engine/commit/95a48e057f856201cb3cbf7c5046128da7e64df6))
* in ES require changed to import ([b4d7d6d](https://github.com/alibaba/lowcode-engine/commit/b4d7d6d8c290a335a2c1f60731d4417b23444941))
* lowcode component leaf dont have export prop, exec leaf.export make error ([9d51dcd](https://github.com/alibaba/lowcode-engine/commit/9d51dcdae38850be0206861f2cae74ca68805c25))
* performance issues when focusing node ([bcaad57](https://github.com/alibaba/lowcode-engine/commit/bcaad576b34c521d1e50a2256d4595bde37e381d))
* project.exportSchema api lack stage param & setAssets should be a async fn ([0ea76a7](https://github.com/alibaba/lowcode-engine/commit/0ea76a746fac8ea8e7b999d42434c468c85d6372))
* recover component lifecycle and avoid execute from scope __proto__ ([394b56d](https://github.com/alibaba/lowcode-engine/commit/394b56d0cef70101709802fb6ab1fda8f0ec2e3a))
* **render-core:** fix when designMode is false & loop is null, isUseLoop should return true ([11b929b](https://github.com/alibaba/lowcode-engine/commit/11b929b42fb3baf76daed473fa3f76cb431c56f8))
* renderer not rendering correct components when loading components with loadAsyncLibrary api ([9b3b4f9](https://github.com/alibaba/lowcode-engine/commit/9b3b4f9b0e35ef3ea2f0117f0cdb2254e15d5389))
* **renderer-core:** remove compatibility with uipaas ([c643c0f](https://github.com/alibaba/lowcode-engine/commit/c643c0fc4f4c9eb90b8d273447fef04d28cfe13d))
* return first if input schema is a react dom ([f5438ff](https://github.com/alibaba/lowcode-engine/commit/f5438ff1abe6067ddb2e267fa8b905dca589138e))
* scope props merge defaultProps ([#2716](https://github.com/alibaba/lowcode-engine/issues/2716)) ([ebdcc41](https://github.com/alibaba/lowcode-engine/commit/ebdcc4146135ae3d41c8cf79024e9247238a8c63))
* type=legao dont make request ([98ececa](https://github.com/alibaba/lowcode-engine/commit/98ececa9c11f93e5f849b201b5b5e7ff453733d7))
* **utils:** isReactComponent not including react.memo ([6160056](https://github.com/alibaba/lowcode-engine/commit/6160056139a044e6b32b2ab0573694fef7f38453))
* when designMode is not design, the hidden attribute does not take effect ([3dd0b6d](https://github.com/alibaba/lowcode-engine/commit/3dd0b6d0a86267e3029c176ff49aff793ce3e186))
* when the component is configured in a loop, the key value changes and renders error ([5db418e](https://github.com/alibaba/lowcode-engine/commit/5db418efe41f8421a644d54926db6ce8d2164eed))
* 修复 forwardRef 组件的错误无法捕获 ([ca6fe7c](https://github.com/alibaba/lowcode-engine/commit/ca6fe7c335b5035eba18a8681a4bb7a5ccac83b3))


### Features

* add common.utils.executeTransaction API to change multi nodes ([e818d84](https://github.com/alibaba/lowcode-engine/commit/e818d84c8b22ae112498e5b2bf419dc07b91fc29))
* add componentRenderer lifeCycles log ([3d470ca](https://github.com/alibaba/lowcode-engine/commit/3d470cad69afb1c761da16dcdadb9bdd6b9c1d19))
* add createIntl to common.utils, and fix misuse of zh_CN ([84e0c1f](https://github.com/alibaba/lowcode-engine/commit/84e0c1f09609d81716274af2f94c676e68ab8f15))
* add new cache from diff origin component ([19935cf](https://github.com/alibaba/lowcode-engine/commit/19935cfc93de111e82691502eaf4f186a84cae37))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add some features ([18d1a4f](https://github.com/alibaba/lowcode-engine/commit/18d1a4fe1d952bcd4715e693def09fee94da49a5))
* add types for shell, and move functions in types to utils ([55c3fc9](https://github.com/alibaba/lowcode-engine/commit/55c3fc9e58d566edeabd1daa489ac83ba6b787d1))
* added features in workspace mode ([33fd6bf](https://github.com/alibaba/lowcode-engine/commit/33fd6bf6426f3300a1e95c80b3021fed26656872))
* added thisRequiredInJSE API to control whether JSExpression expression access context must use this ([#702](https://github.com/alibaba/lowcode-engine/issues/702)) ([da7f77e](https://github.com/alibaba/lowcode-engine/commit/da7f77ee91b3bf441a4a57614872df32d6a1d041))
* **command:** add command apis ([b3880e9](https://github.com/alibaba/lowcode-engine/commit/b3880e9a96c70d750f8f8487913bf6329cdcfb92))
* export nodeChildrenSymbol && remove some unnecessary editor.set ([e83adce](https://github.com/alibaba/lowcode-engine/commit/e83adcee815eea73b6b1ed4f43f4d684c11818ca))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* fix render-core leaf hoc component condition config should get from leaf exportSchema fn ([85704c3](https://github.com/alibaba/lowcode-engine/commit/85704c36946191a1b88db789cfac59e9d027a371))
* improve lowcode component error state in simulator renderer ([#1818](https://github.com/alibaba/lowcode-engine/issues/1818)) ([d64da1e](https://github.com/alibaba/lowcode-engine/commit/d64da1e065aa814d221317beead9c9e32f874472))
* low-code components support lifecycle and function execution ([176583f](https://github.com/alibaba/lowcode-engine/commit/176583f48af573d30c0d2c36faa3d901b0541c06))
* lowcode component add error placeholder ([9228a2b](https://github.com/alibaba/lowcode-engine/commit/9228a2baa702eb72eb556967c25a73d175c534bd))
* modify the output method of rendering module parsing errors ([8255b79](https://github.com/alibaba/lowcode-engine/commit/8255b7945836ee5d25fae73913faa6d0af7b3ff3))
* optimize error component output information ([39f455e](https://github.com/alibaba/lowcode-engine/commit/39f455e13fb3742f56ee5a18b36761f8c85930ab))
* **outline-pane:** export OutlinePaneContext ([5b14230](https://github.com/alibaba/lowcode-engine/commit/5b1423068e5630975cba21460a58b46702810dee))
* provide new api project.setI18n for setting schema.i18n data ([f951399](https://github.com/alibaba/lowcode-engine/commit/f951399f97cee55dd09bcd732f5afafbda54143f))
* removed Rax packages, discontinuing support for Rax ([31a031c](https://github.com/alibaba/lowcode-engine/commit/31a031ce4e4cc22c377aa9d1ce961c5df4cad58b))
* **render-core:** update logger to console ([b697ea9](https://github.com/alibaba/lowcode-engine/commit/b697ea9ad4399a90cf2560b45beb4ae669700fbc))
* **renderer-core:** added log when executing setState ([5c49044](https://github.com/alibaba/lowcode-engine/commit/5c49044a7738713fa5f883f1fa1afa11a898d9bf))
* **renderer-core:** optimize the judgment of whether leaf hoc has children ([d82bcfd](https://github.com/alibaba/lowcode-engine/commit/d82bcfdf2a4d469fe844632cb0683945ff7aadb9))
* **renderer-core:** optimize the judgment of whether leaf hoc has children ([f10b694](https://github.com/alibaba/lowcode-engine/commit/f10b694c42ae97ebdd337758361031d8745349d8))
* support for NotFoundComponent design state is optional ([#1013](https://github.com/alibaba/lowcode-engine/issues/1013)) ([d3c891e](https://github.com/alibaba/lowcode-engine/commit/d3c891e2a46d138e31c81a7f9b804a8240154df5))
* the renderer-core leaf component removes the react.createElement call ([c3ce042](https://github.com/alibaba/lowcode-engine/commit/c3ce042c835b0c6c8f319dc9c286bc43a903c61a))
* **utils:** checkPropTypes suport IPublicTypePropType as rule for check ([e6ba79b](https://github.com/alibaba/lowcode-engine/commit/e6ba79b4d7eab23962c5aae29fca633a9862d173))
* **utils:** move checkPropTypes to utils module ([0e65f02](https://github.com/alibaba/lowcode-engine/commit/0e65f021169aa9ddc9016cfa2929bcfd15fd605e))
* 为 renderer 追加 displayName，以支持后续的反射功能 ([6399cce](https://github.com/alibaba/lowcode-engine/commit/6399cce05ae494dac6facf4366949b0b97576079))

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.4.1](https://github.com/alibaba/lowcode-engine/compare/v1.4.0...v1.4.1) (2025-10-17)

**Note:** Version bump only for package @epoch/lowcode-react-simulator-renderer





# 1.4.0 (2025-10-17)


### Bug Fixes

* duplicate key "locale" in renderer.ts ([1b0e7e2](https://github.com/alibaba/lowcode-engine/commit/1b0e7e288a5bd6c618222746900fade6a1b1090a))
* fiberkey compatibility ([fb3aea4](https://github.com/alibaba/lowcode-engine/commit/fb3aea4f27ba99a14183c37ee7961d55fa9149e7))
* fix low-code component rendering problems: 1. thisRequiredInJSE does not take effect 2. jsx components cannot obtain source components ([5dd4625](https://github.com/alibaba/lowcode-engine/commit/5dd462544fbbbccfa97165f2bcfeed8629fab2a3))
* fix render module state expression initialization exception ([5bd68ee](https://github.com/alibaba/lowcode-engine/commit/5bd68ee6b448fa58b022870b3f8175d8b77febde))
* fix responsive invalidation caused by upgrading build-plugin-component ([c7c7d93](https://github.com/alibaba/lowcode-engine/commit/c7c7d93e1a0f64d201f04e75039602e7d10174e3))
* fix slot id is automatically generated every time ([33a4192](https://github.com/alibaba/lowcode-engine/commit/33a4192e2c786a0dae170744c31d15ef3bbe3ced))
* fix the leaf hoc component fails to monitor Node changes, and modify the logic for get node ([f400172](https://github.com/alibaba/lowcode-engine/commit/f4001728259047b09db75d76a8c3ef1e1bcb4e0a))
* leaf should be type of ShellNode other than InnerNode ([5bb8cf5](https://github.com/alibaba/lowcode-engine/commit/5bb8cf5d12d38d70b69fa28deb2f8aa0afa9b9b9))
* missing i18n parameter in simulater and renderer ([fc7c217](https://github.com/alibaba/lowcode-engine/commit/fc7c217f8cec0e0db064b7ebf8038c75c3ef253a))
* **react-simulator-renderer:** detached node has children ([b29c539](https://github.com/alibaba/lowcode-engine/commit/b29c53901e4a1c1f437d9fe71aadaa16d02686f4))
* **react-simulator-renderer:** fix missing i18n of customCreateElement ([5c6572e](https://github.com/alibaba/lowcode-engine/commit/5c6572e3026ce7dafde6648b04f6ea0bc1be4b5e))
* renderer not rendering correct components when loading components with loadAsyncLibrary api ([9b3b4f9](https://github.com/alibaba/lowcode-engine/commit/9b3b4f9b0e35ef3ea2f0117f0cdb2254e15d5389))
* 修复 forwardRef 组件的错误无法捕获 ([ca6fe7c](https://github.com/alibaba/lowcode-engine/commit/ca6fe7c335b5035eba18a8681a4bb7a5ccac83b3))
* 修复React17选中组件bug ([750d282](https://github.com/alibaba/lowcode-engine/commit/750d282c03a880204fefdef01e180510465b82f8))


### Features

* add common.utils.executeTransaction API to change multi nodes ([e818d84](https://github.com/alibaba/lowcode-engine/commit/e818d84c8b22ae112498e5b2bf419dc07b91fc29))
* add createIntl to common.utils, and fix misuse of zh_CN ([84e0c1f](https://github.com/alibaba/lowcode-engine/commit/84e0c1f09609d81716274af2f94c676e68ab8f15))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* added thisRequiredInJSE API to control whether JSExpression expression access context must use this ([#702](https://github.com/alibaba/lowcode-engine/issues/702)) ([da7f77e](https://github.com/alibaba/lowcode-engine/commit/da7f77ee91b3bf441a4a57614872df32d6a1d041))
* first commit - genesis ([4f4ac51](https://github.com/alibaba/lowcode-engine/commit/4f4ac5115d18357a7399632860808f6cffc33fad))
* improve lowcode component error state in simulator renderer ([#1818](https://github.com/alibaba/lowcode-engine/issues/1818)) ([d64da1e](https://github.com/alibaba/lowcode-engine/commit/d64da1e065aa814d221317beead9c9e32f874472))
* low-code components support lifecycle and function execution ([176583f](https://github.com/alibaba/lowcode-engine/commit/176583f48af573d30c0d2c36faa3d901b0541c06))
* lowcode component add error placeholder ([9228a2b](https://github.com/alibaba/lowcode-engine/commit/9228a2baa702eb72eb556967c25a73d175c534bd))
* lowCode components support project schema ([f6537f5](https://github.com/alibaba/lowcode-engine/commit/f6537f536f965ebffb2af50c99d1147f7276373d))
* provide new api project.setI18n for setting schema.i18n data ([f951399](https://github.com/alibaba/lowcode-engine/commit/f951399f97cee55dd09bcd732f5afafbda54143f))
* suport more locale config ([4728484](https://github.com/alibaba/lowcode-engine/commit/4728484e7e449b8af4d66b414bdb474608bc95e0))
* support for NotFoundComponent design state is optional ([#1013](https://github.com/alibaba/lowcode-engine/issues/1013)) ([d3c891e](https://github.com/alibaba/lowcode-engine/commit/d3c891e2a46d138e31c81a7f9b804a8240154df5))
* support SPA mode ([1f9150e](https://github.com/alibaba/lowcode-engine/commit/1f9150e4b260d522bd7cb31497069b700a1e8576))
* sync utils/constants ([#506](https://github.com/alibaba/lowcode-engine/issues/506)) ([2871b5b](https://github.com/alibaba/lowcode-engine/commit/2871b5ba4c3dbf1ed76bf4d6359fb457190a9b22))
* 分析了 dragon 以及修改 placeholder ([00c17b4](https://github.com/alibaba/lowcode-engine/commit/00c17b42c5e2745a7e444368bead9d75b83556ab))
* 新增render notFoundComponent、faultComponent engineConfig配置 ([fceffce](https://github.com/alibaba/lowcode-engine/commit/fceffce5cdc2cb4aabc7d17b3405bc91ad0d7402))

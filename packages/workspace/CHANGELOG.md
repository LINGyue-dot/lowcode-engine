# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.4.0 (2025-10-17)


### Bug Fixes

* fix left-pane cant hidden when iframe click ([412cb16](https://github.com/alibaba/lowcode-engine/commit/412cb16628222d529fc67ac1180598c6d51e3900))
* fix packege/workspace missing partial export ([f9e6913](https://github.com/alibaba/lowcode-engine/commit/f9e6913c20adf8ce5b4c6a45f807387c95c9f095))
* fix responsive invalidation caused by upgrading build-plugin-component ([c7c7d93](https://github.com/alibaba/lowcode-engine/commit/c7c7d93e1a0f64d201f04e75039602e7d10174e3))
* fix the problem of using canvas.dragon api in workspace mode ([b07d33e](https://github.com/alibaba/lowcode-engine/commit/b07d33e99a14a9cedf298bc14517ddfa161ffa81))
* fix workspace api ts defined ([6d4ca29](https://github.com/alibaba/lowcode-engine/commit/6d4ca29466640164082274ea791ae2055136c3f9))
* fix workspace openEditorWindow API bugs ([5c13918](https://github.com/alibaba/lowcode-engine/commit/5c139181b6b0e1a542e0babc9cb63e7938306079))
* optimize interface type export ([4ddff25](https://github.com/alibaba/lowcode-engine/commit/4ddff259f8e7ffaabade44309b75317a0b91d5ff))
* removeEditorWindow does not compare title ([9fd28ef](https://github.com/alibaba/lowcode-engine/commit/9fd28efd0ea6f4d872928d1e339c852b817194da))
* ts interface error ([fc964ec](https://github.com/alibaba/lowcode-engine/commit/fc964ec7156f7598ead2a568c4c315fbb1264d2f))
* **workspace:** fix workspace editorView is undefined ([44beb2a](https://github.com/alibaba/lowcode-engine/commit/44beb2a25ad57cbc4cc2c88c577c5467542a9fd4))


### Features

* add commonUI API ([be0456f](https://github.com/alibaba/lowcode-engine/commit/be0456fb398c731c4492fbca83aebc8ed9e9f3f3))
* add config.workspaceEmptyComponent ([aa1bb1c](https://github.com/alibaba/lowcode-engine/commit/aa1bb1c0d720d972e64049f92358456b14069310))
* add hotkey in workspace plugins ([8414425](https://github.com/alibaba/lowcode-engine/commit/841442574080d6399d549a1a974c71d5b4a572f0))
* add resource layer layout in workspace mode ([6482609](https://github.com/alibaba/lowcode-engine/commit/6482609ac140b62ddd2b0469f187e0b9b775583b))
* add skeleton item model ([239bb29](https://github.com/alibaba/lowcode-engine/commit/239bb29de1853c87f687a4355df76179a09d5ae5))
* add some big features to engine ([c2db198](https://github.com/alibaba/lowcode-engine/commit/c2db198415632e3fa9653a1c08646f0a67514257))
* add state for workspace windows ([d267fec](https://github.com/alibaba/lowcode-engine/commit/d267fecc67f3c3eec08c224aeb62c1957ff39187))
* add theme color document & optimize some theme colors ([79b9a6e](https://github.com/alibaba/lowcode-engine/commit/79b9a6efa57d1a30559ea8476bbb380b5957d968))
* added apis support resource tree in workspace mode ([ea08173](https://github.com/alibaba/lowcode-engine/commit/ea08173af0b40d1af90c0445328614c000696682))
* added features in workspace mode ([33fd6bf](https://github.com/alibaba/lowcode-engine/commit/33fd6bf6426f3300a1e95c80b3021fed26656872))
* added onChangeViewType event to window model ([0184dcd](https://github.com/alibaba/lowcode-engine/commit/0184dcd9384a3145dff92e96bca2de414c02d99d))
* added workspace api to support registration of multiple resources ([dae09e3](https://github.com/alibaba/lowcode-engine/commit/dae09e3bcb21b420a88a5e5256320ad50ab1ac2d))
* canvas.activeTracker add targer prop ([2b3d96c](https://github.com/alibaba/lowcode-engine/commit/2b3d96cedada3f3c3f91f16129aadee466052b9b))
* **command:** add command apis ([b3880e9](https://github.com/alibaba/lowcode-engine/commit/b3880e9a96c70d750f8f8487913bf6329cdcfb92))
* **context-menu:** update context-menu docs, details, styles ([bb5d7dd](https://github.com/alibaba/lowcode-engine/commit/bb5d7ddf827be5e72707cd1e5ccdf09f6ae16cc1))
* get editor from this or params ([70120a0](https://github.com/alibaba/lowcode-engine/commit/70120a033af95e4d09f3c152c7a6464c5b2ec683))
* improve the workspace sleep scene ([059ffe0](https://github.com/alibaba/lowcode-engine/commit/059ffe0eaac7c82ca3a97789a25a0eed0f57a2c3))
* modify the usage of resource registration ([7d526d1](https://github.com/alibaba/lowcode-engine/commit/7d526d1e836356cc820a7c9aca5981929ced0793))
* optimize ts definition ([88961aa](https://github.com/alibaba/lowcode-engine/commit/88961aa6409c52ebd7af67efd5134baf3c8ab424))
* remove extra classname ([f1519b7](https://github.com/alibaba/lowcode-engine/commit/f1519b7f5cf1d9750215d2badc7c637e0fbae59e))
* resourceList children support different resourceName ([ebe21c4](https://github.com/alibaba/lowcode-engine/commit/ebe21c4d07d9b2805c524bad0e40d45cc8f12c91))
* **shell:** add editor-view model ([358dde4](https://github.com/alibaba/lowcode-engine/commit/358dde43a4a6097abc71fd47e708cca7af105acf))
* support PanelDock icon pointer cursor is always pointer ([a645af7](https://github.com/alibaba/lowcode-engine/commit/a645af7e0b0ce439548f5573102d8c22f35c4fc0))
* support the use of events in workspace mode to communicate in different views ([163416f](https://github.com/alibaba/lowcode-engine/commit/163416fcfe291e133551cd75e484cc3ea6d0edc8))
* support webview type resource in workspace mode ([36d1d3b](https://github.com/alibaba/lowcode-engine/commit/36d1d3bef1d613c06219bab63e578d1939da1c56))
* update test package.yaml ([5657d9c](https://github.com/alibaba/lowcode-engine/commit/5657d9c084899e91077008c491284248776ad7d8))
* update the ts definition of the shell module ([9cec5d8](https://github.com/alibaba/lowcode-engine/commit/9cec5d833c224665bd41f74b20b9014327c6abfa))
* **utils:** add workspace utils ([ad044f4](https://github.com/alibaba/lowcode-engine/commit/ad044f49ed9064fe1afa5195f68759a76bda5f5e))
* workspace add onChangeActiveWindow event api ([22d2fdd](https://github.com/alibaba/lowcode-engine/commit/22d2fddc3e999dc8516f2d5b0e2b57527efbe741))
* workspace add some features ([ee80fb1](https://github.com/alibaba/lowcode-engine/commit/ee80fb12b864f2ddd657fe1503e57f755697d07a))
* workspace mode supports webview type views ([1f8d91f](https://github.com/alibaba/lowcode-engine/commit/1f8d91f85f2e98d39b1a7a571310af1112998f75))
* workspace window add onSave api ([b984ef7](https://github.com/alibaba/lowcode-engine/commit/b984ef72d28f98a6e7a72ea3d051dc254f402749))
* **workspace:** add config for resource shell model ([c3d75b2](https://github.com/alibaba/lowcode-engine/commit/c3d75b27da5c9f1b800d2aee4befc30477b16a29))
* **workspace:** add editorViews to resourceTypeList api ([c838dc7](https://github.com/alibaba/lowcode-engine/commit/c838dc70eb71e4aaae37494baf7f3a1d3fec8340))
* **workspace:** add enableAutoOpenFirstWindow config and onWindowRendererReady function ([9b50bc7](https://github.com/alibaba/lowcode-engine/commit/9b50bc700e18e02d590d7a77591809cdbad8a160))
* **workspace:** add multi foces-tracker in workspace mode ([7b61817](https://github.com/alibaba/lowcode-engine/commit/7b6181719e28b3b56e71f84266a550d14f8d9bba))
* **workspace:** add resourceTypeList api ([#2148](https://github.com/alibaba/lowcode-engine/issues/2148)) ([dc029c2](https://github.com/alibaba/lowcode-engine/commit/dc029c252a5a135ffbce17c66040f72ea4b7fe00))
* **workspace:** add workspace.skeleton api ([1072ff3](https://github.com/alibaba/lowcode-engine/commit/1072ff36fb6be0743ae199e9a48eeaa38bd8e0d1))
* **workspace:** fix onWindowRendererReady api ([bfdc7a2](https://github.com/alibaba/lowcode-engine/commit/bfdc7a277ba4713dbfdd1c9efe01bbd9126a4219))
* **workspace:** resource supports the init lifecycle and initializes plugins ([0d388a3](https://github.com/alibaba/lowcode-engine/commit/0d388a30766c556c5fe3abc57a6db4322b0588c9))
* **workspace:** update openEditorWindow api ([899ffa1](https://github.com/alibaba/lowcode-engine/commit/899ffa15541164c31e2e3688344639046df282ec))
* **workspace:** update removeEditorWindow api ([547bbf4](https://github.com/alibaba/lowcode-engine/commit/547bbf4ddc0377c15f3e348d49d86eaa49de17ca))
* **workspace:** when the sleep window is opened, the active window event is not triggered ([cf3d7a8](https://github.com/alibaba/lowcode-engine/commit/cf3d7a86429f5bd7d9c8ff59162b208b272c627e))

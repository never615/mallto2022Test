该测试题目是我们系统中的已有功能,如图![](https://files.catbox.moe/cf0kjf.png)



题目是使用 mapbox 引擎配合 tree.js 渲染出3d 模型(模型需要和 mapbox 引擎融合). 设计到对两个库的简单的 API 调用,可能涉及到英文文档的阅读,如果搞不定也有开源代码可以参考,涉及到了源码的阅读.同时也考核了 git 的使用.


### 涉及到的依赖库
* 地图引擎 mapbox 官网:mapbox.com
* mapbox 文档中接入3d 模型的部分:https://docs.mapbox.com/mapbox-gl-js/example/add-3d-model/
* tree.js 库地址: https://github.com/mrdoob/three.js


### 涉及到的文件
* 目录中的 rd.gltf 是3d 模型文件
* index.json 是 Mapbox style object.包含地图样式和数据. 使用mapbox 的setstyle api 可以设置改 json文件.


---

另外有开源代码可以参考:gltf 是一个使用 tree.js用来预览3d 模型文件的网站,并且他的代码是开源的可以用来参考 tree.json 的使用.https://gltf-viewer.donmccurdy.com/

目录中的截图1就是该网站默认打开3D 模型的样子.




完成的代码提交到自己的 github 上,然后把项目地址给我们进行检查.

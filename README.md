题目是使用 mapbox 引擎配合 tree.js 渲染出3d 模型并和 mapbox 引擎融合.

地图引擎 mapbox 官网:mapbox.com
mapbox 文档中接入3d 模型的部分:https://docs.mapbox.com/mapbox-gl-js/example/add-3d-model/
tree.js 库地址: https://github.com/mrdoob/three.js


目录中的 rd.gltf 是3d 模型文件
index.json 是 Mapbox style object.包含地图样式和数据. 使用mapbox 的setstyle api 可以设置改 json文件.


gltf 是一个使用 tree.js用来预览3d 模型文件的网站,并且他的代码是开源的可以用来参考 tree.json 的使用.https://gltf-viewer.donmccurdy.com/

目录中的截图就是该网站默认打开3D 模型的样子.

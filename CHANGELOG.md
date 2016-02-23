# ChangeLog

## 1.0.0-rc.3

* update:强化打包功能，增加引用压缩静态资源打包方式，同时将代码压缩成zip包
* update:发布功能增加携带remote参数指定机器名，以避免重复选择发布机器

## 1.0.0-rc.2

* fix:修复页面片需要合并时页面URL出错的问题
* fix:修复windows下编译文件路径的问题
* fix:修复windows下文件上传过滤的bug
* update:站点地图通过扫描各个模块下页面来生成
* update:当请求模板错误且本地没有缓存模板时使用默认模板

## 1.0.0-rc.1

* update:编译提速，增加图片压缩时的缓存
* update:编译提速，增加编译时的sass缓存

## 0.0.39

* 生成项目、模块、页面、组件文件结构
* 轻量组件化功能
* 根据组件加载情况生成资源依赖表
* 页面、组件html编译
* Sass/less 编译
* csslint/jshint 代码检查
* CSS合并压缩
* CSS prefix，px转rem
* JS合并压缩
* 自动生成雪碧图，自动多倍图
* 图片压缩
* 字体压缩
* 文件MD5戳
* 本地预览
* 资源定位（图片等资源路径替换）
* 生成CSS页面片
* 部署到预览机和开发机

![Bower version](https://img.shields.io/bower/v/adminlte.svg)
[![npm version](https://img.shields.io/npm/v/admin-lte.svg)](https://www.npmjs.com/package/admin-lte)
[![Packagist](https://img.shields.io/packagist/v/almasaeed2010/adminlte.svg)](https://packagist.org/packages/almasaeed2010/adminlte)

###一些事一些情
龙果团队是一个年轻有力的团队，在开发过程中，发现国内很难找到有高大上的后台模板。后来团队使用了AdminLTE这个开源框架，好东西不敢独享。我们在AdminLTE上面做了多项优化，并进行了汉化，适合国民使用。

###简介
**RonCoo AdminLTE** --是一个完全响应式的后台管理模板。基于 **[AdminLTE](https://github.com/almasaeed2010/AdminLTE)** 框架，易于使用，并高度可定制，适合许多屏幕分辨率从小型移动设备到大型台式机。

###重要说明
 框架基于AdminLTE 的最新版本 **[2.3.6](https://github.com/almasaeed2010/AdminLTE/tree/v2.3.6)**，后续会随着AdminLET版本更新而更新。

###优化日志
1. 根据我们团队的需求，增加了Ajax的布局模式。只需要在body标签里面添加`.ajax-template .fixed`类即可实现。
2. 增加include文件夹，用于存放ajax加载的内页文件。
3. 根目录的build文件夹增加了fonts、img、js文件夹，通过grunt编译转移到dist/目录，更利于二次开发时源码目录与编译目录区分。
4. Gruntfile.js 添加了`grunt-contrib-connect`模块，装好node编译环境后，grunt即可发起服务，在浏览器输入`localhost:8000`即可访问，更方便二次开发。
5. 把index.html的外链的js、css和字体文件全部下载到本地的build目录下

###如何发布


###接下来要做点什么？
1. 我们将会开源一个后台管理框架，基于SpringMVC进行集成
2. 继续优化本框架，欢迎大家来提建议。
3. 群号：546588570

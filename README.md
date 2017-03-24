
![Bower version](https://img.shields.io/bower/v/adminlte.svg)
[![npm version](https://img.shields.io/npm/v/admin-lte.svg)](https://www.npmjs.com/package/admin-lte)
[![Packagist](https://img.shields.io/packagist/v/almasaeed2010/adminlte.svg)](https://packagist.org/packages/almasaeed2010/adminlte)

![roncoo_adminLte](http://www.roncoo.com/images/adminlte.png)

###一些事一些情
对于一个平台的管理后台，功能必然要足够强大，但界面也不可忽略，特别是近年来行业对界面的越加重视使得后台界面也要做得 ‘ 高大上 ’ 起来；可惜国内至今未能找到一款免费开源的稍微高大上点后台模板，用国内模板的都会引来 leader的各种吐槽；而国外虽然有很多很优秀的模板，但由于都没有中文版或者担心社区不够强大而不敢使用；针对这一点龙果团队决定为国民谋利，找了一款国外非常优秀的后台模板AdminLTE，并在AdminLTE上面做了多项优化，并进行了汉化，免费开源给国民开发者使用，并对AdminLTE后期的更新做维护。

###简介
**RonCoo AdminLTE** --是一个完全响应式的免费开源后台管理模板。基于 **[AdminLTE](https://github.com/almasaeed2010/AdminLTE)** 框架（后续会随着版本更新而更新）;使用jQuery 2.2.3版本，并引入很多优秀的第三方jQuery插件，开发者也可以改用自己熟悉的第三方插件,易于使用，并高度可定制，适合许多屏幕分辨率从小型移动设备到大型台式机，这是国内的开源模板未支持的。

#####在线预览：[demo.adminlte.roncoo.com](http://demo.adminlte.roncoo.com/)
##### SSM整合在线预览：[demo.adminlte.roncoo.com/roncoo-adminlte-springmvc](http://demo.adminlte.roncoo.com/roncoo-adminlte-springmvc/)

###更新日志

####2017-03-24
1. 添加tab页刷新
2. 优化tab导航
3. 修复index2内页样式丢失

####2017-01-03
1. 添加自定义表格及实例
2. 优化tab导航

####2016-11-11
1. tab导航右键菜单
2. 优化滚动条
3. 优化app.js

####2016-11-7
修改目录，把跟目录下的bootstrap移到plugins
增加一个使用版，使用版没有开发源文件，只剩下min后的js和CSS

####2016-10-28
1. ajax模式中所有js和css统一在index.html引入，不再分开页面引入。
2. ajax模式中添加tab页功能，加载页面可以加载多个，通过头部tab切换，该功能只在ajax模式中存在.
3. 在实例中添加了一个table的实例，并做好了服务端的分页，table数据的处理等。
4. a标签通过添加属性target=navTab添加新开标签页功能，通过异步请求href连接页面，仅ajax模式可使用。
5. a标签通过添加属性target="modal"添加弹出层页面功能，并通过modal=lg \modal=ms \ modal="" 属性约定窗口大小 不设置modal属性是使用默认的大小适中的弹出层。
6. 新增提示窗js功能，alertMsg（"提示内容"，"提示类型——default、success、warning、danger 默认为default"）。
7. 优化右侧栏功能。

####2016-10-17
1. 根据用户反馈，添加三个新的登录注册页面实例，可以在预览地址中左边导航的实例中预览
`/pages/examples/login1.html`
`/pages/examples/login2.html`
`/pages/examples/login3.html`

2. `/Gruntfile.js`代码编译打包优化，执行 `grunt` 默认对less编译，对js复制处理，如果需要对js做代码质量检测，请执行`grunt lint`

####2016-09-30
1. 添加在线预览地址

####2016-09-26
1. 根据我们团队的需求，增加了Ajax的布局模式。只需要在body标签里面添加`.ajax-template .fixed`类即可实现。
2. 增加include文件夹，用于存放ajax加载的内页文件。
3. 根目录的build文件夹增加了fonts、img、js文件夹，通过grunt编译转移到dist/目录，更利于二次开发时源码目录与编译目录区分。
4. Gruntfile.js 添加了`grunt-contrib-connect`模块，装好node编译环境后，grunt即可发起服务，在浏览器输入`localhost:8000`即可访问，更方便二次开发。
5. 把index.html的外链的js、css和字体文件全部下载到本地的build目录下

###如何使用
**RonCoo AdminLTE** 的使用跟使用普通的html模板一样，可以自由和PHP、asp、jsp等技术集成，静态资源文件在`/dist`目录，第三方插件在`plugins`目录，也可以根据自己的开发需求加入更好更适合自己使用的插件。需要注意的是龙果集成的AJAX模式需要放在web服务上才可以预览效果（可以是本机发起的服务如tomcat、apache、node）等，具体如何使用请参考`/index.html`。

###二次开发
**AdminLTE** 是用nodejs 相关工具开发的，所以要做二次开发首先要有一定的nodejs基础并安装好node环境和git版本管理工具。
####获取
直接 [github](https://github.com/roncoo/roncoo-adminLTE.git) 下载源码，或者在存放代码的目录打开命令行并输入
```
git clone https://github.com/roncoo/roncoo-adminLTE.git
```
####安装
```
npm install
```
####编译发布
```
grunt
```
####项目目录
```
roncoo-AdminLTE/
├── dist/ 编译后的静态资源目录
│   ├── CSS/
│   ├── JS
│   ├── fonts
│   ├── img
├── build/ 编译前的源文件目录
│   ├── less/
│   │   ├── roncoo-AdminLTE's Less 文件
│   ├── fonts/
│   │   ├── roncoo-AdminLTE's 字体 文件
│   ├── js/
│   │   ├── roncoo-AdminLTE's javascript 文件
│   ├── img/
│   │   ├── roncoo-AdminLTE's image 文件
│   └── Bootstrap-less/ (bootstrap less，仅供参考，不做修改)
│       ├── mixins/
│       ├── variables.less
│       ├── mixins.less
└── plugins/
    ├── 所有的第三方插件的CSS和JS文件
```

###接下来要做点什么？
1. 我们将会开源一个后台管理框架，基于SpringMVC进行集成
2. 继续优化本框架，并与AdminLTE同步更新。
3. 如果大家有疑问或建议（加群：546588570 或者邮件：laiwb@roncoo.com）。

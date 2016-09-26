龙果后台管理系统-前端框架
============

![Bower version](https://img.shields.io/bower/v/adminlte.svg)
[![npm version](https://img.shields.io/npm/v/admin-lte.svg)](https://www.npmjs.com/package/admin-lte)
[![Packagist](https://img.shields.io/packagist/v/almasaeed2010/adminlte.svg)](https://packagist.org/packages/almasaeed2010/adminlte)

###一些事一些情
龙果团队是一个年轻有力的团队，在开发过程中，发现国内很难找到有高大上的后台模板。后来团队内部一致使用了AdminLET这个开源框架，好东西不敢独享。我们在AdminLET上面做了优化，并进行了汉化，使用国民使用。

###简介
**RonCoo AdminLTE** --是一个完全响应式的后台管理模板。基于 **[AdminLET](https://github.com/almasaeed2010/AdminLTE)** 框架，易于使用，并高度可定制，适合许多屏幕分辨率从小型移动设备到大型台式机。

###重要说明
 框架基于AdminLET 的最新版本 **[2.3.6](https://github.com/almasaeed2010/AdminLTE/tree/v2.3.6)**，后续会随着AdminLET版本更新而更新。

###优化日志
1. 根据我们团队的需求，增加了Ajax的布局模式。只需要在body标签里面添加`.ajax-template .fixed`类即可实现。
2. 增加include文件夹，用于存放ajax加载的内页文件。
3. 根目录的build文件夹增加了fonts、img、js文件夹，通过grunt编译转移到dist/目录，更利于二次开发时源码目录与编译目录区分。
4. Gruntfile.js 添加了`grunt-contrib-connect`模块，装好node编译环境后，grunt即可发起服务，在浏览器输入`localhost:8000`即可访问，更方便二次开发。
5. 把index.html的外链的js、css和字体文件全部下载到本地的build目录下

###如何发布
1. （加上一些截图）

###接下来要做点什么？
1. 我们将会开源一个后台管理框架，基于SpringMVC进行集成
2. 继续优化本框架，欢迎大家来提建议。
3. 群号：xxxx

###捐赠



Looking for Premium Templates?
------------------------------
**Almsaeed studio just opened a new premium templates page. Hand picked to insure the best quality and the most affordable prices. Visit https://almsaeedstudio.com/premium for more information.**


!["AdminLTE Presentation"] (https://almsaeedstudio.com/AdminLTE2.png "AdminLTE Presentation")

**AdminLTE** has been carefully coded with clear comments in all of its JS, LESS and HTML files. LESS has been used to increase code customizability.

Installation
------------
There are multiple ways to install AdminLTE.

####Download:

Download from Github or [visit Almsaeed Studio](https://almsaeedstudio.com) and download the latest release.

####Using The Command Line:

**Github**

- Fork the repository ([here is the guide](https://help.github.com/articles/fork-a-repo/)).
- Clone to your machine
```
git clone https://github.com/YOUR_USERNAME/AdminLTE.git
```

**Bower**

```
bower install admin-lte
```

**npm**

```
npm install --save admin-lte
```

**Composer**

```
composer require "almasaeed2010/adminlte=~2.0"
```

Documentation
-------------
Visit the [online documentation](https://almsaeedstudio.com/themes/AdminLTE/documentation/index.html) for the most
updated guide. Information will be added on a weekly basis.

Browser Support
---------------
- IE 9+
- Firefox (latest)
- Chrome (latest)
- Safari (latest)
- Opera (latest)

Contribution
------------
Contribution are always **welcome and recommended**! Here is how:

- Fork the repository ([here is the guide](https://help.github.com/articles/fork-a-repo/)).
- Clone to your machine ```git clone https://github.com/YOUR_USERNAME/AdminLTE.git```
- Make your changes
- Create a pull request

#### Contribution Requirements:

- When you contribute, you agree to give a non-exclusive license to Almsaeed Studio to use that contribution in any context as we (Almsaeed Studio) see appropriate.
- If you use content provided by another party, it must be appropriately licensed using an [open source](http://opensource.org/licenses) license.
- Contributions are only accepted through Github pull requests.
- Finally, contributed code must work in all supported browsers (see above for browser support).

License
-------
AdminLTE is an open source project by [Almsaeed Studio](https://almsaeedstudio.com) that is licensed under [MIT](http://opensource.org/licenses/MIT). Almsaeed Studio
reserves the right to change the license of future releases.

Todo List
---------
- ~~Light sidebar colors~~ (Done v2.1.0)
- ~~Right sidebar~~ (Done v2.1.0)
- ~~Minified main-sidebar~~ (Done v2.1.0)
- Right to left support
- ~~Custom pace style~~ (Done v2.3.1)

Legacy Releases
----------------
AdminLTE 1.x can be easily upgraded to 2.x using [this guide](https://almsaeedstudio.com/themes/AdminLTE/documentation/index.html#upgrade), but if you intend to keep using AdminLTE 1.x, you can download the latest release from the [releases](https://github.com/almasaeed2010/AdminLTE/releases) section above.

Change log
----------
**For the most recent change log, visit the [releases page](https://github.com/almasaeed2010/AdminLTE/releases) or the [changelog file](https://github.com/almasaeed2010/AdminLTE/blob/master/changelog).** We will add a detailed release notes to each new release. 

Image Credits
-------------
[Pixeden](http://www.pixeden.com/psd-web-elements/flat-responsive-showcase-psd)

[Graphicsfuel](http://www.graphicsfuel.com/2013/02/13-high-resolution-blur-backgrounds/)

[Pickaface](http://pickaface.net/)

[Unsplash](https://unsplash.com/)

[Uifaces](http://uifaces.com/)

Donations
---------
Donations are **greatly appreciated!**

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif "AdminLTE Presentation")](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=629XCUSXBHCBC "Donate")

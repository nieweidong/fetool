# 大前端工具集

> 本篇文章记录了一枚程序猿的百宝箱。

> 主要内容是一些使用过的库、工具、套路或关注的前端组织等等，反正用 **前端瑞士军刀** 来总结这篇文章再合适不过鸟。

#### 您可以通过以下方式联系到我：
- 微博 [@聂微东](http://weibo.com/darrencode "Darren 聂微东")
- 个人 Blog [fefork.com](http://www.fefork.com/ "一枚 Web 技术领域的手艺人")
- 博客园 [犀利的东哥](http://www.cnblogs.com/Darren_code/ "关注前端技术")
- QQ 群 **214199415**，群名__前端 Club__。PS：入群务必请提供 __有内容的 git 或 blog 地址__，否则进不去哈:)

---

## 目录
- [前端组织](#org)
- [前端博客](#blogs)
- [博客搭建](#blogbuild)
- [CSS](#css)
- [浏览端 JS](#javascript)
- NodeJS
  - [推荐 Package](#RecPackageForNode)
  - [Node 学习资料](#RecBookForNode)
- [Build 项目构建](#build)
  - [Gulp 推荐包](#gulp)
- 精选阅读
  - [前端技术](#fedev)
  - [前端面试](#interview)
  - [Nodejs](#nodejsdev)
  - [其他技术](#otherdev)
- 工具/软件
  - [Web](#web)
  - [APP](#app)
    - [Android](#android)
    - [iPhone](#iphone)
  - [Mac](#mac)
  - [Linux](#linux)
- [Chrome 浏览器插件](#BrowserPlugins)
- [Git](#git)
- [Redis](#redis)
- [MongoDB](#mongodb)
- [杂七杂八](#other)
- [前端炫技-__炫酷狂拽叼炸天的 Web__](#cool)
- [设计/交互](#ux)
- [速查手册](#handbook)
- [小结](#summary)
- [TODO](#todo)

## 正文

<h3 id="org">前端组织</h3>

> 虽混过外企俩家，但劳资英文这项的技能点还是灰色的...so，俺关注的站点主要以中文为主

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[GitHub](https://github.com) |★★★★★ |劳资清楚这不是个纯粹的前端社区... 但作为全球最大的搞基社区，无数前端项目在这启航 没 Git 都不好意思面基有木有！
[MDN](https://developer.mozilla.org/zh-CN/) |★★★★★ |不解释，无数的资源再等着你探索
[Awesomes.cn](http://www.awesomes.cn/) |★★★★☆ |国人维护的前端资源库，深度对接到 Github
[慕课](http://www.imooc.com/) |★★★★☆ |大量的在线计算机课程。 虽然初、中级居多，但是不乏有巨作值得细细品尝
[W3Cplus](http://www.w3cplus.com/) |★★★★☆ |大漠(《图解 CSS3》作者)在国内的影响力杠杠的 Sass 专家级
[百度 FEX](http://fex.baidu.com/) |★★★★ |代表作 FIS、UEditor、WebUploader、KityMinder
[前端乱炖](http://www.html-js.com) |★★★☆ |前端社区太多，乱炖还算做的不错的
[极客学院](http://www.jikexueyuan.com/course/web/) |★★★ |和慕课类似，但是内容更杂、更丰富 PS：貌似比较新颖的教程都是收费的
[Div.IO](http://div.io/digg) |★★★ |主要内容是最新的前端库和前沿技术
[腾讯全端 AlloyTeam](http://www.alloyteam.com/) |★★★ |腾讯 Web 前端团队

<h3 id="blogs">前端博客</h3>

> 值得长期占坑的前端个人博客，都是偶经常关注的

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[如何跟上前端开发的最新前沿](https://uptodate.frontendrescue.org/zh/) |★★★★★ |RT
[阮一峰](http://javascript.ruanyifeng.com/) |★★★★★ |关注多年，拜读其 ES6 系列... 虽网传靠写书进鸟阿里，但博客内容确实够丰富
[粉丝日志 for 张丹](http://blog.fens.me/) |★★★★★ |大爱作者写的 Node 系列
[张鑫旭](http://www.zhangxinxu.com/wordpress/) |★★★★★ |成名多年的、高产的前端大湿

<h3 id="blogbuild">博客搭建</h3>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[hexo](https://hexo.io/zh-cn/) |★★★★★ |快速、简洁且高效的博客框架
[jekyll](http://jekyll.bootcss.com/) |★★★★ |将纯文本转化为静态网站和博客
[Tumblr](https://www.tumblr.com/) |★★★ |轻博客的祖师爷
[Wordpress](https://zh-cn.wordpress.com/) |★ |这玩意古老到我都不想介绍鸟

> ___使用 ```hexo/jekyll + GitPage```，前端搭建静态博客那是相当 easy。用 Markdown 写文章做记录，再 push 到 Git 上，分分钟高大上有木有___

<h4 id="css">CSS</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[MetroUI](http://metroui.org.ua/) |★★★★☆ |好看好用，重点是样式特别、个性
[LoadersCSS](https://connoratherton.com/loaders) |★★★★☆ |用 CSS 技术实现 loading 动画； 补一句，想熟悉、理解 ```keyframes、animation、transform、transition``` 的童鞋可以直接去读其源码(只有千把行代码)，读完就算出师鸟:)
[WeUI](https://github.com/weui/weui) |★★★★☆ |一套同微信原生视觉体验一致的基础样式库 为微信 Web 开发量身设计，令用户的使用感知更加统一
[PostCSS](https://github.com/postcss/postcss) |★★★★☆ |最近才知道大名鼎鼎[Autoprefixer](https://github.com/postcss/autoprefixer)是其插件 推荐大漠的文章[《PostCSS深入学习》](http://www.w3cplus.com/PostCSS/postcss-deep-dive-what-you-need-to-know.html)，有关 PostCSS 不是什么？PostCSS 是什么？PostCSS 可以做什么等等问题，文章里面有答案
[CSSgram](https://github.com/una/CSSgram) |★★★★ |图片滤镜库，终于可以用 CSS 在 web 上实现滤镜的效果鸟 IE不支持，不过新的移动设备支持没问题 [Can I Use](http://caniuse.com/#search=CSS%20Blend%20Modes)
[HINT.css](https://github.com/chinchang/hint.css) |★★★★ |一款非常小巧的提示框效果
[Hover.css](http://ianlunn.github.io/Hover/) |★★★★ |很多鼠标 Hover 态的效果，可以给产品学习一下:)
[Cursor](http://css-cursor.techstream.org/) |★★★★ |记录各浏览器对Cursor的支持情况
[csscss](https://github.com/zmoazeni/csscss) |★★★★ |用于检查 CSS 代码冗余
[purecss](http://purecss.io/) |★★★☆ |小巧的响应式 CSS 库，Yahoo!出品
[cssmatic](http://www.cssmatic.com) |★★★ |一个帮忙调试CSS效果的工具

<h4 id="javascript">浏览端 JS</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[requirejs](https://github.com/jrburke/requirejs) |★★★★★ |JS模块化是构建复杂项目的第一步 中文学习文档奉上：[RequireJS 中文网](http://www.requirejs.cn/)
[ECharts](http://echarts.baidu.com/index.html) |★★★★★ |好用，最关键的是支持的图表展示非常之多，强烈推荐
[Swiper](http://www.swiper.com.cn) |★★★★★ |强大的 Slider 库 其实这类效果库非常多，但文档能那么专业的就很少鸟
[fullPage](http://alvarotrigo.com/fullPage/) |★★★★☆ |非常好用的全屏滑动库，看 Demo 就明白
[PhotoSwipe](http://photoswipe.com/) |★★★★☆ |偶常用的 js 库 官网上有这么一句很关键、重要"no dependencies"
[Vuejs](http://cn.vuejs.org) |★★★★☆ |比较喜欢其作者... 所以劳资正在看源码学习学习
[favico.js](http://lab.ejci.net/favico.js/) |★★★★☆ |动态改变浏览器标签栏中的网站图标，非常好玩
[ant.design](http://ant.design) |★★★★☆ |淘宝搞的良心项目，文档美好的令人发指 样式优雅，强烈推荐内部系统尝试此库
[nodePPT](https://github.com/ksky521/nodePPT) |★★★★ |前同事三水的大作，好用必须得支持:) 用 Markdown 写 PPT，还可以 HTML 混排，上手飞快
[peity.js](http://benpickles.github.io/peity/) |★★★★ |jQuery的图表插件，特别cute，感觉萌萌哒 将HTML转换成一个小的```<svg>```饼图、圆环图、折线图等等
[emojify.js](https://github.com/Ranks/emojify.js) |★★★★ |能够将```emoji```关键词转换为```emoji```图片的```JS```插件 可以快速的为你的网站提供```emoji```表情支持
[Highcharts](http://www.hcharts.cn/)|★★★★ |Highcharts 中文网，又是一个图表库 确实功能强大，但是觉得不好看... PS：官网就做的不好看，脏脏的赶脚
[NProgress](https://github.com/rstacruz/nprogress/) |★★★★ |使页面加载时有更好的loading效果
[Noticejs](https://github.com/jaredreich/notie.js) |★★★★ |一个简单的通知库，木有依赖
[onepage-scroll](https://github.com/peachananr/onepage-scroll) |★★★☆ |依赖 jQuery 的单页滚动库，和 [fullPage](http://alvarotrigo.com/fullPage/) 类似
[videojs](http://videojs.com/) |★★★☆ |当下视频需求都用上```<video>```鸟 样式和交互统一的问题交给 videojs 搞定:)
[clipboard](http://zenorocha.github.io/clipboard.js/) |★★★☆ |仅 2KB 大小，搞定剪贴板功能，屌不屌~ 但是，Safari 不支持...
[impress.js](https://github.com/impress/impress.js) |★★☆ | 用来写 PPT 不错，偶也曾为其写过一篇[impress.js 初体验](http://www.cnblogs.com/Darren_code/archive/2013/01/04/impressjs.html)
[Cropper](http://fengyuanchen.github.io/cropper/) |★★☆ |国人开发的图片裁剪库

> ___```Swiper/PhotoSwipe/fullPage``` 有这仨库，微信里常见的 H5 页完全不是问题哒___

### NodeJS

> 作为一名大前端甚至是多端，Node 绝逼是必备的一块

> 社区活跃、部署方便都是令我对 Node 爱不释手的主要原因

<h4 id="RecPackageForNode">推荐 Package</h4>

##### 这里介绍些有特色且前端有必要知道的包

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[anywhere](https://www.npmjs.com/package/anywhere) |★★★★★ |随时随地将你的当前目录变成一个静态文件服务器的根目录
[supervisor](https://www.npmjs.com/package/supervisor) |★★★★★ |监控 Node 代码，自动重启。 A supervisor program for running nodejs programs
[nodemon](https://github.com/remy/nodemon) |★★★★★ |监控 Node 代码，自动重启。 Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.
[pm2](https://www.npmjs.com/package/pm2) |★★★★★ |是一个带有负载均衡功能的 Node 应用的进程管理器； 是 [Forever](https://www.npmjs.com/package/forever) 的进阶库，想了解的可以看这篇文章[《拥抱PM2》](http://se77en.cc/2013/06/27/goodbye-node-forever-hello-pm2-translation/)
[async](https://www.npmjs.com/package/async) |★★★★☆ |一个流程控制工具包，提供直接而强大的异步功能
[lodash](https://www.npmjs.com/package/lodash) |★★★★☆ |JS 工具库 ```Underscore.js```的一个 fork 发展而来
[socket.io](https://github.com/socketio/socket.io) |★★★★☆ |预计 Node 的实时框架 聊天室、页游等对实时性有高要求的较适用
[Mongoose](https://github.com/Automattic/mongoose) |★★★★☆ |让 NodeJS 更容易操作 Mongodb 数据库；  附上一篇[Mongoose 学习参考文档](https://cnodejs.org/topic/504b4924e2b84515770103dd)
[CNPM](http://npm.taobao.org/) |★★★★☆ |淘宝 NPM 镜像，提供了 NPM 同步的服务 当然可不仅仅这样，利用 CNPM 可以打造__企业/个人__私有的 NPM 服务 推荐篇搭建私有NPM的文章：[《CNPM搭建私有的NPM服务》](http://blog.fens.me/nodejs-cnpm-npm/)
[koa](http://koajs.com/) |★★★★☆ |玩 Node 都知道 express，但使用 koa 的就少很多，门槛比 Ex 稍高 通过 generator 避免繁琐的回调函数嵌套，强烈推崇 [官方的文章教程](https://github.com/turingou/koa-guide)
[Shipit](https://github.com/shipitjs/shipit) |★★★★☆ |一个强大的自动化部署工具。 shipit 很多地方非常类似 gulp，他们的核心都是任务系统。
|[node-inspector](https://www.npmjs.com/package/node-inspector) |★★★★☆ |Node 调试工具，使用起来跟 Chrome 的 JS 调试器很相似
[winston](https://www.npmjs.com/package/winston) |★★★★☆ |Node 服务最流行的日志库之一
[co](https://www.npmjs.com/package/co) |★★★★☆ |用 generator 写法让异步代码同步
[thenify-all](https://www.npmjs.com/package/thenify-all) |★★★★ |把异步的方法变成 Promise 的 Promisifies all the selected functions in an object
[PhantomJS](http://phantomjs.org/) |★★★★ |一般用来做抓取截图和无界面测试 也可以用来操作 DOM 和网络监测，很好玩的库 [Quick Start](http://phantomjs.org/quick-start.html)
[Mocha](https://github.com/mochajs/mocha) |★★★★ |Node 里最常用的测试框架； 它支持多种 Node 的 Assert libs； 同时支持异步和同步的测试，同时支持多种方式导出结果； 也支持直接在 browser 上跑 JS 代码测试。
[everyauth](https://www.npmjs.com/package/everyauth)|★★★★ |OAuth 的集成解决方案
[shelljs](http://documentup.com/shelljs/shelljs) |★★★☆ |写 Node 时难免需要用 shell 去操作些神马 shelljs 是基于 Node 的 shell 工具，API 及其简单
[hashids](https://www.npmjs.com/package/hashids) |★★★☆ |看名称就懂，给 userid 加解密用的
[colors](https://www.npmjs.com/package/colors) |★★☆ |花俏的小工具 让打印```console.log```时有更好的展示样式
[n](https://www.npmjs.com/package/n) |★★ |控制Node的版本，想升级一行代码搞定

> ```supervisor``` 和 ```nodemon``` 这俩都是监控 Node 代码，使得每次修改代码后会，开发 Node 程序必备

> 以上库俺都有使用过，甚至有不少都是项目开发中、各种特定场景下必用的，有任何使用问题欢迎沟通哈:)

<h4 id="RecBookForNode">Node 学习指南</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[Node.js 中文资料导航](https://github.com/youyudehexie/node123) |★★★★★ |Node 的中文资料导航，```start1300+```
[从零开始 NodeJS 系列文章](http://blog.fens.me/series-nodejs/) |★★★★★ |基本上每一篇都看过，强烈推荐
[Node.js 包教不包会](http://nqdeng.github.io/7-days-nodejs/) |★★★★★ |值得阅读，看完绝不用买书鸟
[七天学会 NodeJS](https://github.com/alsotang/node-lessons) |★★★★★ |劳资还没看，不过看目录还不错:)
[Style Guide](https://github.com/dead-horse/node-style-guide) |★★★★ |这是一份关于如何写出一致且美观的 ```Node.js``` 代码的风格指南

<h3 id="build">Build 项目构建</h3>

> Gulp + Webpack 的使用__套路__参考: [learning-gulp](https://github.com/demohi/learning-gulp)

> Gulp 资料收集：[use-gulp](https://github.com/Platform-CUF/use-gulp)

> 推荐篇与 Webpack 相关的文章《[CSS Modules](http://boke.io/tan-tan-css-modules/)》

> Webpack 用起来吼吼：[webpack-howto](https://github.com/petehunt/webpack-howto)

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[pm2](https://www.npmjs.com/package/pm2) |★★★★★ |是一个带有负载均衡功能的 Node 应用的进程管理器； 是 [Forever](https://www.npmjs.com/package/forever) 的进阶库，想了解的可以看这篇文章[《拥抱PM2》](http://se77en.cc/2013/06/27/goodbye-node-forever-hello-pm2-translation/)
[Webpack](http://webpack.github.io/) |★★★★★ |项目构建工具，由于过于复杂和太强大，所以劳资还没去深入研究。
[Gulp](https://github.com/gulpjs/gulp/) |★★★★★ |Gulp 是基于 Node 实现 Web 前端自动化开发的工具。 学习资料附上[GulpBook](https://github.com/nimojs/gulp-book)
[Bower](http://bower.io/) |★★★★☆ |前端项目的包管理其实是件复杂的事 谁谁谁依赖谁谁谁，谁谁谁依赖谁谁谁的某个版本...卧槽 Bower 就是搞定这件事儿的，亲爹是 Twitter 推荐篇 Bower 的中文文章：[《bower 解决 js 的依赖管理》](http://blog.fens.me/nodejs-bower-intro/)
[Grunt](http://gruntjs.com/) |★★★★☆ |和 Gulp 类似，都是项目构建的常见选择 对比这俩的文章可谓不少，推荐篇[《Gulp vs Grunt》](http://www.benben.cc/blog/?p=407) 英盲又想看文档，可以去[Grunt 中文网](http://www.gruntjs.net/)
[FIS](http://fex-team.github.io/fis3/) |★★★★ |度厂出品的前端构建工具 文档清晰，功能强大，推荐了解和使用
[Gitlab CI](https://ci.gitlab.org/) |★★★ |一套基于[Gitlab](https://about.gitlab.com/)的持续集成服务

<h4 id="gulp">Gulp 推荐包</h4>

> Gulp 最基础的库就不列在下表格中鸟，其中包括：
  - [gulp-concat](https://www.npmjs.com/package/gulp-concat) 作用是___连接/合并___文件
  - [gulp-cssshrink](https://www.npmjs.com/package/gulp-cssshrink) CSS 文件压缩
  - [gulp-uglify](https://www.npmjs.com/package/gulp-uglify) JS 文件压缩

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[gulp-webpack](https://www.npmjs.com/package/gulp-webpack) |★★★★★ |webpack 与 gulp 配合，开启前端 Build 新纪元 webpack plugin for gulp
[gulp-rev](https://www.npmjs.com/package/gulp-rev) |★★★★☆ |高大上第一步，静态文件名称变成 HASH 名称
[gulp-rev-collector](https://www.npmjs.com/package/gulp-rev-collector) |★★★★☆ |配合[gulp-rev](https://www.npmjs.com/package/gulp-rev)使用，自动用 HASH 替换模板内静态文件名
[run-sequence](https://www.npmjs.com/package/run-sequence) |★★★★ |Gulp 任务机制为并行，RS 使得有依赖的任务可串行执行 使用 gulp-rev 时得用 RS 配合 要不并行的生成配置和处理.html 文件不能同事生效
[gulp-util](https://www.npmjs.com/package/gulp-util) |★★★★ |内含一套方法库，功能太多 个人感觉更喜欢功能单一的包，不太喜欢这种大杂烩
[gulp-connect](https://www.npmjs.com/package/gulp-connect) |★★★★ |有 reload 功能的 Run WebServer 工具 我一般用来 LivereLoad，即保存之后自动刷新页面
[gulp-load-plugins](https://www.npmjs.com/package/gulp-load-plugins) |★★★★ |可加载 package.json 内与 Gulp 相关的插件 省去鸟一行一行 require 的功夫咯
[gulp-clean](https://www.npmjs.com/package/gulp-clean) |★★★☆ |移除文件或文件夹的包
[gulp-replace](https://www.npmjs.com/package/gulp-replace) |★★★☆ |其功能看名字就知道，用做字符串替换的
[gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) |★★★☆ |叼炸天的自动处理浏览器前缀的包 文档地址：[usage](https://github.com/postcss/autoprefixer#usage)
[gulp-rename](https://www.npmjs.com/package/gulp-rename) |★★★ |把文件重命名 结构设计的好不太会用到这个
[gulp-flatten](https://www.npmjs.com/package/gulp-flatten) |★★★ |删除或替换文件的相对路径； 一般我这用来移动 img 或者其他静态文件到新目录 同上：结构设计的好不太会用到这个

### 精选阅读

<h4 id="fedev">前端技术</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[2015D2前端论坛](http://www.imooc.com/learn/590) |★★★★★ |Node方向的非常非常值得看，相信东哥推荐哈
[前端开发规范手册](http://zhibimo.com/read/Ashu/front-end-style-guide/index.html) |★★★★☆ | 此手册主要实现的目标：代码一致性和最佳实践
[ECMAScript 6入门](http://es6.ruanyifeng.com/) |★★★★☆ |阮一峰大神所著，一本开源的JS教程 全面介绍 ECMAScript 6新引入的语法特性
[ReactNative 中文版](http://wiki.jikexueyuan.com/project/react-native/) |★★★★☆ |翻译自官方的中文文档
[ReactWebpackCookBook](https://fakefish.github.io/react-webpack-cookbook/index.html) |★★★★☆  |此书会引导读者是进入```React```和```Webpack```的世界。 俩都是非常前沿的技术，同时使用会更有趣。
[ReactNative 学习指南](https://github.com/ele828/react-native-guide) |★★★☆ |新玩意层出不穷... 对于能持续学习的童鞋，这是个美好的时代
[HTML/CSS 编码规范](http://www.css88.com/doc/codeguide/) |★★★☆ |编写灵活、稳定、高质量的```HTML```和```CSS```代码的规范
[移动前端入门](http://gold.xitu.io/entry/56c29abfa34131005b8cb1f3) |★★★☆ |入门价值高，移动方向常见问题的较好总结
[GulpBook](https://github.com/nimojs/gulp-book) |★★★☆ |Gulp 是基于 Node 实现 Web 前端自动化开发的工具

<h4 id="interview">前端面试</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[在 LinkedIn 做面试官的故事](http://dongfei.baijia.baidu.com/article/52449) |★★★★★ |非面试题，介绍 LinkedIn 的面试过程 文章有很多中肯的建议和想法，推荐阅读
[大漠：写给前端面试者](http://www.w3cplus.com/css/write-to-front-end-developer-interview.html) |★★★★★ |这篇文章不涉及任何的面试题 大漠与大家聊聊面试者与被面者之间的感受...
[前端面试题](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Chinese) |★★★★☆ |Git 上非常火的前端面试题，```start17k+```
[前端面经](https://github.com/paddingme/Front-end-Web-Development-Interview-Question) |★★★★ |主要内容是些前端面试笔试题和面试套路，值得阅读

<h4 id="nodejsdev">Nodejs</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[Node.js 中文资料导航](https://github.com/youyudehexie/node123) |★★★★★ |Node 的中文资料导航，```start1300+```
[从零开始 NodeJS 系列文章](http://blog.fens.me/series-nodejs/) |★★★★★ |基本上每一篇都看过，强烈推荐
[Node.js 包教不包会](http://nqdeng.github.io/7-days-nodejs/) |★★★★★ |值得阅读，看完绝不用买书鸟
[七天学会 NodeJS](https://github.com/alsotang/node-lessons) |★★★★★ |劳资还没看，不过看目录还不错:)
[stream-handbook](https://github.com/jabez128/stream-handbook) |★★★★☆ |如果学习 NodeJS，那么流一定是需要掌握的概念

<h4 id="otherdev">其他技术</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[MongoDB 极简实践入门](https://github.com/StevenSLXie/Tutorials-for-Web-Developers/blob/master/MongoDB%20%E6%9E%81%E7%AE%80%E5%AE%9E%E8%B7%B5%E5%85%A5%E9%97%A8.md) |★★★★☆ |入门推荐的套路，非常浅显易懂
[Mac 设置指南](https://github.com/macdao/ocds-guide-to-setting-up-mac) |★★★★ |Mac 使用必看 尤其适合 偏执狂/强迫症 患者:)
[Markdown 资料](https://github.com/xirong/my-markdown) |★★★ |简单看些语法入门，快速用起来

<h3>工具/软件</h3>

<h4 id="web">Web</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[CanIuse](http://caniuse.com/) |★★★★★ |__前端必备__；查看浏览器对各种新特性的兼容情况
[overapi](http://overapi.com/) |★★★★★ |最全的开发人员在线速查手册
[百度脑图](http://naotu.baidu.com) |★★★★☆ |非常方便的思维导图工具
[ProcessOn](https://www.processon.com/) |★★★★☆ |和百度脑图的功能类似，脑图工具。
[VimAwesome](http://vimawesome.com/) |★★★★☆ |Vim 插件集合，__Vim 党必备__
[Tower](https://tower.im) |★★★★☆ |小而美的多人协同工具。 不光只有 Web 版，还有 iPhone、iPad、Android、微信版。
[Slides](https://slides.com/) |★★★★☆ |一个所见即所得的 WebPPT 编辑器，非常推荐
[faviconer.co](http://www.faviconer.co/) |★★★★ |一个所见即所得的icon生成器，很好用
[smallpdf](http://smallpdf.com/cn) |★★★★ |提供各种格式和 PDF 互相转换
[Cmd Markdown](https://www.zybuluo.com/mdeditor) |★★★★ |好用的 Web 版 Markdown 编辑器
[StackEdit](https://stackedit.io/editor) |★★★★ |又是一款 Web 版 Markdown 编辑器
[墨刀](https://modao.cc/) |★★★★ |一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。
[htm2pdf](http://www.htm2pdf.co.uk)|★★★★ |HTML to PDF
[Speaker Deck](https://speakerdeck.com/p/featured) |★★★★ |在线的演讲稿展示平台

<h4 id="app">APP</h4>

> 以下列表中的 APP 都是不区分系统平台的

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[印象笔记](https://www.yinxiang.com/) |★★★★★ |免费账号完全够用，跨平台跨终端的记录软件
[365日历](http://www.365rili.com/) |★★★★ |首先肯定比系统自带的日历强大，要不推荐个蛋蛋 俺一般用来搞目标管理，比如学习计划和工作计划 生活中会订阅演唱会、电影首映的信息
[多看阅读](http://www.duokan.com/) |★★★★ |kindle 确实好，但是懒得随身带着 多看还算不错，书较多且偶尔有特价比较爽

<h5 id="android">Android</h5>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[小米桌面](http://zhuomian.xiaomi.com/) |★★★★☆ |多好看、多漂亮谈不上，关键是没有广告

<h5 id="iphone">iPhone</h5>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[Surge](https://itunes.apple.com/cn/app/surge-web-developer-tool-proxy/id1040100637?mt=8&v0=WWW-GCCN-ITSTOP100-PAIDAPPS&l=&ign-mpt=uo%3D4) |★★★★ |非免费 牛逼的网络开发与调试工具，前端必备
[Monkey](https://github.com/coderyi/Monkey) |★★★★ |Monkey 是 iPhone 上一个 GitHub 第三方客户端。 展示 GitHub 上的开发者的排名，以及仓库的排名

<h4 id="mac">Mac</h4>

> 对于美好事务的追求无论何时都不算晚，前年公司给配了台 Mac 用做测试开发机，于是开始在 Mac 下办公。 __Windows？__ 回不去鸟...

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[Homebrew](http://brew.sh/) |★★★★★ |没它程序猿没法好好干活... ```Homebrew```使```OS X```更完美。 使用```gem```来安装```gems```、用```brew```来搞定那些依赖包
[iTerm2](http://www.iterm2.com/) |★★★★☆ |Mac 终端功能少又不好看，iTerm2 可以解救你~  推荐篇文章：[《让你的命令行丰富多彩》](http://swiftcafe.io/2015/07/25/iterm/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
[BrowseShot](https://itunes.apple.com/cn/app/browseshot/id615916400) |★★★★☆ |偶正在使用的网页截图工具，强烈推荐
[BeyondCompare](http://www.scootersoftware.com) |★★★★☆ |在Windows下就开始用了 比对文件和文件夹杠杠好使，Merge必备工具
[CheatSheet](http://www.mediaatelier.com/CheatSheet/) |★★★★ |能够显示当前程序的快捷键列表，默认的快捷键是长按 ⌘
[Sequel Pro](http://www.sequelpro.com) |★★★★ |免费好用的Mysql工具
[LICEcap](http://www.cockos.com/licecap/) |★★★★ |屏幕录制工具，支持导出 GIF 动画图片格式 轻量级、使用简单，录制过程中可以改变录屏范围
[Manico](http://manico.im/) |★★★★ |快捷启动和切换 APP 的工具，高效的第一步 AppStore 上收费，不过可以免费试用
[WebStorm](http://www.jetbrains.com/webstorm/) |★★★★ |功能超强的前端 IDE，不多介绍，谁用谁知道 PS：貌似俺插件装多了，用着卡卡的，风扇呼呼转...
[Atom](https://atom.io) |★★★★ |2015 年 7 月之前，在桌面环境下我最喜欢的编辑器是 Sublime。 但之后就是 Atom，俺也专门为它写了篇___[使用纪要](https://github.com/nieweidong/learn-atom)___
[马克鳗](http://www.getmarkman.com/) |★★★★ |MarkMan，非常强大好用的标注、测量工具。 日常工作免费版就完全可以满足，__强烈推荐__
[Wireshark](https://www.wireshark.org/) |★★★☆ |说实话，Mac 下木有 Fiddler 挺不习惯，不过在有更强大的替代品
[SourceTree](https://www.sourcetreeapp.com/) |★★★☆ |一款好用的的 Git 客户端工具，重点是支持中文:)
[focus booster](https://www.focusboosterapp.com/) |★★★ |因为比较在意时间管理，所以这软件是俺工作时间的必备之物
[Mou](http://25.io/mou/) |★★ |小清新的 Markdown 编辑器

<h4 id="linux">Linux</h4>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[oh-my-zsh](http://ohmyz.sh/) |★★★★★ |___终端党___ 必用的好工具，强烈推荐
[tree](http://www.cnblogs.com/iadanac/p/3859481.html) |★★★★ |linux 以树状图逐级列出目录的内容
[oneapm](http://www.oneapm.com/) |★★★★ |强大的运维工具，提供多种监控客户端； 有采集、分析、展示等一套功能； PS：我这用了服务器监控(免费哦)
[httpie](https://github.com/jkbrzt/httpie) |★★★☆ |一个 CLI 中的 HTTP 客户端 用法简单、易读

<h3 id="BrowserPlugins">Chrome 浏览器插件</h3>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[JSONView](https://github.com/gildas-lormeau/JSONView-for-Chrome) |★★★★★ |麻麻再也不用担心偶调试接口啦
[wappalyzer](https://wappalyzer.com/) |★★★★☆ |分析网站使用的技术 它可以检测网页的 Web 服务器、JS 框架等等
[Postman](https://www.getpostman.com/) |★★★★ |强大的调试工具，推荐之
[gitShare](https://github.com/LukyVj/gitShare) |★★★★ |用于方便把Github项目分享到 Twitter 或 Facebook
[二维码生成器](https://chrome.google.com/webstore/detail/%E4%BA%8C%E7%BB%B4%E7%A0%81qr%E7%A0%81%E7%94%9F%E6%88%90%E5%99%A8/pflgjjogbmmcmfhfcnlohagkablhbpmg) |★★★★ |RT
[User-Agent Switcher](http://spoofer-extension.appspot.com/) |★★★★ |模拟各种终端的 UA，达到调试目的
[GitPlug](https://porter.io/plug/) |★★★☆ |在 Git 项目页中嵌入有关的图表信息
[Swap My Cookie](https://chrome.google.com/webstore/detail/swap-my-cookies/dffhipnliikkblkhpjapbecpmoilcama) |★★★☆ |切换马甲非常方便
[Infinity](http://infinitynewtab.com/) |★★☆ |针对 Chrome 的插件，__新标签页__ 会让你耳目一新

<h3 id="git">Git</h3>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[Git 教程-廖雪峰](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) |★★★★☆ |俺有看过不少 Git 的文章，确实这个系列是最通俗易懂的
[GitAwards](http://github-awards.com/) |★★★★ |Git 工具，可以查看 Git 排名
[Git 速查](https://github.com/flyhigher139/Git-Cheat-Sheet/blob/master/Git%20Cheat%20Sheet-Zh.md) |★★★★ |分类清晰的速查表
[Git 简明指南](http://rogerdudler.github.io/git-guide/index.zh.html) |★★★☆ |入门```Git```的简明指南，木有高深内容:)
[Git 学习资料整理](https://github.com/xirong/my-git)|★★★ |内容包括很多 Git 的相关资料，```star 1200+```
[GitHub 漫游指南](https://github.com/phodal/github-roam) |★★☆ |一篇还算不错的 Git 学习总结，就是乱了点... 我理解作者___漫游___的意思是漫无目的想到哪写到哪~ 看到作者为鸟达成 Git 连击的成就，也是蛮拼的:)

<h3 id="redis">Redis</h3>

<h3 id="mongodb">MongoDB</h3>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[Mongoose](https://github.com/Automattic/mongoose) |★★★★☆ |让 NodeJS 更容易操作 Mongodb 数据库。  附上一篇[Mongoose 学习参考文档](https://cnodejs.org/topic/504b4924e2b84515770103dd)

<h3 id="other">杂七杂八</h3>

> 放些开发中较有用的杂物在这儿

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[租房要点](https://github.com/soulteary/tenant-point) |★★★★☆ |适用于北上广深杭，大城市打拼__租房__确实是硬伤
[QQ 群规](https://github.com/jsfront/src/blob/master/qq.md) |★★★★☆ |突然某天，有个 QQ 群让我加群 原本我是拒绝的，但当我看完这篇 QQ 群规后... 劳资真的被感动到了，太牛逼、够专业！ 最后，我默默加群鸟:)
[.gitignore 文件](https://github.com/github/gitignore) |★★★★☆ |介绍不同语言项目的 gitignore 模板
[git-draw](https://github.com/ben174/git-draw) |★★★ |黑魔法，可以修改自己Git上的Contributions
[Codebabes](https://codebabes.com/) |★★★ |学编程的网站。 重点是每通过一个测试，尼玛对应的妞会脱一件衣服... PS：要翻墙哦~
[ReadmeSample](https://github.com/nieweidong/ReadmeSample)|☆ |项目高大上的第一步就是__包装__，所以来看看 ```README``` 的书写套路吧 PS：劳资怎么这么无聊...

<h3 id="cool">前端炫技-_炫酷狂拽叼炸天站点_</h3>

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[windows93](http://www.windows93.net/) |★★★★☆ |模拟 Win93 桌面，思路、体验和整体效果比较有意思
[GeekTyper](http://geektyper.com/) |★★★★☆ |好玩又具有 Geek 精神的网站，虽然创建的目的是个恶作剧 PS：网站需要翻墙
[前端技能栈](http://skill.phodal.com/) |★★★★ |好玩的前端技能栈展示
[Mapbox](https://www.mapbox.com/) |★★★★ |非常叼的开源项目，有方便的 JSAPI(还有 SDK)。 不过免费版只能浅尝，流量有限。 PS：网站需要翻墙
[Clark Duvall](http://www.clarkduvall.com/) |★★★★ |一枚歪果仁的个人blog，范儿叼叼的
[SuperScrollorama](http://johnpolacek.github.io/superscrollorama/) |★★★☆ |好玩好看的动画库，链接是 SuperScrollorama 的展示页
[parallax.js](http://matthew.wagerfield.com/parallax/) |★★★ |一个视差引擎的官网，在电脑和手机上都有很好的体验
[CSS字母](http://yusugomori.com/projects/css-sans/fonts) |★★ |用CSS实现英文字母，叼叼的
[墨刀](https://modao.cc/) |★★ |一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。

<h3 id="ux">设计/交互</h3>

> 作为负责最终效果呈现的前端工程师，多少得了解些 __设计和交互__ 的，这也是为什么 fetool 会单独的存在这一章...当然话又说回来了，偶毕业的第一份工作是设计:)

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[站酷](http://www.zcool.com.cn/works/) |★★★★☆ |里面好东西太多，俺当年真没少再上面淘素材
[UI中国](http://www.ui.cn/list.html) |★★★★ |光听名字就知道有多高大上鸟:)

<h3 id="handbook">速查手册</h3>

> RT，这篇都是些文档或者API，一般这类东西都在大家浏览器的书签内，偶这也列一下大前端常用的手册地址

 名称 | 推荐指数 | 备注/说明
 ----- | ----- | ------
[百度CDN公共库](http://cdn.code.baidu.com/) |★★★★☆ |基本常见的库都收录拉，搞 demo 的时候特方便
[HTML 和 CSS 代码规范](http://codeguide.bootcss.com/) |★★★★☆ |编写灵活、稳定、高质量的 HTML 和 CSS 代码的规范
[Linux命令中文手册](http://linux.51yip.com) |★★★★ |木有系统的好好学习 Linux，所以命令更不熟悉 真羡慕那些CLI玩的飞起的:)
[Git 速查](https://github.com/flyhigher139/Git-Cheat-Sheet/blob/master/Git%20Cheat%20Sheet-Zh.md) |★★★★ |分类清晰的速查表
[jQueryAPI 1.11.3](http://jquery.cuishifeng.cn/) |★★★★ |ZeptoAPI 基本和 jQuery 一样，所以看一份就好
[CSS3](http://www.php100.com/manual/css3_0/index.html) |★★★★ |CSS3 的在线手册
[Express API](http://www.expressjs.com.cn/4x/api.html) |★★★☆ |中文手册:) 4.x和3.x都有
[CI用户指南](http://codeigniter.org.cn/user_guide/index.html) |★★ |一个轻量级的 PHP 框架用户指南 推荐指数低的原因是劳资PHP比较弱，囧
[Yaf](http://www.laruence.com/manual/) |★★ |鸟哥(惠新宸)所写的 PHP 框架 推荐指数低的原因同上...


<h3 id="summary">小结</h3>

##### 背景
  俺算个比较能自我总结的码农，所以偶尔喜欢写点东西做些记录或者自我熏陶陶醉一下。
  可写着写着发现```Evernote```里面的东西太尼玛多(乱)了，于是想着把一些技术相关的资料都整理整理，都丢到```Git```上沉淀下来。 这样Evernote就可以只需要记录些偏生活方便的，看着清爽一些...

  所以，这篇记录其实只是为偶自己而写，确信以后也一直会这样~~~

##### 说说目标
  其实与这篇记录类似的文章太多鸟，俺也不愿意成为一个单纯的收集资料，分享资料的这么个东西。
  我希望 fetool 能更生动、更个性，最好能更另类点，对于每样工具的思考和解析更多点，吐槽也必须有理有据，然后再配上劳资收集的 low 图，完美！
  __希望通过不停的完善这篇记录，能Push劳资多了解业内的新玩具和新创意，然后围绕这些新东西，客观的再写点好东西，比如文章、资料、开源项目这些，让其他伙伴们少走弯路或学的更顺畅点儿__

> 所以劳资对自己的要求是：这篇记录里列出的每样东西，自己都得的去了解、去尝试，然后再列出来。 能举一反三最好，如果达不到至少也能清楚的认识：列出来的这玩意对程序员有没有卵用，解决了啥痛点。

<h3 id="todo">TODO</h3>

1. 继续完善和扩充内容

2. “备注/说明”这一栏不够犀利，希望再多加入自己的理解、点评、吐槽，让这篇记录更犀利和生动

3. 支持导出多种格式，如```.pdf```、```.epub```、```.mobi```等

4. 后续看看如果有必要，可以单独搞个页面，优化下阅读和展示效果

---

以下是 [@拔赤](http://weibo.com/jayli) 总结的前端技能图：
![拔赤总结的前端技能图](https://raw.githubusercontent.com/nieweidong/fetool/master/img/fe.jpg)

---

完善 ing，慢慢把 __Evernote__ 和 __浏览器书签__ 里面的好东西慢慢捣腾到这儿，更欢迎 PR，谢谢。

<img src="https://raw.githubusercontent.com/nieweidong/fetool/master/img/me.jpg" width="120" height="120" style="border-radius: 60px;" />

#### 用自己青涩时的照片镇楼，哇哈哈~

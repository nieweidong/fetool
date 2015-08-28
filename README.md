# 大前端工具集

<img src="https://raw.githubusercontent.com/nieweidong/fetool/master/img/me.jpg" width="120" height="120" style="border-radius: 60px;" />

> 本篇文章记录了一名前端的工具集。主要内容是一些使用过的库、工具、套路或关注的前端组织等等，反正用 **前端瑞士军刀** 来总结这篇文章再合适不过鸟。

#### 您可以通过以下方式联系到我：
- 微博 [@聂微东](http://weibo.com/darrencode "Darren 聂微东")
- 个人Blog [fefok.com](http://www.fefork.com/ "一枚Web技术领域的手艺人")
- 博客园 [犀利的东哥](http://www.cnblogs.com/Darren_code/ "关注前端技术")
- QQ群 **214199415**，群名前端Club。PS:入群__务必请提供git或blog地址__，否则进不去哈:)

---

以下是[拔赤](http://weibo.com/jayli)总结的前端技能图：
![拔赤总结的前端技能图](https://raw.githubusercontent.com/nieweidong/fetool/master/img/fe.jpg)

---

## 目录
- [前端组织](#org)
- [前端博客](#blogs)
- [博客搭建](#blogbuild)
- [CSS](#css)
- [浏览端JS](#javascript)
- Node
  - [推荐Package](#RecPackageForNode)
  - [Node学习资料](#RecBookForNode)
- [Build 项目构建](#build)
- [精选阅读](#read)
- [前端面试](#interview)
- 工具/软件
  - [Web](#web)
  - [APP](#app)
  - [Mac](#mac)
  - [Linux](#linux)
- [浏览器插件](#BrowserPlugins)
- [Git](#git)
- [Redis](#redis)
- [MongoDB](#mongo)
- [杂七杂八](#other)
- [前端炫技-__炫酷狂拽叼炸天的Web__](#cool)

## 正文

<h3 id="org">前端组织</h3>

> 虽混过外企俩家，但劳资英文这项的技能点还是灰色的...so，俺关注的站点主要以中文为主

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Git |https://github.com |劳资清楚这不是个纯粹的前端社区... 但作为全球最大的搞基社区，无数前端项目在这启航。 用啦都说好:)|
|MDN |https://developer.mozilla.org/zh-CN/ |不解释，无数的资源再等着你探索 |
|慕课 |http://www.imooc.com/ |大量的在线计算机课程。 虽然初、中级居多，但是不乏有巨作值得细细品尝 |
|极客学院 |http://www.jikexueyuan.com/course/web/ |和慕课类似，但是内容更杂、更丰富 |
|W3Cplus |http://www.w3cplus.com/ |大漠(《图解CSS3》作者)在国内的影响力杠杠的 |
|前端乱炖 |http://www.html-js.com |前端社区太多，乱炖还算做的不错的 |
|Div.IO |http://div.io/digg |berg牵头打造的前端信息聚合网站，分享内容有最新的库和前沿技术 |

<h3 id="blogs">前端博客</h3>

> 值得长期占坑的前端个人博客，都是偶经常关注的

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|阮一峰 |http://javascript.ruanyifeng.com/ |关注多年，拜读其ES6系列... 虽网传靠写书进鸟阿里，但是博客内容确实够丰富，值得重点关注 |
|粉丝日志for张丹 |http://blog.fens.me/ |大爱作者写的Node系列 |
|张鑫旭 |www.zhangxinxu.com/wordpress/ |成名多年的、高产的前端大湿 |

<h3 id="blogbuild">博客搭建</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Tumblr |https://www.tumblr.com/ |轻博客的祖师爷 |
|Wordpress |https://zh-cn.wordpress.com/ |这玩意古老到我都不想介绍鸟 |
|hexo |https://hexo.io/zh-cn/ |快速、简洁且高效的博客框架 |
|jekyll |http://jekyll.bootcss.com/ |将纯文本转化为静态网站和博客 |

> ___使用 ```hexo/jekyll + GitPage```，前端搭建静态博客那是相当easy。用Markdown写文章做记录，再push到Git上，分分钟高大上有木有___

<h4 id="css">CSS</h4>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|LoadersCSS |https://connoratherton.com/loaders |用CSS技术实现loading动画； 补一句，想熟悉、理解 ```keyframes、animation、transform、transition``` 的童鞋可以直接去读其源码(只有千把行代码)，读完就算出师鸟:) |
|Hover.css |http://ianlunn.github.io/Hover/ |很多鼠标Hover态的效果，可以给产品学习一下:) |
|purecss |http://purecss.io/ |非常小巧、强大的响应式CSS库,Yahoo!出品 |
|csscss |https://github.com/zmoazeni/csscss |用于检查css代码冗余 |

<h4 id="javascript">浏览端JS</h4>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Swiper |http://www.swiper.com.cn |强大的Slider库 其实吧，这类效果库非常多，但文档能那么专业的就很少鸟 |
|PhotoSwipe |http://photoswipe.com/ |偶常用的js库 官网上有这么一句很关键、重要"no dependencies" |
|fullPage |http://communitylocals.com/ |非常好用的全屏滑动库，看demo就明白 |
|Vuejs |http://cn.vuejs.org |比较喜欢其作者... 所以劳资正在看源码学习学习 |
|Cropper |http://fengyuanchen.github.io/cropper/ |国人开发的图片裁剪库 |
|Echarts |http://echarts.baidu.com/index.html |好用，最关键的是支持的图表展示非常之多，强烈推荐 |
|impress.js|https://github.com/impress/impress.js | 用来写PPT不错，偶也曾为其写过一篇[impress.js初体验](http://www.cnblogs.com/Darren_code/archive/2013/01/04/impressjs.html)|

> ___```Swiper/PhotoSwipe/fullPage``` 有这仨库，微信里常见的H5页完全不是问题哒___

<h3>Node</h3>

<h4 id="RecPackageForNode">推荐Package</h4>

##### 这里介绍些有特色且前端有必要知道的包

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|supervisor |https://www.npmjs.com/package/supervisor |监控Node代码，自动重启。 A supervisor program for running nodejs programs |
|nodemon |https://github.com/remy/nodemon |监控Node代码，自动重启。 Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.|
|pm2 |https://www.npmjs.com/package/pm2 |是一个带有负载均衡功能的Node应用的进程管理器 |
|async |https://www.npmjs.com/package/async |一个流程控制工具包，提供直接而强大的异步功能 |
|thenify-all |https://www.npmjs.com/package/thenify-all |Promisifies all the selected functions in an object |
|koa |http://koajs.com/ |玩Node都知道express，但是koa使用的人就少很多，门槛比Ex稍高一点点。 通过generator避免繁琐的回调函数嵌套，强烈推崇。[官方的文章教程](https://github.com/turingou/koa-guide) |
|Shipit |https://github.com/shipitjs/shipit |一个强大的自动化部署工具。 shipit很多地方非常类似gulp，他们的核心都是任务系统。
|Mocha |https://github.com/mochajs/mocha |JS测试框架，可用于Node或者浏览器中 |

> ```supervisor``` 和 ```nodemon``` 这俩都是监控Node代码，使得每次修改代码后会，开发Node程序必备

<h4 id="RecBookForNode">Node学习指南</h4>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|node.js中文资料导航 |https://github.com/youyudehexie/node123 |Node的中文资料导航，```start1300+``` |
|Node.js 包教不包会 |http://nqdeng.github.io/7-days-nodejs/ |PS:劳资还没看，不做评价 |
|七天学会NodeJS |https://github.com/alsotang/node-lessons |PS:劳资还没看，不做评价 |
|从零开始nodejs系列文章 |http://blog.fens.me/series-nodejs/ |基本上每一篇都看过，强烈推荐 |

<h3 id="build">Build 项目构建</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Gitlab CI |https://ci.gitlab.org/ |一套基于[Gitlab](https://about.gitlab.com/)的持续集成服务 |
|Webpack |http://webpack.github.io/ |项目构建工具，由于过于复杂和太强大，所以劳资还没去深入研究。 [精选阅读](#read)中有篇资料就是介绍Webpack和React的工作机制。 |
|Bower |http://bower.io/ |一句话解释：A package manager for the web |

<h3 id="read">精选阅读</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|React-Native学习指南 |https://github.com/ele828/react-native-guide |新玩意层出不穷，对于那些能持续学习的童鞋，这是个美好的时代。 |
|react-webpack-cookbook |https://fakefish.github.io/react-webpack-cookbook/index.html |这本小书的目的是引导你进入```React```和```Webpack```的世界。 他们两个都是非常有用的技术，如果同时使用他们，前端开发会更加有趣。 |
|MongoDB 极简实践入门 |https://github.com/StevenSLXie/Tutorials-for-Web-Developers/blob/master/MongoDB%20%E6%9E%81%E7%AE%80%E5%AE%9E%E8%B7%B5%E5%85%A5%E9%97%A8.md |入门推荐的套路，非常浅显易懂入门推荐的套路，非常浅显易懂 |

<h3 id="interview">前端面试</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|大漠：写给前端面试者 |http://www.w3cplus.com/css/write-to-front-end-developer-interview.html |这篇不涉及任何的面试题，大漠和大家聊聊面试者与被面者之间的感受... |

<h3>工具/软件</h3>

<h4 id="web">Web</h4>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|CanIuse |http://caniuse.com/ |__前端必备__；查看浏览器对各种新特性的兼容情况 |
|smallpdf |http://smallpdf.com/cn |提供各种格式和pdf互相转换 |
|Cmd Markdown |https://www.zybuluo.com/mdeditor |好用的Web版Markdown编辑器 |
|StackEdit |https://stackedit.io/editor |又是一款Web版Markdown编辑器 |
|墨刀 |https://modao.cc/ |一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。 |
|htm2pdf|www.htm2pdf.co.uk/index.php |HTML to PDF |
|Speaker Deck |https://speakerdeck.com/p/featured |在线的演讲稿展示平台 |
|VimAwesome |http://vimawesome.com/ |Vim插件集合，__Vim党必备__ |
|百度脑图 |http://naotu.baidu.com |非常方便的思维导图工具 |
|Tower|https://tower.im |小而美的多人协同工具。 不光只有Web版，还有iPhone、iPad、Android、微信版。 |

<h4 id="app">APP</h4>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Monkey |https://github.com/coderyi/Monkey |Monkey是iPhone上一个GitHub第三方客户端。 展示 GitHub 上的开发者的排名，以及仓库的排名 |

<h4 id="mac">Mac</h4>

> 对于美好事务的追求无论何时都不算晚，游行从2014年开始在Mac下办公(公司配的)
> Windows？回不去了...

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Wireshark |https://www.wireshark.org/ |说实话，Mac下木有Fiddler挺不习惯，不过在有更强大的替代品 |
|马克鳗 |http://www.getmarkman.com/ |MarkMan，非常强大好用的标注、测量工具。 日常工作免费版就完全可以满足，__强烈推荐__ |
|Mou |http://25.io/mou/ |快速好用的Markdown编辑器 |
|WebStorm |http://www.jetbrains.com/webstorm/ |功能超强的前端IDE，不多介绍，谁用谁知道 |
|Atom |https://atom.io |2015年7月之前，在桌面环境下我最喜欢的编辑器是Sublime。 但之后就是Atom，俺也专门为它写了篇___[使用纪要](https://github.com/nieweidong/learn-atom)___ |
|focus booster |https://www.focusboosterapp.com/ |因为比较在意时间管理，所以这软件是俺工作时间的必备之物 |
|SourceTree |https://www.sourcetreeapp.com/ |一款好用的的Git客户端工具，重点是支持中文:) |

<h4 id="linux">Linux</h4>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|oh-my-zsh |http://ohmyz.sh/ |___终端党___必用的好工具 |
|oneapm |http://www.oneapm.com/ |强大的运维工具。 提供多种监控客户端，有采集、分析、展示等一套功能；我这用了服务器监控(免费哦) |

<h3 id="BrowserPlugins">浏览器插件</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Infinity |http://infinitynewtab.com/ |针对Chrome的插件，__新标签页__会让你耳目一新 |

<h3 id="git">Git</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Git教程-廖雪峰 |http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000 |俺有看过不少Git的文章，确实这个系列是最通俗易懂的 |
|Git速查 |https://github.com/flyhigher139/Git-Cheat-Sheet/blob/master/Git%20Cheat%20Sheet-Zh.md |分类清晰的速查表 |
|Git简明指南 |http://rogerdudler.github.io/git-guide/index.zh.html |助你入门```Git```的简明指南，木有高深内容:) |


<h3 id="redis">Redis</h3>

<h3 id="mongodb">MongoDB</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|Mongoose |https://github.com/Automattic/mongoose |让NodeJS更容易操作Mongodb数据库；  附上一篇[Mongoose学习参考文档](https://cnodejs.org/topic/504b4924e2b84515770103dd) |

<h3 id="other">杂七杂八</h3>

> 放些开发中较有用的杂物在这儿

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|gulp-book |https://github.com/nimojs/gulp-book |Gulp是基于Node实现Web前端自动化开发的工具 |
|.gitignore文件 |https://github.com/github/gitignore |介绍了不同语言项目的gitignore模板 |

<h3 id="cool">前端炫技-_炫酷狂拽叼炸天站点_</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|windows93 |http://www.windows93.net/ |模拟Win93桌面，思路、体验和整体效果比较有意思 |
|GeekTyper |http://geektyper.com/ |非常好玩的、具有Geek精神的网站，虽然创建的目的就是个恶作剧。 PS：网站需要翻墙 |
|墨刀 |https://modao.cc/ |一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。 |
|Mapbox |https://www.mapbox.com/ |非常叼的开源项目，有方便的JSAPI(还有SDK)。 不过免费版只能浅尝，流量有限。 PS：网站需要翻墙 |
|parallax.js |http://matthew.wagerfield.com/parallax/ |一个视差引擎的官网，在电脑和手机上都有很好的体验 |
|SuperScrollorama |http://johnpolacek.github.io/superscrollorama/ |好玩好看的动画库，链接是SuperScrollorama的展示页 |

---

完善ing，慢慢把 __Evernote__ 和 __浏览器书签__ 里面的好东西慢慢捣腾到这儿，更欢迎PR，谢谢。

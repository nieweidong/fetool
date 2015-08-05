# Toolbox

<img src="http://www.fefork.com/images/me.jpg" width="120" height="120" style="border-radius: 60px;" />

> 本篇文章记录了一名前端的工具集。主要内容是一些使用过的库、工具、套路或关注的前端组织等等，反正用 **前端瑞士军刀** 来总结这篇文章再合适不过了。

#### 您可以通过以下方式联系到我：
- 微博 [@聂微东](http://weibo.com/darrencode "Darren 聂微东")
- 个人Blog [fefok.com](http://www.fefork.com/ "一枚Web技术领域的手艺人")
- 博客园 [犀利的东哥](http://www.cnblogs.com/Darren_code/ "关注前端技术")
- QQ群 **214199415**，群名前端Club。PS:入群__务必请提供git或blog地址__，否则进不去哈:)

## 目录
- [前端炫技-__炫酷狂拽叼炸天的Web__](#101)
- [前端组织](#201)
- [前端博客](#801)
- [库/框架](#301)
- [Node](#401)
  - [推荐Package](#402)
  - [Node学习指南](#403)
- [精选好书&学习资料](#501)
- [前端面试](#601)
- [工具/软件](#901)
  - [Web](#902)
  - [APP](#903)
  - [Mac](#904)
  - [Linux](#905)
- [杂七杂八](#701)
  - [浏览器插件](#702)
  - [Git](#703)

## 正文

<h3 id="101">前端炫技-_炫酷狂拽叼炸天站点_</h3>

| 名称 | 地址 | 备注/说明 |
| ----- | ----- | ------ |
|windows93 |http://www.windows93.net/ |模拟Win93，整体体验和效果比较有意思 |
|GeekTyper |http://geektyper.com/ |非常好玩的一个网站，虽然创建的目的就是个恶作剧 —— “GeekTyper was inspired by the various media where hacking is usually portrayed incorrectly”。 PS：网站需要翻墙|
|墨刀 |https://墨刀.com/ |这是个在线移动应用原型制作工具，旨在帮助产品经理快速制作可在手机端展示的移动应用原型。 |
|Mapbox |https://www.mapbox.com/ |非常叼的开源项目，有方便的JSAPI(还有SDK)，不过免费版只能浅尝，流量有限。 PS：网站需要翻墙 |
|parallax.js |http://matthew.wagerfield.com/parallax/ |一个视差引擎的官网，在电脑和手机上都有很好的体验 |

<h3 id="201">前端组织</h3>
> 虽然混过俩家外企，但劳资英文阅读能力确实有限，所以俺关注的站点都以中文为主

- [Git](https://github.com) 全球最大的搞基社区，用了都说好:)
- [MDN](https://developer.mozilla.org/zh-CN/) 不解释，无数的资源再等着你探索
- [慕课](http://www.imooc.com/) 大量的在线课程，虽然初、中级居多，但是不乏有巨作值得细细品尝
- [W3Cplus](http://www.w3cplus.com/) 大漠(《图解CSS3》作者)在国内的影响力杠杠的
- [前端乱炖](www.html-js.com) 前端社区太多，乱炖还算做的不错的

<h3 id="801">前端博客</h3>
> 值得长期占坑的前端个人博客，都是偶经常关注的

- [阮一峰](http://javascript.ruanyifeng.com/) 已经关注多年...虽网传靠写书进了阿里，但是站内的内容确实丰富，值得占坑长期关注
- [粉丝日志for张丹](http://blog.fens.me/) 大爱作者写的Node系列
- [张鑫旭](www.zhangxinxu.com/wordpress/) 成名多年的、高产的前端大湿

<h3 id="301">库/框架</h3>
> Swiper/PhotoSwipe/fullPage 有了这仨库，微信里常见的H5页完全不是问题了
- [Swiper](www.swiper.com.cn) 强大的Slider库，其实这类效果库非常之多，但是中文文档能那么专业的就很少了
- [PhotoSwipe](http://photoswipe.com/) 我常用的js库，官网上有这么一句很关键、重要"no dependencies"
- [fullPage](http://communitylocals.com/) 非常好用的全屏滑动库，看demo就明白是做什么的了

- [Vuejs](http://cn.vuejs.org) 比较喜欢其作者，所以劳资正在看源码学习学习
- [Cropper](http://fengyuanchen.github.io/cropper/) 国人开发的图片裁剪库
- [LoadersCSS](https://connoratherton.com/loaders) 点连接就明白做什么了；补一句，对keyframes、animation、transform、transition不熟悉的盆友可以直接直接去读其源码(只有千把行代码)，读完就算出师了:)
- [purecss](http://purecss.io/) 非常小巧、强大的响应式CSS库,Yahoo!出品
- [bower](http://bower.io/) A package manager for the web
- [csscss](https://github.com/zmoazeni/csscss) 用于检查css代码冗余
- [Mocha](https://github.com/mochajs/mocha) JS测试框架，可用于NodeJS或者浏览器中

> 有了hexo/jekyll + GitPage，前端搭建博客那是相当easy了。用mk写文章做记录，再push到Git上，分分钟高大上有木有
- [hexo](https://hexo.io/zh-cn/) 快速、简洁且高效的博客框架
- [jekyll](http://jekyll.bootcss.com/) 将纯文本转化为静态网站和博客

<h3 id="401">Node</h3>
<h4 id="402">推荐Package</h4>

##### 这里介绍些有特色且前端有必要知道的包
> 下面这俩都是监控Node代码，使得每次修改代码后会自动重启，开发Node程序必备
> - [supervisor](https://www.npmjs.com/package/supervisor) A supervisor program for running nodejs programs
> - [nodemon](https://github.com/remy/nodemon) Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.


- [pm2](https://www.npmjs.com/package/pm2) Production process manager for Node.JS applications with a built-in load balancer.
- [async](https://www.npmjs.com/package/async) Higher-order functions and common patterns for asynchronous code
- [thenify-all](https://www.npmjs.com/package/thenify-all) Promisifies all the selected functions in an object
- [koa](http://koajs.com/) express肯定不用介绍了，但是koa就相对于知道的人就少很多。通过generator避免了重复繁琐的回调函数嵌套，值得深入了解哦。[官方的文章教程](https://github.com/turingou/koa-guide)
- [Shipit](https://github.com/shipitjs/shipit) 一个强大的自动化部署工具；shipit很多地方非常类似gulp，他们的核心都是任务系统。

<h4 id="403">Node学习指南</h4>
- [node.js中文资料导航](https://github.com/youyudehexie/node123) NodeJS的中文资料导航，```start1300+```
- [Node.js 包教不包会](http://nqdeng.github.io/7-days-nodejs/) PS:劳资还没看，不做评价
- [七天学会NodeJS](https://github.com/alsotang/node-lessons) PS:劳资还没看，不做评价
- [从零开始nodejs系列文章](http://blog.fens.me/series-nodejs/) 基本上每一篇都看过，强烈推荐

<h3 id="501">精选好书&学习资料</h3>
- [React-Native学习指南](https://github.com/ele828/react-native-guide) 新玩意层出不穷，对于那些能持续学习的童鞋，这是个美好的时代。
- [react-webpack-cookbook](https://fakefish.github.io/react-webpack-cookbook/index.html) 这本小书的目的是引导你进入 React 和 Webpack 的世界。他们两个都是非常有用的技术，如果同时使用他们，前端开发会更加有趣。

<h3>前端面试</h3>
- [大漠：写给前端面试者](http://www.w3cplus.com/css/write-to-front-end-developer-interview.html) 这篇文章中，将不涉及任何的面试题，大漠只想和大家聊聊面试者与被面者之间的感受。


<h3 id="901">工具/软件</h3>

<h4 id="902">Web</h4>
- [CanIuse](http://caniuse.com/) __前端必备__；查看浏览器对各种新特性的兼容情况
- [smallpdf](http://smallpdf.com/cn) 提供各种格式和pdf互相转换
- [墨刀](https://墨刀.com/) 这是个在线移动应用原型制作工具，旨在帮助产品经理快速制作可在手机端展示的移动应用原型
- [Cmd Markdown](https://www.zybuluo.com/mdeditor) 好用的Web版Markdown编辑器
- [StackEdit](https://stackedit.io/editor) 又是一款Web版Markdown编辑器
- [htm2pdf](www.htm2pdf.co.uk/index.php) HTML to PDF conversion for your website or application
- [Speaker Deck](https://speakerdeck.com/p/featured) 在线的演讲稿展示平台
- [VimAwesome](http://vimawesome.com/) Vim插件集合，__Vim党必备__

<h4 id="903">APP</h4>

<h4 id="904">Mac</h4>
- [Wireshark](https://www.wireshark.org/) 说实话，没有Fiddler挺不习惯，不过在Mac上有更强大的替代品
- [马克鳗](http://www.getmarkman.com/) 英文名MarkMan，非常强大好用的标注、测量工具，日常工作免费版就完全可以满足，强烈推荐
- [Mou](http://25.io/mou/) 快速好用的Markdown编辑器
- [WebStorm](http://www.jetbrains.com/webstorm/) 功能超强的前端IDE，不多介绍，谁用谁知道
- [focus booster](https://www.focusboosterapp.com/) 因为偶比较在意时间管理，所以这软件是偶上班时间的必备之物
- [Atom](https://atom.io) 2015年7月之前，在桌面环境下我最喜欢的编辑器是Sublime，但之后就是Atom，为它俺也专门写了一篇___[使用纪要](https://github.com/nieweidong/learn-atom)___

<h4 id="905">Linux</h4>
- [oh-my-zsh](http://ohmyz.sh/) 务必强大好用的工具
- [oneapm](http://www.oneapm.com/) 强大的运维工具，提供多种监控客户端，有采集、分析、展示等一套功能；俺这用了服务器监控(免费)

<h3 id="701">杂七杂八</h3>
> 放些开发中较有用的杂物在这儿

- [VimAwesome](http://vimawesome.com/) Vim插件集合，__Vim党必备__

<h4 id="702">浏览器插件</h4>


<h4 id="703">Git</h4>
- [Git教程-廖雪峰](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) 俺有看过不少Git的文章，确实这个系列是最通俗易懂的。
- [Git速查](https://github.com/flyhigher139/Git-Cheat-Sheet/blob/master/Git%20Cheat%20Sheet-Zh.md) 分类清晰的速查表
- [Git简明指南](http://rogerdudler.github.io/git-guide/index.zh.html) 助你入门 git 的简明指南，木有高深内容 ;)

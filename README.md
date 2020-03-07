# ![ts-logo](media/ts-favicon-96x96.png) Awesome TypeScript

![awesome](media/awesome.svg)  ![license](media/creative-commons.svg)

[TypeScript](https://www.typescriptlang.org/) is a free and open source programming language developed by Microsoft. It is a superset of JavaScript and essentially adds optional static typing and class-based object-oriented programming to the language.

> Awesome TypeScript inspired by  [dzharii/awesome-typescript](https://github.com/dzharii/awesome-typescript)，Thanks [dzharii](https://github.com/dzharii)。

The resources of this article are mainly from the following websites：

[![sf-favicon.ico](media/sf-favicon.ico)](https://segmentfault.com/) [![juejin-favicon](media/juejin-favicon.ico)](https://juejin.im/timeline) [![zhihu-favicon](media/zhihu-favicon.ico)](https://www.zhihu.com/explore) [![jianshu-favicon](media/jianshu-favicon.ico)](https://www.jianshu.com/) [![toutiao-favicon](media/toutiao-favicon.ico)](https://toutiao.io/) [![medium-favicon](media/medium-favicon.ico)](https://medium.com/)[![github-favicon](media/github-favicon.ico)](https://github.com/)

[Chinese](https://github.com/semlinker/awesome-typescript/blob/master/README-zh.md) | [English](https://github.com/semlinker/awesome-typescript/blob/master/README.md)

**阅读更多关于 Angular、TypeScript、Node.js/Java 、Spring 等技术文章，欢迎访问我的个人博客或关注我的公众号 —— [全栈修仙之路](http://www.semlinker.com/)**

![fer_road_qrcode](media/fer_road_qrcode.jpg)

### Semlinker's Blog

#### TypeScript Basic

- [TypeScript 交叉类型](http://www.semlinker.com/ts-intersection-types/)
- [TypeScript 枚举类型](http://www.semlinker.com/ts-enum-type/)
- [TypeScript never 类型](http://www.semlinker.com/ts-never-type/)

#### TypeScript Design Pattern

- [TypeScript 设计模式之单例模式](http://www.semlinker.com/ts-singleton-pattern/)

- [TypeScript 设计模式之观察者模式](http://www.semlinker.com/ts-observer-pattern/)
- [TypeScript 设计模式之适配器模式](http://www.semlinker.com/ts-adapter-pattern/)
- [TypeScript 设计模式之模板方法](http://www.semlinker.com/ts-template-method/)
- [TypeScript 设计模式之享元模式](http://www.semlinker.com/ts-flyweight-pattern/)

## Contents

<!-- TOC -->

- [Awesome TypeScript](#ts-logomediats-favicon-96x96png-awesome-typescript)
    - [Contents](#contents)
    - [TypeScript Tutorials](#typescript-tutorials)
        - [Features](#features)
        - [Chinese](#chinese)
            - [Beginner](#beginner)
            - [Advanced](#advanced)
            - [Practical](#practical)
        - [English](#english)
            - [Features](#features-1)
            - [Tutorials](#tutorials)
            - [Samples](#samples)
            - [Guide](#guide)
            - [Awesome](#awesome)
    - [TypeScript Starters/Boilerplates](#typescript-startersboilerplates)
    - [TypeScript Design patterns](#typescript-design-patterns)
    - [TypeScript Videos](#typescript-videos)
        - [Chinese](#chinese-1)
        - [English](#english-1)
    - [TypeScript QA](#typescript-qa)
    - [TypeScript Books](#typescript-books)
        - [Chinese](#chinese-2)
        - [English](#english-2)
    - [TypeScript Tools/Libraries/frameworks](#typescript-toolslibrariesframeworks)
        - [Build](#build)
            - [webpack](#webpack)
            - [gulp](#gulp)
            - [grunt](#grunt)
            - [compiler](#compiler)
            - [linter](#linter)
        - [Ioc](#ioc)
        - [Doc](#doc)
        - [Data Structure](#data-structure)
        - [Database](#database)
        - [Server](#server)
    - [TypeScript IDE](#typescript-ide)
        - [Offline](#offline)
            - [IDE/Plugins](#ideplugins)
        - [Online](#online)
            - [Playground](#playground)
            - [Chrome Extension](#chrome-extension)
    - [Contributing](#contributing)
        - [Guide](#guide-1)

<!-- /TOC -->

## TypeScript Tutorials

### Features

- [蚂蚁金服数据体验技术团队 - TypeScript体系调研报告](https://juejin.im/post/59c46bc86fb9a00a4636f939)
- [Vilicvane - TypeScript 2.0 新特性一览](https://zhuanlan.zhihu.com/p/21629069)
- [Vilicvane - TypeScript 2.1 新特性一览](https://zhuanlan.zhihu.com/p/24267683)
- [Vilicvane - TypeScript 2.2 新特性一览](https://zhuanlan.zhihu.com/p/25579011)
- [Vilicvane - TypeScript 2.3 新特性一览](https://zhuanlan.zhihu.com/p/27349475)
- [Microsoft - TypeScript 2.4 新特性一览](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript)
- [Vilicvane - TypeScript 2.5~2.6 新特性一览](https://zhuanlan.zhihu.com/p/30760290)
- [黄子毅 - 精读<<TypeScript2.0 - 2.9>>](https://zhuanlan.zhihu.com/p/37374083)
- [Linux中国 - 一篇缺失的 TypeScript 介绍](https://zhuanlan.zhihu.com/p/28494162)
- [单纯的土豆 - ES5, ES2015 和 TypeScript 的区别](http://www.jianshu.com/p/3c8c7713fa0e)
- [三七二十 - TypeScript 的好处都有啥？和 JavaScript 的区别在哪？](https://zhuanlan.zhihu.com/p/38526585)
- [Grain 先森 - 前端-TypeScript VS JavaScript 深度对比](https://www.jianshu.com/p/0dfbcd4a0757)
- [贺贺v5 - Angular2、Ionic、TypeScript、es6的关系？](http://www.jianshu.com/p/27c026734b8d)
- [极客学院 - 使用 TypeScript 提高开发能力](http://www.jianshu.com/p/066a6017db1b)
- [Hevin - 为什么 Reddit 选择了 TypeScript？](https://zhuanlan.zhihu.com/p/27695708)
- [JiaXinYi - Angular: 我们为什么选择 TypeScript](https://segmentfault.com/a/1190000010892897)
- [Djcordhose - 对比 Flow 和 TypeScript](http://djcordhose.github.io/flow-vs-typescript/flow-typescript-2.html#/)
- [Neal1991 - 采用 Flow 以及 TypeScript](https://github.com/neal1991/articles-translator/blob/master/%E9%87%87%E7%94%A8Flow%E4%BB%A5%E5%8F%8ATypeScript.md)
- [柳佳 - Flow vs Typescript](https://zhuanlan.zhihu.com/p/27593029)
- [SDK.cn - Slack 的 TypeScript 之路](https://sdk.cn/news/6789)
- [RDDcoding - 熟悉全栈 TypeScript](https://segmentfault.com/a/1190000014414303)
- [Lxxyx - TypeScript - 不止稳，而且快](http://www.lxxyx.win/2017/07/23/2017/ts-accerlate/)
- [Zhangwang - TypeScript - 一种思维方式](https://zhuanlan.zhihu.com/p/63346965)
- [Lienviws - TypeScript 安利指南](https://juejin.im/post/5d8efeace51d45782b0c1bd6)

### Chinese

#### Beginner

- [Xcatliu - TypeScript 入门教程](https://ts.xcatliu.com/)
- [Taobaofed - 认识 TypeScript](http://taobaofed.org/blog/2017/03/09/head-first-typescript/)
- [Shangpudxd - TypeScript 入门](http://www.jianshu.com/p/4e7094d62b34)
- [Muyunyun - 从 JavaScript 到 TypeScript](http://muyunyun.cn/posts/66a54fc2/)
- [Gukson - Typescript基础入门](https://www.jianshu.com/p/103933b7c2b4)
- [oWSQo - TypeScript 入门](https://www.jianshu.com/p/c4e639296b98)
- [Semlinker - TypeScript 简介及编码规范](https://semlinker.com/ts-intro-and-guide/)
- [技术胖 - TypeScript图文视频教程](https://juejin.im/post/5ba43b38f265da0aef4e0bc6)

#### Advanced

- [Zhongsp - TypeScript Handbook (中文版)](https://zhongsp.gitbooks.io/typescript-handbook/content/)
- [Bjcl - TypeScript 教程](https://www.w3cschool.cn/typescript/)
- [Jason - 你所不知道的 Typescript 与 Redux 类型优化](https://zhuanlan.zhihu.com/p/32112508)
- [王亦斯 - 巧用 Typescript](https://zhuanlan.zhihu.com/p/39620591)
- [三毛 - 巧用 TypeScript （一）](https://jkchao.cn/article/5bb9c63963a5d23d5ce3091b)
- [三毛 - 巧用 TypeScript （二）](https://jkchao.cn/article/5bde8fdf94307c57d4c8d37a)
- [三毛 - 巧用 TypeScript （三）](https://jkchao.cn/article/5befe57994307c57d4c8d383)
- [三毛 - 巧用 TypeScript （四）](https://jkchao.cn/article/5c162137e35fb85c4c7e1278)
- [三毛 - 巧用 TypeScript （五）](https://jkchao.cn/article/5c8a4d99e53a054fad647c15)
- [Square - TypeScript 3.0 元组类型的用法和一些奇技淫巧](https://zhuanlan.zhihu.com/p/38687656)
- [Square - Typescript 类型高级技巧，和强约束 bind 的实现](https://zhuanlan.zhihu.com/p/38789971)
- [腾讯NEXT学位 - 深入 TypeScript 的类型系统](https://zhuanlan.zhihu.com/p/38081852)
- [newraina - 手把手教写 TypeScript Transformer Plugin](https://zhuanlan.zhihu.com/p/30360931)
- [EER - TypeScript 重构 Axios 经验分享](https://juejin.im/post/5bf7f1c0e51d455ed74f625c)
- [三毛 - 深入理解 TypeScript](https://jkchao.github.io/typescript-book-chinese/)
- [Poetry - Typescript 实践总结[基础+工程+实践]](http://blog.poetries.top/2019/09/03/ts-in-action/)
- [Shanyue - TypeScript 高级技巧](https://juejin.im/post/5cffb431f265da1b7401f466)

#### Practical

**Angular**

- [Yanxiaodi - Ionic 2 With TypeScript](https://www.gitbook.com/book/yanxiaodi/ionic2-guide/details)
- [Cacivy - Angular 2 + TypeScript 实现的 Cnode 社区](https://juejin.im/entry/5811c2cba22b9d00639f69f5)

**Vue**

- [薯条真的好好吃哦 - almost最好的Vue + Typescript系列01 环境搭建篇](https://segmentfault.com/a/1190000013676663)
- [toBeTheLight - Vue 2.5中将迎来有关TypeScript的改进！](https://segmentfault.com/a/1190000011474717)
- [盘风 - Vue2.5+ Typescript 引入全面指南](https://segmentfault.com/a/1190000011853167)
- [腾讯Bugly - vuejs+ts+webpack2框架的项目实践](https://mp.weixin.qq.com/s/p2Uc9IV284MXbRHhV2Vf-g)
- [LinkFly - 从 JavaScript 到 TypeScript 6 - Vue 引入 TypeScript](https://segmentfault.com/a/1190000011520912)
- [SimonZhanglTer - 可能是最全的Vue-TypeScript教程(附实例代码和一键构建工具)](https://segmentfault.com/a/1190000012486378)
- [三命 - vue + typescript 进阶篇](https://segmentfault.com/a/1190000011878086)
- [qiangdada - TypeScript + 大型项目实战](https://juejin.im/post/5b54886ce51d45198f5c75d7)
- [距离 - Vue全家桶+TypeScript使用总结](https://segmentfault.com/a/1190000013462418)
- [海蓝2018 - vue全家桶+Typescript开发一款习惯养成APP](https://segmentfault.com/a/1190000014884801)
- [Treri - 使用FIS3 和 TypeScript 实现 vue-hackernews-2.0](https://juejin.im/entry/58d8d603b123db199f4639a3)
- [🍼holyZhengs - 记录一次基于vue、typescript、pwa的项目由开发到部署](https://juejin.im/post/5ba3d205e51d450e8477af33)
- [大转转FE - 原有vue项目接入typescript](https://mp.weixin.qq.com/s?__biz=MzU0OTExNzYwNg==&mid=2247484478&idx=1&sn=a1222cc6d327fe80690b71e4398a27a2&chksm=fbb58ff7ccc206e12b5e2d57fb7cf84f8fe31dce3213e9b2c9ea00d5555873ddbb68ff2fde84&token=1712114111&lang=zh_CN&rd2werd=1#wechat_redirect)
- [MartinYin - 使用typescript+vue 编写电影信息小项目！](https://juejin.im/post/5bc2fd06e51d450e7903c783)
- [三毛 - 在 Vue 中使用 TypeScript 的一些思考（实践）](https://jkchao.cn/article/5b3d3bbef9d34142a117b184)

**React**

- [fi3ework - 基于 React + TypeScript 的网易云音乐](https://juejin.im/post/5b715796e51d4566334ca28c)
- [iKcamp - 翻译 | 开始使用 TypeScript 和 React](https://juejin.im/post/595cc34ff265da6c3d6c262b)
- [贾顺名 - TypeScript在react项目中的实践](https://segmentfault.com/a/1190000016163937)
- [花生毛豆 - TypeScript 在 React 中使用总结](https://juejin.im/post/5bab4d59f265da0aec22629b)
- [icepy - 复杂 React 应用中的TypeScript 3.0实践](https://zhuanlan.zhihu.com/p/42141179)
- [蚂蚁金服数据体验技术团队 - TypeScript 实践](https://juejin.im/post/5a9c004a6fb9a028b92c9e91)
- [蚂蚁金服数据体验技术团队 - TypeScript 2.8下的终极React组件模式](https://juejin.im/post/5b07caf16fb9a07aa83f2977)
- [YDJFE - 一次TypeScript, React, Node, MongoDB的模板式前后端分离开发实践](https://juejin.im/post/5b89e47f51882542c062651f)

**React Native**

- [胡桓铭 - React Native 与 TypeScript 在企业开发中的实践](https://zhuanlan.zhihu.com/p/27029898)

**Wechat**

- [Guyoung - 使用 TypeScript 开发微信小程序](https://segmentfault.com/a/1190000008175944)

**Node.js**

- [MarxJiao - 使用webpack搭建基于typescript的node开发环境](https://www.jianshu.com/p/6aab86403dc1)
- [天猪 - 当 Egg 遇到 TypeScript，收获茶叶蛋一枚](https://zhuanlan.zhihu.com/p/35334932)
- [奇舞团 - ThinkJS 3.0 如何实现对 TypeScript 的支持](https://75team.com/post/thinkjs-3.0-with-typescript.html)
- [贾顺名 - TypeScript在node项目中的实践](https://segmentfault.com/a/1190000015719697)
- [贾顺名 - 使用 TS + Sequelize 实现更简洁的 CRUD](https://mp.weixin.qq.com/s/agjjsO-47Qdd517wthadFg)

### English

#### Features

- [Marius Schulz - TypeScript 2.0: The never Type](https://blog.mariusschulz.com/2016/11/18/typescript-2-0-the-never-type )
- [Marius Schulz - TypeScript 2.0: Tagged Union Types](https://blog.mariusschulz.com/2016/11/03/typescript-2-0-tagged-union-types)
- [Marius Schulz - TypeScript 2.0: Read-Only Properties](https://blog.mariusschulz.com/2016/10/31/typescript-2-0-read-only-properties)
- [Marius Schulz - TypeScript 2.1: Object Rest and Spread](https://blog.mariusschulz.com/2016/12/23/typescript-2-1-object-rest-and-spread)
- [Marius Schulz - TypeScript 2.1: Mapped Types](https://blog.mariusschulz.com/2017/01/20/typescript-2-1-mapped-types)
- [Marius Schulz -  TypeScript 2.1: Improved Inference for Literal Types](https://blog.mariusschulz.com/2017/01/27/typescript-2-1-improved-inference-for-literal-types)
- [Marius Schulz -  TypeScript 2.1: keyof and Lookup Types](https://blog.mariusschulz.com/2017/01/06/typescript-2-1-keyof-and-lookup-types)
- [Marius Schulz - TypeScript 2.2: Dotted Properties and String Index Signatures](https://blog.mariusschulz.com/2017/03/03/typescript-2-2-dotted-properties-and-string-index-signatures)
- [Marius Schulz - TypeScript 2.3: Generic Parameter Defaults](https://blog.mariusschulz.com/2017/06/02/typescript-2-3-generic-parameter-defaults)
- [Marius Schulz - TypeScript 2.4: String Enums](https://blog.mariusschulz.com/2017/10/27/typescript-2-4-string-enums)
- [Marius Schulz - TypeScript 2.5: Optional catch Binding](https://blog.mariusschulz.com/2018/01/30/typescript-2-5-optional-catch-binding)
- [Marius Schulz - TypeScript 2.6: JSX Fragment Syntax](https://blog.mariusschulz.com/2018/02/09/typescript-2-6-jsx-fragment-syntax)
- [Marius Schulz - TypeScript 2.7: Strict Property Initialization](https://blog.mariusschulz.com/2018/05/20/typescript-2-7-strict-property-initialization)
- [Marius Schulz - TypeScript 2.7: Numeric Separators](https://blog.mariusschulz.com/2018/02/16/typescript-2-7-numeric-separators)
- [Marius Schulz - TypeScript 2.8: Per-File JSX Factories](https://blog.mariusschulz.com/2018/07/08/typescript-2-8-per-file-jsx-factories)

#### Tutorials

- [Microsoft - TypeScript-Handbook](https://github.com/Microsoft/TypeScript-Handbook)
- [Microsoft - TypeScript Team Blog](http://blogs.msdn.com/b/typescript/)
- [TypeStrong - Learn TypeScript](https://github.com/TypeStrong/learn-typescript)
- [Indrek Lasn - TypeScript — JavaScript with superpowers](https://medium.freecodecamp.org/typescript-javascript-with-super-powers-a333b0fcabc9)
- [Indrek Lasn - TypeScript — JavaScript with superpowers II](https://hackernoon.com/typescript-javascript-with-superpowers-part-ii-69a6bd2c6842)
- [Martin Hochel - Interface vs Type alias in TypeScript 2.7](https://medium.com/@martin_hotell/interface-vs-type-alias-in-typescript-2-7-2a8f1777af4c)
- [Valentin PARSY - Typescript : class vs interface](https://medium.com/front-end-hacking/typescript-class-vs-interface-99c0ae1c2136)
- [Victor Savkin - Functional TypeScript](https://vsavkin.com/functional-typescript-316f0e003dc6)
- [Netanel Basal - Using TypeScript Dynamic Imports in Angular](https://netbasal.com/using-typescript-dynamic-imports-in-angular-d210547484dd)
- [Elena Sufieva - Advanced TypeScript Types with Examples](https://levelup.gitconnected.com/advanced-typescript-types-with-examples-1d144e4eda9e)
- [Wolksoftware - Decorators Reflection JavaScript TypeScript](http://blog.wolksoftware.com/decorators-reflection-javascript-typescript)
- [Luis Aviles - Real Time Apps with TypeScript: Integrating Web Sockets, Node & Angular](https://medium.com/dailyjs/real-time-apps-with-typescript-integrating-web-sockets-node-angular-e2b57cbd1ec1)
- [Jonny Fox - WebSocket + Node.js + Express — Step by step tutorial using Typescript](https://medium.com/factory-mind/websocket-node-js-express-step-by-step-using-typescript-725114ad5fe4)
- [Trey Huffine - TypeScript and React using create-react-app: A step-by-step guide to setting up your first app](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)
- [Rinto Jose - React Native with TypeScript](https://medium.com/@rintoj/react-native-with-typescript-40355a90a5d7)

#### Samples

- [Microsoft - TypeScriptSamples](https://github.com/Microsoft/TypeScriptSamples)
- [DanWahlin - Angular-JumpStart](https://github.com/DanWahlin/Angular-JumpStart)
- [chsakell - aspnet5-angular2-typescript](https://github.com/chsakell/aspnet5-angular2-typescript)
- [Lemoncode - react-typescript-samples](https://github.com/Lemoncode/react-typescript-samples)
- [jaysoo - todomvc-redux-react-typescript](https://github.com/jaysoo/todomvc-redux-react-typescript)
- [rangle - typescript-react-redux-example](https://github.com/rangle/typescript-react-redux-example)
- [luixaviles - socket-io-typescript-chat](https://github.com/luixaviles/socket-io-typescript-chat)
- [dwyl - hapi-typescript-example](https://github.com/dwyl/hapi-typescript-example)

#### Guide

- [piotrwitek - react-redux-typescript-guide](https://github.com/piotrwitek/react-redux-typescript-guide)
- [labs42io - clean-code-typescript](https://labs42io.github.io/clean-code-typescript)
- [sw-yx - react-typescript-cheatsheet](https://github.com/sw-yx/react-typescript-cheatsheet)

#### Awesome

- [dzharii - awesome-typescript](https://github.com/dzharii/awesome-typescript)
- [brookshi - awesome-typescript-projects](https://github.com/brookshi/awesome-typescript-projects)

## TypeScript Starters/Boilerplates

- [Microsoft - TypeScript-React-Starter](https://github.com/Microsoft/TypeScript-React-Starter)
- [Microsoft - TypeScript-Vue-Starter](https://github.com/Microsoft/TypeScript-Vue-Starter)
- [Microsoft - TypeScript-Knockout-Starter](https://github.com/Microsoft/TypeScript-Knockout-Starter)
- [Microsoft - TypeScript-React-Native-Starter](https://github.com/Microsoft/TypeScript-React-Native-Starter)
- [Microsoft - TypeScript-WeChat-Starter](https://github.com/Microsoft/TypeScript-WeChat-Starter)
- [Microsoft - TypeScript-Babel-Starter](https://github.com/Microsoft/TypeScript-Babel-Starter)
- [Microsoft - TypeScript-Node-Starter](https://github.com/Microsoft/TypeScript-Node-Starter)
- [wmonk - create-react-app-typescript](https://github.com/wmonk/create-react-app-typescript)
- [rokoroku - react-redux-typescript-boilerplate](https://github.com/rokoroku/react-redux-typescript-boilerplate)
- [bitjson - typescript-starter](https://github.com/bitjson/typescript-starter)
- [blove - typescript-express-starter](https://github.com/blove/typescript-express-starter)
- [w3tecch - express-typescript-boilerplate](https://github.com/w3tecch/express-typescript-boilerplate)
- [kamahl19 - react-starter](https://github.com/Kamahl19/react-starter)
- [jsynowiec - node-typescript-boilerplate](https://github.com/jsynowiec/node-typescript-boilerplate)

## TypeScript Design patterns

- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 创建型模式](https://juejin.im/post/59fa88ac5188255a6a0d5f31)
- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 结构型模式（上）](https://juejin.im/post/5a2d16325188252da0535d73)
- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 结构型模式（下）](https://juejin.im/post/5a51da10f265da3e347b1483)
- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 对象行为型模式（上）](https://juejin.im/post/5a6dd4dd51882573385ffa8e)
- [蚂蚁金服数据体验技术团队 -Typescript玩转设计模式 之 对象行为型模式（下）](https://juejin.im/post/5a77211b6fb9a0635774d61a)
- [杜帅 - 浅析Typescript设计模式](https://zhuanlan.zhihu.com/p/43283016)
- [torokmark - design_patterns_in_typescript](https://github.com/torokmark/design_patterns_in_typescript)

## TypeScript Videos

### Chinese

- [慕课网 - TypeScript 入门](http://www.imooc.com/learn/763)
- [智能社 - TypeScript - 2小时带你体验微软新坑](https://chuanke.baidu.com/v1021662-207581-1268007.html)
- [cnode - 2018年最新Typescript视频教程](https://cnodejs.org/topic/5b4419df13ca2fe569fb924a)

### English

- [egghead.io - Use Types Effectively in TypeScript](https://egghead.io/courses/use-types-effectively-in-typescript)
- [egghead.io - Up and Running with TypeScript](https://egghead.io/courses/up-and-running-with-typescript)
- [egghead.io - advanced-static-types-in-typescript](https://egghead.io/courses/advanced-static-types-in-typescript)
- [Microsoft - Angular Applications with TypeScript](https://mva.microsoft.com/en-US/training-courses/angular-applications-with-typescript-14330)
- [udemy - TypeScript Fundamentals](https://www.udemy.com/ts-fundamental/)
- [udemy - Introduction to TypeScript](https://www.udemy.com/typescript/)
- [udemy - TypeScript: Learn the Basics in a Refreshing Way](https://www.udemy.com/typescript-hero/)
- [youtube - Evolving JavaScript with TypeScript](https://www.youtube.com/watch?v=Ut694dsIa8w)
- [scrimba - Introduction to TypeScript](https://scrimba.com/g/gintrototypescript)

## TypeScript QA

- [Segmentfault - 为什么Angular2和Ionic2都用TypeScript开发，TypeScript有什么优势吗？](https://segmentfault.com/q/1010000004152645)
- [Zhihu - TypeScript 和 JavaScript 的区别？](https://www.zhihu.com/question/25421196)
- [Zhihu - 如何评价 TypeScript？](https://www.zhihu.com/question/21879449)
- [Zhihu - 现在 TypeScript 的生态如何？](https://www.zhihu.com/question/37222407)
- [Zhihu - 关于Typescript和ES6的对比？](https://www.zhihu.com/question/59375764)
- [Zhihu - 为什么 TypeScript 成功了，更先进的 ActionScript 却失败了？](https://www.zhihu.com/question/49170215)
- [Zhihu - Typescript有什么冷门但是很好用的特性？](https://www.zhihu.com/question/276172039/answer/385433602)
- [Zhihu - TypeScript中的装饰器(Decorators)的本质是什么](https://www.zhihu.com/question/68257128/answer/261502855)
- [Zhihu - 如何学习用Typescript写Reactjs?](https://www.zhihu.com/question/38838053/answer/78371116)

## TypeScript Books

### Chinese

- [Learning TypeScript (中文版)](https://amazon.cn/gp/product/B071Z65LLT/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B071Z65LLT&linkCode=as2&tag=semlinker-23&linkId=90e1e4c6c17c6b68e463654b727114de)
- [TypeScript实战指南](https://amazon.cn/gp/product/B07WYWVC3Q/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B07WYWVC3Q&linkCode=as2&tag=semlinker-23&linkId=9737c185dcd0d31547e4c32999dffb60)
- [TypeScript图形渲染实战：2D架构设计与实现](https://amazon.cn/gp/product/B07PDL3MDX/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B07PDL3MDX&linkCode=as2&tag=semlinker-23&linkId=f5618de108e9c829391e9f164e37ff11)
- [迈向 Angular 2: 基于 TypeScript 的高性能 SPA 框架](https://amzn.to/37vb1ke)

### English

- [TypeScript Essentials](https://amzn.to/2QgRtde)
- [Mastering TypeScript](https://www.amazon.cn/dp/B00WMLHQFC)
- [Mastering TypeScript - Second Edition](https://amzn.to/2stJzo7)
- [Mastering TypeScript 3: Build enterprise-ready, industrial-strength web applications using TypeScript 3 and modern frameworks, 3rd Edition](https://amzn.to/37q4Q0x)
- [TypeScript 3.0 Quick Start Guide: The easiest way to learn TypeScript](https://amzn.to/2ZFPt1q)
- [Learn React with TypeScript 3: Beginner's guide to modern React web development with TypeScript 3](https://amzn.to/2rJZ4rs)
- [Advanced TypeScript Programming Projects: Build 9 different apps with TypeScript 3 and JavaScript frameworks such as Angular, React, and Vue](https://amzn.to/2ZJiKYV)
- [Hands-On RESTful Web Services with TypeScript 3: Design and develop scalable RESTful APIs for your applications](https://amzn.to/36aPNHX)
- [Hands-On TypeScript for C# and .NET Core Developers: Transition from C# to TypeScript 3.1 and build applications with ASP.NET Core 2](https://amazon.cn/gp/product/B07GYR34S8/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B07GYR34S8&linkCode=as2&tag=semlinker-23&linkId=e7e8425deb0e1072ac83a80645d41725)
- [Hands-On Functional Programming with TypeScript: Explore functional and reactive programming to create robust and testable TypeScript applications](https://amazon.cn/gp/product/B07KSXLCNK/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B07KSXLCNK&linkCode=as2&tag=semlinker-23&linkId=41627cba9b3218ee4c1c98c58c3840e1)
- [Learning TypeScript](https://amazon.cn/gp/product/B0151N0G7W/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B0151N0G7W&linkCode=as2&tag=semlinker-23&linkId=dfaf71cb179bab7e12e5efec9c989d94)
- [Learning TypeScript 2.x](https://amzn.to/2QcvCUu)
- [TypeScript 2.x By Example](https://amzn.to/2ZGE817)
- [TypeScript 2.x for Angular Developers](https://amazon.cn/gp/product/B0753J1W3Z/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B0753J1W3Z&linkCode=as2&tag=semlinker-23&linkId=516a4d410a52a13ab2eaa2c6f00ec3a5)
- [Angular 2 Development with TypeScript ](https://www.amazon.cn/dp/1617293121)
- [TypeScript: Modern JavaScript Development](https://amzn.to/2ZJjld7)
- [TypeScript Blueprints](https://amazon.cn/gp/product/B01CUI0JW8/ref=as_li_tl?ie=UTF8&camp=536&creative=3200&creativeASIN=B01CUI0JW8&linkCode=as2&tag=semlinker-23&linkId=53a25b758a65aae7f591b6349d2fc668)
- [Pro TypeScript](https://www.amazon.cn/dp/1484232488)
- [TypeScript Design Patterns](https://amzn.to/2FbWkpY)
- [TypeScript High Performance](https://amzn.to/2QAERNk)
- [TypeScript Microservices](https://amzn.to/39ru7cx)

## TypeScript Tools/Libraries

### Build

#### webpack

- [s-panferov - awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader)
- [TypeStrong - ts-loader](https://github.com/TypeStrong/ts-loader)

#### gulp

- [ivogabe - gulp-typescript](https://github.com/ivogabe/gulp-typescript)

#### grunt

- [TypeStrong - grunt-ts](https://github.com/TypeStrong/grunt-ts)

#### compiler

- [TypeStrong - ts-node](https://github.com/TypeStrong/ts-node)
- [AssemblyScript - assemblyscript](https://github.com/AssemblyScript/assemblyscript)
- [bcherny - json-schema-to-typescript](https://github.com/bcherny/json-schema-to-typescript)
- [YousefED - typescript-json-schema](https://github.com/YousefED/typescript-json-schema)

#### linter

- [palantir - tslint](https://github.com/palantir/tslint)

### Ioc

* [Inversify - InversifyJS](https://github.com/inversify/InversifyJS)
* [Inversify - inversify-express-example](https://github.com/inversify/inversify-express-example)

### Doc

- [TypeStrong - typedoc](https://github.com/TypeStrong/typedoc)

### Data Structure

- [dcodeIO - protobuf.js](https://github.com/dcodeIO/protobuf.js)
- [basarat - typescript-collections](https://github.com/basarat/typescript-collections)
- [samchon - tstl](https://github.com/samchon/tstl)

### Database

- [Typeorm - typeorm](https://github.com/typeorm/typeorm)
- [RobinBuschmann - sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript)
- [MikroORM](https://github.com/mikro-orm/mikro-orm)

### Server

- [Alibaba - egg.js](https://eggjs.org/)
- [welefen - thinkjs](https://github.com/thinkjs/thinkjs)
- [kamilmysliwiec - nest](https://github.com/nestjs/nest)
- [samchon - tgrid](https://github.com/samchon/tgrid)

## TypeScript IDE

### Offline

#### IDE/Plugins

- [Visual Studio Community](https://visualstudio.microsoft.com/zh-hans/vs/community/)
- [Visual Studio Code](https://www.visualstudio.com/en-us/products/code-vs.aspx)
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [PhpStorm](https://www.jetbrains.com/phpstorm/download/)
- [TypeScript Sublime Plugin](https://github.com/Microsoft/TypeScript-Sublime-Plugin)
- [Atom TypeScript](https://github.com/TypeStrong/atom-typescript)
- [TypeScript Interactive Development Environment for Emacs](https://github.com/ananthakumaran/tide)
- [TypeScript IDE for Eclipse](http://typecsdev.com/)
- [TypeScript Syntax for VIM](https://github.com/leafgarland/typescript-vim)

### Online

#### Playground

- [TypeScript official Playground](http://www.typescriptlang.org/Playground/)
- [Stackblitz](https://stackblitz.com/)
- [JS Bin](http://jsbin.com/?js)
- [Codepen](http://codepen.io/)
- [TypeScript Editor](http://drake7707.github.io/Typescript-Editor/)
- [TypeScript Interpret - Terminal Emulator](http://niutech.github.io/typescript-interpret/)
- [TypeScript Play](https://agentcooper.github.io/typescript-play/)

#### Chrome Extension

- [OctoLinker](https://github.com/OctoLinker/browser-extension)

## Contributing

We welcome your contributions 🌺

### Guide

1. Please make sure to add your item in the correct section.
2. Always add new items at the end of the list. The format should be consistent with the current section's items.
3. If you feel that some items are in the wrong section or you need to add a new section, please feel free to edit.

**[⬆ Go To Top](#contents)**

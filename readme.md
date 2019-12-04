# step

## JS

* 工程目录结构：
  * page/  【一个文件夹作为一个功能模块】
    * imgs 【该模块的图片】
    * index.html
    * index.less
    * index.js 【把本功能模块需要的AP 配置 到 JS内部】
    * test_data.js 【模拟测试数据，用于和后台格式约定】
* 学习路径：https://github.com/zc3hd/demo_JS_learn
  * JS基础
  * webAPI
  * JQ
  * JS高级
  * ES6
  * git



## gulp

* 用法-1：[gulp-01](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_001)
  * `npm run web_only`：单独开启前端的gulp编译-无代理
* 用法-2：[gulp-01](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_001)
  * `npm run web_proxy`：单独开启前端的gulp编译-有代理（代理所配合的后台的API端口）；

* 用法-3：[gulp-01](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_001)
  * `npm run web_proxy`：单独开启前端的gulp编译-有代理（代理所配合的后台的API端口）；
  * `npm run api_proxy`：开启后台服务-被gulp代理的服务（只不过此处的后台是我们自己写）；
* 用法-4：[gulp-01](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_001)
  * `npm run api_only`：当后台是由我们独立完成，这个相当于是看最终版；



## vue

* vue学习笔记最后的小项目。
* [vue学习笔记-1](https://github.com/zc3hd/demo_vue_again/tree/master);
* [vue学习笔记-2](https://github.com/zc3hd/demo_vue_again/tree/webpack);
* [vue小项目](https://github.com/zc3hd/demo_vue_again/tree/webpack/demo_099)；



## webpack

* 学习webpack，首先需要知道webpack有几种编译模式；
* 要知道：纯DOM项目和vue项目更适合用是什么编译工具。vue用webpack就行，js用也可以用webpack。
* 最终形成的架子：[vue+webpack 前后两个端口，自动化](https://github.com/zc3hd/demo_webpack_again/tree/master/webpack_demo_005);





## node

* Express：知道如何指定静态服务的中间件，现在的模式是根据webapp里模块对应来设计路由，不要ejs,不要后台MVC。维护和开发省时才是硬道理。内部API模块完全按照面向对象的写法提供API服务，API的路由设计也写在内部。
* **gulp与express**：前端是纯JS开发，后台是express。目前的模式是express提供API和静态资源服务，nodemo热加载后台代码，bs做代理服务器，配合gulp进行代码实时编译和浏览器实时刷新。见 [架子](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_002);
* **webpack与express**：前端主要为vue,webpack进行编译，后台为express。见[架子](https://github.com/zc3hd/demo_webpack_again/tree/master/webpack_demo_005)；为前后端同时各监测各的状态。




## 计划

1. 记忆曲线复习计划  **（进度：100%）**
2. 地图聊天室  **（进度：90%）**
3. 面试地图标注-小程序版   **（进度：0%）**
4. 爬GitHub形成自己的博客  **（进度：0%）**
5. 每次提交代码，标识特定字段，提醒服务器进行爬一次GitHub生成自己的博客数据  **（进度：0%）**
6. GAS计划：服务端每周期自定义天数，每个项目提交随机条数代码，不友好地保证GitHub的little star ；该项目已经完成，项目代码只供学习，若现实中出现负面影响，本码农概不负责。**（进度：100%）**




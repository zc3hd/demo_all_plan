# step

### 1.JS

* 现有的工作结构目录：一个文件夹作为一个功能模块，下面有JS/html/less,JS采用面向对象开发，把需要的API写入JS模块内的全局配置，主要全局配置参数进行全局配置；test_data.js测试的数据单独分一个JS文件。
* 学习路径：[js](https://github.com/zc3hd/demo_JS_learn);

-------

### 2.gulp

* 基于上面JS前端开发的结构目录，该架子适合做JS面向对象、dom操作项目。
* [针对前端为JS模块化开发的实时测试打包工具](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_001);
* [gulp+express前后同时开发的工具，前后端同时监测](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_002);
-------

### 3.vue

* vue学习笔记最后的小项目。
* [vue学习笔记-1](https://github.com/zc3hd/demo_vue_again/tree/master);
* [vue学习笔记-2](https://github.com/zc3hd/demo_vue_again/tree/webpack);
* [vue小项目](https://github.com/zc3hd/demo_vue_again/tree/webpack/demo_099)；

-------

### 4.webpack

* 学习webpack，首先需要知道webpack有几种编译模式；
* 要知道：纯DOM项目和vue项目更适合用是什么编译工具。vue用webpack就行，js用也可以用webpack。
* 最终形成的架子：[vue+webpack 前后两个端口，自动化](https://github.com/zc3hd/demo_webpack_again/tree/master/webpack_demo_005);

-------

### 5.node

* Express：知道如何指定静态服务的中间件，现在的模式是根据webapp里模块对应来设计路由，不要ejs,不要后台MVC。维护和开发省时才是硬道理。内部API模块完全按照面向对象的写法提供API服务，API的路由设计也写在内部。

#### 5.1 gulp与express

* 针对项目：前端是纯JS开发，后台是express。目前的模式是express提供API和静态资源服务，nodemo热加载后台代码，bs做代理服务器，配合gulp进行代码实时编译和浏览器实时刷新。见 [架子](https://github.com/zc3hd/demo_gulp_learn/tree/master/gulp_002);

#### 5.2 webpack与express

* 前端主要为vue,webpack进行编译，后台为express。见[架子](https://github.com/zc3hd/demo_webpack_again/tree/master/webpack_demo_005)；为前后端同时各监测各的状态。


### 6.其他

* cordova是搞混合app开发玩的，这个后期一定要了解。

### &.计划

> 1. 记忆曲线复习计划（进度：100%）
> 2. 地图聊天室（进度：90%）
> 3. 面试地图标注-小程序版 （进度：0%）
> 4. 爬GitHub形成自己的博客（进度：0%）；
> 5. 每次提交代码，标示提醒服务器进行自动爬一次GitHub（进度：0%）




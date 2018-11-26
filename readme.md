# step

### 1.JS

* 现有的工作模式：一个文件夹作为一个功能模块，下面有JS/html/less,JS采用面向对象开发，把需要的API写入模块的全局配置，主要配置参数进行全局配置
* test_data.js测试的数据单独分一个JS文件。
* 问题1：各种设计模式的学习

### 2.gulp

```
001-demo_gulp_learn/gulp-001：针对前端为JS模块化开发的实时测试打包工具。
001-demo_gulp_learn/gulp-002：gulp+express前后同时开发的工具。
```

### 3.vue

* 开始学习vue,学习到最后有一个vue的小项目，都是vue的优化和笔记。
* 最后需要打包，也要符合公司实际情况的配合和工程目录的结构，就涉及到webpack的build

### 4.webpack

* 按照上面的思路，学习到了webpack，知道webpack有几种编译模式，对于纯JS项目和vue项目更适合用是什么编译工具。vue建议用webpack就行，js用现在的gulp就可以了。
* 最后如果后台也是你做，你就需要知道node。

* 问题1: webpack如何JS内部直接引用的img地址抽取出来？


### 5.node

* Express：知道如何指定静态服务的中间件，现在的模式是根据webapp里模块对应来设计路由，不要ejs,不要后台MVC。维护和开发省时才是硬道理。内部API模块完全按照面向对象的写法提供API服务，API的路由设计也写在内部。

### 5.1 gulp与express
* 问题1: 目前gulp框架适合纯JS工程，那么gulp如何引入express的服务？

* 针对项目：前端是纯JS开发，后台是express，都是一个人开发。
* 该问题已经解决，目前的模式是express提供API和静态资源服务，nodemo热加载后台代码，bs做代理服务器，配合gulp进行代码实时编译和浏览器实时刷新。
* 目前是缺少一个成熟的框架kit

### 5.2 webpack与express

* 针对：前端为vue或者JS开发，后台为express，一个人。
* 目前无框架。




### 其他

* cordova是搞混合app开发玩的，这个后期一定要了解。




# weibo_server
PHP和Android最佳实战中的服务端实例，业务逻辑和Json通信协议一样，但是没有用书上的框架
------
###1.摆脱了原作者的Hush-framework
###2.自己实现了原基础框架的所需功能（服务端需要的基础功能），包括：


- 1）请求分发
- 2）Debug后台需要的解析注释文档功能
- 3）底层和数据库交互配置、单例工厂类
- 4）自己实现基础控制器类
- ...

###3.当然还有对原作者的目录结构做了调整，化繁为简，更加清晰
###4.对原作者的实现逻辑有一定的修改，包括：
- 1）模型层逻辑
- 2）控制器某些Action的实现逻辑，如获取参数的方法、打印的方法、判断合法性。
- 3）对PHP一些常量的配置更加清晰，代码的结构更加整洁 不会一打开就全是黄色（PHPStorm）
###5.自己实现了自动加载，更加省资源
#.
#.
-----

##当然还是要致敬原作者：

###1.服务端整体架构是根据原书上面的
###2.整体业务逻辑也是
###3.Debug后台的模板直接套用书上的，感谢作者那么好用的Debug后台
###4.作者的一些代码技巧我也是套用（比自己写确实好）
###5.学到了不少东西呀~~~~
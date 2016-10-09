##day-01 jQuery源码阅读之整体架构

```js
(function(){
    //(21, 94) 定义了一些变量和函数 jQuery = function(){}
    //(96, 283) 给JQ对象添加一些属性和方法
    //(285, 347）extend JQ的继承方法
    //(349, 817) jQuery.extend() jQuery扩展一些工具方法
    //(877, 2856) Sizzle: 复杂选择器的实现
    //(2880, 3042) Callbacks: 回调对象---对函数的统一管理
    //(3043, 3183) Deferred: 延时对象---对异步的统一管理
    //others 兼容性检查
    //8826 window.jQuery = window.$ = jQuery 将jQuery暴露给用户
})();
```

##什么是Sizzle.js
>大家都知道，Sizzle是jQuery的御用选择器引擎，是jQuery作者John Resig写的DOM选择器引擎，速度号称业界第一。

##TO Be Continue...

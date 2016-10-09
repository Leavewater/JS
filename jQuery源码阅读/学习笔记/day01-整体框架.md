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
    //(3184,3295) support
    //(3308, 3652) data() 方法的功能---数据缓存并没有挂载在dom上，防止内存泄露
    //(3653, 3797) queue()功能---队列管理
    //(3803, 4299) attr, prop, addClass, val方法等，对元素属性的操作
    //(4300, 5128) on, trigger等事件操作的相关方法
    //(5140, 6057) Dom操作的方法 crud及包装等
    //(6058, 6620) css() 针对样式的操作
    //(6621, 7854) 提交的数据数据和AJAX的操作ajax\load\getJSON
    //(7855, 8584) 运动的操作
    //(8585, 8792) offset() scrollTop()等位置与尺寸的方法
    //(8804, 8821) JQuery支持模块化的模式
    //8826 window.jQuery = window.$ = jQuery 将jQuery暴露给用户
})();
```

##什么是Sizzle.js
>大家都知道，Sizzle是jQuery的御用选择器引擎，是jQuery作者John Resig写的DOM选择器引擎，速度号称业界第一。

##TO Be Continue...

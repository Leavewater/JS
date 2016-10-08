##day-01 jQuery源码阅读之整体架构

```js
(function(){
    //(21, 94) 定义了一些变量和函数 jQuery = function(){}
    //(96, 283) 给JQ对象添加一些属性和方法
    //(285, 347）extend JQ的继承方法
    //(349, 817) jQuery.extend() jQuery扩展一些工具方法
    //8826 window.jQuery = window.$ = jQuery 将jQuery暴露给用户
})();
```



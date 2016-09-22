`dialog`组件，包含`alert`和`confirm`两种样式，下面是它的使用方法：

在html文件中引入对应的css和js

``` html

<link rel="stylesheet" href="widget/dialog/dialog.css">

<script src="widget/dialog/dialog.js"></script>

```
js文件中调用

```js

lnv.alert({
    title: '提示',
    content: 'content',
    alertBtnText: '确定',
    alertHandler: function(){

        // 点击确定按钮的回调

    }
})

```

效果如下：

![alert](img/alert.png)

js文件中调用

```js

lnv.confirm({
    title: '提示',
    content: 'content',
    confirmBtnText: '确定选择',
    confirmHandler: function(){

        // 点击确定按钮的回调

    },
    cancelBtnText: '取消',
    cancelHandler: function(){

        // 点击取消按钮的回调

    }
})

```

效果如下：

![confirm](img/confirm.png)
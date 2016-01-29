
1. 介绍
===

**wangEditor**——轻量级web富文本编辑器，配置方便，使用简单</b>。支持IE8+浏览器。

* 软件官网：[wangEditor.github.io](http://wangeditor.github.io/)
* demo演示：[wangEditor.github.io](http://wangeditor.github.io/)
* 文档：[http://www.kancloud.cn/wangfupeng/wangeditor2/113961](http://www.kancloud.cn/wangfupeng/wangeditor2/113961)

![](http://images2015.cnblogs.com/blog/138012/201509/138012-20150910004209122-1645253022.png)

2. 使用
===

引用wangEditor.css、jquery.js和wangEditor.js之后，即可简单生成富文本编辑器，简单易用。
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>wangEditor</title>
    <link rel="stylesheet" type="text/css" href="../dist/css/wangEditor.min.css">
    <style type="text/css">
        #div1 {
            width: 100%;
            height: 500px;
        }
    </style>
</head>
<body>
    <div id="div1">
        <p>请输入内容...</p>
    </div>

    <script type="text/javascript" src="../dist/js/lib/jquery-1.10.2.min.js"></script>
    <script type="text/javascript" src="../dist/js/wangEditor.min.js"></script>
    <script type="text/javascript">
        $(function () {
            var editor = new wangEditor('div1');
            editor.create();
        });
    </script>
</body>
</html>
```

更多配置，可参见官网的文档页面：[http://www.kancloud.cn/wangfupeng/wangeditor2/113961](http://www.kancloud.cn/wangfupeng/wangeditor2/113961)

3. 本地运行demo
===

第一，确定本机安装了 `nodejs`，可使用 `node -v` 验证

第二，下载源码、解压，或者 `https://github.com/wangfupeng1988/wangEditor.git` 。**注意，`windows`系统必须下载到`C盘`运行**

第三，进入源码目录，找到 `server.js` 或者 `server-windows.js`，windows系统运行 `node server-windows.js` ，mac、linux系统运行 `node server.js`

第四，打开浏览器访问 `http://localhost:8011/test/index.html`

3. 交流
===
交流QQ群：**164999061**

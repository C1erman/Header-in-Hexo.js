## 关于

`Header-in-Hexo.js`帮助你在由`Hexo`生成的文档中插入一个目录。

当你在移动端打开你的博客时，你会发现`Hexo`令人遗憾之处：由于手机屏幕太小，你将看不到侧边导航栏——这在文章很长时是无法忍受的。

因此，我们需要一次移动端适配。

## 更新

- **v0.01** 增加了视口判断，只有当宽度小于400或高度小于800时才会显示该目录，修复了页面重绘时目录仍然留存的BUG。

- **v0.00** 第一次上传

## 用法

`Header-in-Hexo.js`帮助你解决这个问题，你要做的仅仅是在`Markdown`文件中插入一个`<div id='_menu'>`——用于放置生成的目录，你可以将它放置在页面上的任何位置，`id='_menu'`是必须的。

当然，你还需要复制`Header-in-Hexo.js`中的内容到你的`Markdown`文件中，填在一个`<script>`标签里。

## 效果

在移动设备上看到一篇文章的结构将变的轻而易举：

![示例](https://raw.githubusercontent.com/C1erman/Graph-bed/master/imgs/For%20Blog/Header-in-Hexo-click.gif)

## 下载

[![图片描述](https://img.shields.io/badge/download-%E4%B8%8B%E8%BD%BD-blue.svg)](https://github.com/C1erman/Header-in-Hexo.js/releases)

## 错误

如果有任何错误，欢迎提交`issue`。


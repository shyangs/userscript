自用修改版
=========

对他人的脚本进行一些修改。**请使用原版，并不保证更新。**

### nextpage.user.js

改自 [Next Page for Greasemonkey](http://userscripts.org:8080/scripts/show/27251)


### PanLinkCheck.user.js（2014-5-27）

[网盘死链检查 By Jixun](https://greasyfork.org/scripts/1262)

- **注意**：对百度盘链接的检查有严重 bug，由于同时对多个链接进行请求，会被百度盘临时封掉。所以我目前只对自己需要的网址 @include。
- 修正 FireGestures 一拖曳就会检查的问题。
- 增加 360云盘 的检查（有效文件的检查未完成）
- 文件名加入英文（Scriptish 中文忽略的 bug）

### TxtReader.user.js

[txt小说阅读器 ](http://userscripts.org:8080/scripts/show/185278)

- 乱改了一通，实际上并未多大变化，仅仅更改了样式，禁用了文本替换功能（太耗时间）。
- 用的次数不多，用到的时候发现问题改下。

### quick-view-douban 修正版.user.js

改于 2013-09-01，原脚本 [豆瓣快查 for Greasemonkey](http://userscripts.org:8080/scripts/show/129416)

- 修正电影搜索，增加图片显示
- 电影搜索限制：每分钟10次（采用公开 api v2）
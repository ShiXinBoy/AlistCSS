---
title: Alist主题
tags: Alist主题
categories: Alist
abbrlink: 64793
date: 2022-06-06 19:35:31
---

## 用前必读

1. 该站所有内容伪原创，允许任何人直接使用，如果你是开发者，对本站==任何文件的任何内==容进行了修改，在发布时请注明原作者为：“[思卿长安归](https://shixin.vercel.app)”
2. 本站对应github仓库地址为：[https://github.com/ShiXinBoy/AlistCSS](https://github.com/ShiXinBoy/AlistCSS)
3. 本页面其他URL
   1. vercel：[https://alistcss.vercel.app](https://alistcss.vercel.app)
   2. github：[https://www.icefox.site/AlistCSS/](https://www.icefox.site/AlistCSS/)
   <!--more-->
## 预览dome

在本站的网址后追加对应的html路径即可预览。
> 工程文件非原始布局，与正式效果略有出入。
> HTML路径为github仓库中对应css文件同名的*.HTML文件，一般为== folder/name@version.html ==

## 使用方法

### 方法一

1.在“自定义body”中添加如下内容：

``` html
<link href="https://alistcss.vercel.app/{folder/name@version}.css" rel="stylesheet" style="text/css"/>
<style>
    {:root}
</style>
```

> 注意：你需要替换<kbd>{folder/name@version}</kbd>和<kbd>{:root}</kbd>字段：

> <kbd>{folder/name@version}</kbd>：
> 对应值请在github仓库打开对应文件，然后复制该内容：
> ![css目录](https://raw.githubusercontent.com/ShiXinBoy/picbed/main/202206101140867.png)

> <kbd>{:root}</kbd>:
> 对应值为同目录下HTML文件中class="root"的style标签内的所有内容，注意包含整个style标签。
> ![image-20220606112737838](https://raw.githubusercontent.com/ShiXinBoy/picbed/main/202206101141219.png)

### 方法二

直接在”自定义body“中添加如下内容：

![image-20220606113407625](https://raw.githubusercontent.com/ShiXinBoy/picbed/main/202206101141727.png)

> 注意：该style标签位于对应文件夹下HTML文件的尾部，复制时请连同style标签一同复制。

# 关于作者
[@思卿长安归](https://www.icefox.site)


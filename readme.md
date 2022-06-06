# AlistCSS

## 用前必读
1. 该站所有内容伪原创，允许任何人直接使用，如果你是开发者，对本站==任何文件的任何内==容进行了修改，在发布时请注明原作者为：“[思卿长安归](https://shixin.vercel.app)”
2. 本站对应github仓库地址为：https://github.com/ShiXinBoy/AlistCSS
3. 本站URL
  1. vercel:https://alistcss.vercel.app
  2. github:https://shixinboy.github.io/alistcss
  3. CDN:https://alistcss.icefox.site


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
> ![css目录](http://30836.test.upcdn.net//202206061111216.png)

> <kbd>{:root}</kbd>:
> 对应值为同目录下HTML文件中class="root"的style标签内的所有内容，注意包含整个style标签。
> ![image-20220606112737838](http://30836.test.upcdn.net//202206061127915.png)

### 方法二

直接在”自定义body“中添加如下内容：

![image-20220606113407625](http://30836.test.upcdn.net//202206061134661.png)

> 注意：该style标签位于对应文件夹下HTML文件的尾部，复制时请连同style标签一同复制。

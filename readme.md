# AlistCSS

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
>  
><kbd>{folder/name@version}</kbd>：
>> 对应值请在github仓库打开对应文件，然后复制该内容：
> > ![css目录](http://30836.test.upcdn.net//202206061111216.png)
> <kbd>{:root}</kbd>:
>>对应值为同目录下HTML文件中class="root"的style标签内的所有内容
>>
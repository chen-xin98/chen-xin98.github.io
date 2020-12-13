---
title: Markdown快速入门
categories: 
- 教程类
tags: 
- 语法规则
- markdown
top: 100
---
## Markdown是什么的
下面引用百度百科的说明：
> Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
---
## Markdown语法
### **行内代码**
\`代码\`这样的形式来展示行内代码。(~ 键)
例如：`main()`是入口
### **多行代码**
\`\`\`代码\`\`\`的形式展示多行代码
例如：
```python
    #!/usr/bin/env python3
    print("Hello, World!")
```

### 基本语法
**换行**：\<br\><br>
**标题**
markdown提供1-6级标题，用#的数量来控制。<br>
**加粗**
加粗使用\*来表示，被\*\*包含的部分将**加粗**。<br>
**斜体**
也使用\*表示，被\*包含的部分是*斜体*。<br>
**删除线** 
使用表示\~~删除线~~
~~删除线~~。<br>
**下划线**
使用\<u>\</u>表示<u>下划线</u>。<br>
**Markdown 列表：**
使用\-或1. 。
- 列表项目
1. 列表项目
---
<!-- more -->
**插入链接或文本**
Markdown 插入链接：
[链接文字](http://chen-xin98.github.io "标题")

Markdown 插入图片：
![alt text](/path/to/img.jpg "Title")

<!-- ![头像](http://i1.fuimg.com/730147/351f69502c756960.jpg  "Title") -->
<img src="http://i1.fuimg.com/730147/351f69502c756960.jpg" width="20px" />

***
**表格**

具体看代码 代码中:的位置表示对齐方式。<br>

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
---
***

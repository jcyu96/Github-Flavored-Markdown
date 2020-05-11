README  
![badge](https://img.shields.io/badge/%C2%A9-jcyu96-DarkOrange "作者")
====
主要记录一些不太容易查到的GFM(Github Flavored Markdown)语法规则，充当个人的markdown备忘录，所有内容完全由个人编辑记录。每个语法点都是由基本语法格式、终端显示效果和一些备注说明构成的，行文不当之处可以提出一起讨论。  
内容持续更新中......  
***
## 目录  
[**1. 小色块**](#1-小色块)  

[**2. 标签**](#2-标签)  

[**3. 锚点链接**](#3-标题锚点)  

[**4. 添加表情**](#4-添加表情)  

[**5. 插入图片和文本超链接**](#5-插入添加图片和文本超链接)  

[**6. 鼠标悬停显示**](#6-鼠标悬停显示)
***
### 1. 小色块
**语法：**  
```markdown
基本格式：![可替换文本](色块的url)  

示例：![色块](https://placehold.it/15/f2ed6f/000000?text=+)
```
**效果：**  

![色块](https://placehold.it/15/f2ed6f/000000?text=+)  

**备注：**  
可替换文本表示色块无法显示时显示的内容。示例中的网址`https://placehold.it/15/f2ed6f/000000?text=+`就是色块的url，把网址中的`/f2ed6f/`改成相应颜色的十六进制代码，就可以得到相应颜色的小色块。这里提供一个查询十六进制颜色码的网站：[十六进制颜色码](http://www.peise.net/tools/web/ "点击跳转")。
***
### 2. 标签
**语法：**  
```markdown
基本格式：![可替换文本](标签的url)  

示例：![badge](https://img.shields.io/badge/文本1-文本2-DarkOrange)
```
**效果：**  

![badge](https://img.shields.io/badge/文本1-文本2-DarkOrange "标签")  

**备注：**  
可替换文本表示色块无法显示时显示的内容。示例中网址的最后一部分`文本1-文本2-DarkOrange`中，`文本1`和`文本2`分别表示标签前后两部分的内容，第三个参数控制标签框后半部分的颜色，更简单的方法可以在[https://shields.io/](https://shields.io/)中的*Your Badge*一栏输入相应参数生成标签的url。这里提供一个颜色及对应英文名字查询的网站：[color name](https://html-color-codes.info/color-names/)。
***
### 3. 标题锚点
**语法：**  
```markdown
基本格式：[链接文本](链接标题)  

示例：[回到顶部](#readme)
```
**效果：**  

[回到顶部](#readme "回到顶部")  

**备注：**  
链接文本表示插入超链接的文本，可任意命名。链接标题表示链接文本要跳转的位置，需要和被链接的标题文本内容保持一致。输入链接标题时，以下几个规则需要注意：**①字母全部转换成小写形式；②文本中的空格用 - 代替；③文本中多级序号的 . 直接去掉；④文本中的\!\[\]\(\)可以直接去掉**。
***
### 4. 添加表情
**语法：**  
```markdown
基本格式：:表情代码:  

示例：:open_mouth:
```
**效果：**  

:open_mouth:  

**备注：**  
在两个 : 之间放入特定代码表示表情，表情代码在官网可以查询：[官方emoji代码](https://www.webfx.com/tools/emoji-cheat-sheet/)。
***
### 5. 插入图片和文本超链接
**语法：**  
```markdown
![湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  

<img src="https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg" width="200" height="400" alt="湄南河"/>  

[湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  
```
**效果：**  

![湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  
<img src="https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg" width="100" height="100" alt="湄南河"/>  
[湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  

**备注：**  
插入图片和添加文本超链接的语法表达其实很相似，两者之间只是差了一个'!'。第一个语法是插入图片常见的表达式，第二个语法中width和height两个参数可以控制插入图片的大小，另外这两个语法中的“湄公河”都是图片无法显示时显示的文本。第三个语法是给[]中的文本添加超链接，链接地址放在()里面。
***
### 6. 鼠标悬停显示
**语法：**  
```markdown
:open_mouth:
```
**效果：**  

:open_mouth:  

**备注：**  
在两个 : 之间放入特定代码显示表情，表情代码在官网可以查询：[官方emoji代码](https://www.webfx.com/tools/emoji-cheat-sheet/)。
***

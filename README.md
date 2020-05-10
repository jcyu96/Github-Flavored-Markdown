README  
![badge](https://img.shields.io/badge/%C2%A9-jcyu96-DarkOrange "作者")
====
主要记录一些不太经常用到的GFM语法规则，充当个人的markdown备忘录，所有内容完全由个人编辑记录。每个的语法点都是由基本的语法、显示效果和值得注意的备注说明构成的，行文不当之处可提出修改。  
内容持续更新中......  
***
## 目录  
[**1. 小色块**](#1-小色块)  

[**2. 标签**](#2-标签)  

[**3. 锚点链接**](#3-锚点链接)  

[**4. 添加表情**](#4-添加表情)  

[**5. 图片\!\[\]\(\)和链接\[\]\(\)**](#5-图片-----和链接----)  

***
### 1. 小色块
**语法：**  
```markdown
![#色块](https://placehold.it/15/f2ed6f/000000?text=+)
```
**效果：**  

![#色块](https://placehold.it/15/f2ed6f/000000?text=+ "颜色标识")  

**备注：**  
[]内表示色块无法显示时显示的内容，把后面网址中的`/f2ed6f/`部分修改成对应颜色的代码，即可设置成你想要的颜色。这其实就是添加图片的语法，也可以作为添加颜色标识的一种方式。
***
### 2. 标签
**语法：**  
```markdown
![badge](https://img.shields.io/badge/%C2%A9-可修改-DarkOrange)
```
**效果：**  

![badge](https://img.shields.io/badge/%C2%A9-可修改-DarkOrange "标签")  

**备注：**  
[]内表示标签无法显示时显示的内容。后面网址最后一部分`%C2%A9-可修改-DarkOrange`中，第一个参数表示标签框前一半的内容，第二个参数表示标签框后一半的内容，第三个参数控制标签框颜色，当然也可以在[https://shields.io/](https://shields.io/)中的*Your Badge*一栏输入相应参数生成专属url。这里提供一个颜色及对应英文名字查询的网站：[https://html-color-codes.info/color-names/](https://html-color-codes.info/color-names/)。
***
### 3. 锚点链接
**语法：**  
```markdown
[文本1](#文本2)
```
**效果：**  

[回到顶部](#readme)

**备注：**  
文本1表示含跳转位置处链接的文本，可任意命名。文本2表示文本1链接中的目标位置，需要和目标位置处加#的标题内容保持一致。输入文本2时，以下几个规则需要注意：**①字母全部转换成小写形式；②文本中的空格用 - 代替；③文本中多级序号的 . 去掉**。
***
### 4. 添加表情
**语法：**  
```markdown
:open_mouth:
```
**效果：**  

:open_mouth:  

**备注：**  
在两个 : 之间放入特定代码显示表情，表情代码在官网可以查询：[官方emoji代码](https://www.webfx.com/tools/emoji-cheat-sheet/)。
***
### 5. 图片\!\[\]\(\)和链接\[\]\(\)
**语法：**  
```markdown
:open_mouth:
```
**效果：**  

:open_mouth:  

**备注：**  
在两个 : 之间放入特定代码显示表情，表情代码在官网可以查询：[官方emoji代码](https://www.webfx.com/tools/emoji-cheat-sheet/)。
***

README  
![badge](https://img.shields.io/badge/%C2%A9-jcyu96-DarkOrange "作者")
====
主要记录一些不太经常用到的GFM语法规则，充当个人的markdown备忘录，所有内容完全由个人编辑记录。每个语法点都是由基本语法格式、终端显示效果和一些备注说明构成的，行文不当之处可以提出一起讨论。  
内容持续更新中......  
***
## 目录  
[**1. 小色块**](#1-小色块)  

[**2. 标签**](#2-标签)  

[**3. 锚点链接**](#3-标题锚点)  

[**4. 添加表情**](#4-添加表情)  

[**5. 图片\!\[\]\(\)和链接\[\]\(\)**](#5-%E5%9B%BE%E7%89%87%E5%92%8C%E9%93%BE%E6%8E%A5)  

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
### 3. 标题锚点
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
![湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  

<img src="https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg" width="200" height="400" alt="湄南河"/>  

[湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  
```
**效果：**  

![湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  

<img src="https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg" width="100" height="100" alt="湄南河"/>  

[湄南河](https://github.com/yujia96/Github-Flavored-Markdown/blob/master/Examples/%E6%B9%84%E5%8D%97%E6%B2%B3.jpg)  

**备注：**  
第一个语法是添加图片常见的表达式，第二个语法可以通过width和height两个参数控制显示图片的大小，这两个表达式中的“湄公河”是图片无法显示时显示的文本。第三个语法是给[]中的文本添加超链接，链接地址放在()里面。
***

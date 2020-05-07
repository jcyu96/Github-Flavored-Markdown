README
====
主要记录一些不太经常用到的GFM语法规则，充当个人的markdown备忘录，全文内容完全由个人手打。  
持续更新中......  

![badge](https://img.shields.io/badge/%C2%A9-jcyu-DarkOrange)<br>
***
## 目录  
### [1. 小色块](#1-小色块)  
### [2. 标签](#2-标签)
### [3. 锚点链接](#3-锚点链接)
### [4. 添加表情](#4-添加表情)
***
### 1. 小色块
**语法：**  
```markdown
![#色块](https://placehold.it/15/f2ed6f/000000?text=+)
```
**效果：**  

![#色块](https://placehold.it/15/f2ed6f/000000?text=+)  

**备注：**  
[]内表示色块无法显示时显示的内容，把后面网址中的`/f2ed6f/`部分修改成对应颜色的代码，即可设置成你想要的颜色。这可以作为添加颜色标识的一种方法，仅供选择使用。
***
### 2. 标签
**语法：**  
```markdown
![badge](https://img.shields.io/badge/%C2%A9-可修改-DarkOrange)
```
**效果：**  

![badge](https://img.shields.io/badge/%C2%A9-可修改-DarkOrange)  

**备注：**  
[]内表示标签无法显示时显示的内容。后面网址最后一部分`%C2%A9-可修改-DarkOrange`中，第一个参数表示标签框前一半的内容，第二个参数表示标签框后一半的内容，第三个参数控制标签框颜色，当然也可以在[https://shields.io/](https://shields.io/)中的*Your Badge*一栏输入相应参数生成专属url。这里提供一个颜色及对应英文名字查询的网站：[https://html-color-codes.info/color-names/](https://html-color-codes.info/color-names/)。
***
### 3. 锚点链接
**语法：**  
```markdown
[锚点文本](#跳转的标识文本)
```
**效果：**  

[回到顶部](#readme)

**备注：**  
当需要通过点击文本跳转到文中指定位置时，可在跳转目标位置处的标题前添加任意个数的#。加上#后，可通过上面的语法使文本具有指向性，在点击该文本后，即可跳转到你设定好的标识处。把标题名称写入锚点的标识文本中时，有以下几个书写规范：**字母全部转换成小写形式；空格用 - 代替；把多级序号中的 . 去掉**。
***
### 4. 添加表情
**语法：**  
```markdown
:open_mouth:
```
**效果：**  

:open_mouth:  

**备注：**  
在两个 : 之间放入特定代码显示表情，表情列表在官网中可以查询：[官方emoji代码](https://www.webfx.com/tools/emoji-cheat-sheet/)。
***



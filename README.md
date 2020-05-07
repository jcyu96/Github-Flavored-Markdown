README
====
主要记录一些不太经常用到的语法规则，充当个人的markdown备忘录。  
持续更新中......  

![badge](https://img.shields.io/badge/%C2%A9-jcyu-DarkOrange)<br>
***
## 目录  
### [1. 小色块](#1-小色块)  
### [2. 标签](#2-标签)
### [3. 锚点链接](#3-锚点链接)

***
### 1. 小色块
**语法：**  
```markdown
![#色块](https://placehold.it/15/f2ed6f/000000?text=+)
```
**效果：**  

![#色块](https://placehold.it/15/f2ed6f/000000?text=+)  

**备注：**  
[]内表示色块无法显示时显示的内容，把后面网址中的`/f2ed6f/`部分修改成对应颜色的代码，即可设置成你想要的颜色。这可作为添加颜色标识的一种方法，仅供选择使用。
***
### 2. 标签
**语法：**  
```markdown
![badge](https://img.shields.io/badge/%C2%A9-可修改-DarkOrange)
```
**效果：**  

![badge](https://img.shields.io/badge/%C2%A9-可修改-DarkOrange)  

**备注：**  
[]内表示标签无法显示时显示的内容。后面网址最后一部分`%C2%A9-可修改-DarkOrange`中，第一个参数表示标签框前一半的内容，第二个参数表示标签框后一半的内容，第三个参数控制标签框颜色，当然也可以在 https://shields.io/ 中的*Your Badge*一栏输入相应参数生成专属url。这里提供一个颜色及对应英文名字查询的网站：https://html-color-codes.info/color-names/
***
### 3. 锚点链接
**语法：**  
```markdown
[1.1JCYU 成功跳转](#11jcyu-成功跳转)
```
**效果：**  

[1.1JCYU 成功跳转](#11jcyu-成功跳转)

**备注：**  
当需要通过点击文字跳转到文中指定位置时，可在指定位置的标题前添加任意个数的#，即赋予标题属性。加上#后，可通过上面的语法添加具有指向性的文本，点击该文本后，即可跳转到你设定好的标题位置。
***
###### 1.1JCYU 成功跳转

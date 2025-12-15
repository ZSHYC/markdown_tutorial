# <center><font face="黑体" font color=black size=10>Markdown教程</font>

## <center><font face="Times" size=5>zshyc</font></center>

### 一、准备工作
1. **插件**
    - Markdown All in One
    - Markdown Preview Enhanced
    - Markdown PDF
    - Paste Image
2. **创建.md文件，打开同步预览（右上角侧边栏）**
   
### 二、基本语法
1. **标题**
   #一级标题（**#后面要加空格**）
   #二级标题

2. **引用**
   > 引用一段话
   >> 还可以嵌套引用
   
3. **列表**
   1. **无序列表**
    - 减号可以表示无须列表
    + 加号也可以表示无序列表
    * 星号也可以表示无序列表
   2. **有序列表**
   3. **To do list**
    - [x] a
    - [ ] b
    - [ ] c
  
4. **表格**
   | 左对齐 | 居中 | 右对齐|
   | :---- | :----: | ----: |
   | a | b | c |
   | d | e | f | 

5. **段落**
   - 分割线：三个星号
   ***
   - 字体
      | 字体 | 代码 |
      | :--: | :--: |
      | *斜体* | * * |
      | ==高亮== | == |
      | **粗体** | ** ** |
      | ***斜粗体*** | *** *** |
      | ~~删除~~ | ~~ ~~ |
      | <u>下划线</u> | `<u> </u>` |
   - 脚注
      zsh love[^1] hyc！


6. **代码的表示**
   - 单句代码
   `print("hello world")`
   - 代码块
      ```
      import numpy as np
      import torch
      ```


7. **超链接**
   - [教程可参考]：https://www.runoob.com/markdown/md-tutorial.html
   - 更多功能请[点击链接](https://www.runoob.com/markdown/md-link.html)
   - **引用的格式**
      这个链接用 2 作为网址变量 [Google][2]
      这个链接用 runoob 作为网址变量 [Runoob][runoob]

  [2]: http://www.google.com/
  [runoob]: http://www.runoob.com/


8. **图片插入**
   - **使用图床保存图片并实现插入**
      [路过图床]：https://imgchr.com/
   > 把图片拖到路过图床网站里面，会自动生成markdown格式，复制后插入即可，但是图片位置和大小无法更改
   [![pZEfKbQ.png](https://s41.ax1x.com/2025/11/28/pZEfKbQ.png)](https://imgchr.com/i/pZEfKbQ)

   - **使用html语言可以调整图片大小和位置**
      - 原始代码如下
      > `<a href="https://imgchr.com/i/pZEhwy8"><img src="https://s41.ax1x.com/2025/11/28/pZEhwy8.png" alt="pZEhwy8.png" border="0" /></a>`

      - 通过加入一些代码，可以控制图片的位置（left/center/right)
      > `<a href="https://imgchr.com/i/pZEhwy8"><div align=center><img src="https://s41.ax1x.com/2025/11/28/pZEhwy8.png" alt="pZEhwy8.png" border="0" width="80%" height=60% /></div></a>`
    - 调整完的图片如下：
   <a href="https://imgchr.com/i/pZEhwy8"><div align=right><img src="https://s41.ax1x.com/2025/11/28/pZEhwy8.png" alt="pZEhwy8.png" border="0" width="80%" height=60% /></div></a>



### 三、其他操作
   1. **插入latex公式**
      - 行内显示公式：$f(x)=ax+b$
      - 块内显示数学公式：
      $$
      \begin{Bmatrix}
      a & b \\
      c & d
      \end{Bmatrix}
      $$

   2. **html/css语法**
      - ctrl+shift+p搜索 “**Markdown Preview Enhanced:Customize CSS**"
      - 在style中使用css语法改标题格式等
         > 例如
         [![pZEIGo4.png](https://s41.ax1x.com/2025/11/28/pZEIGo4.png)](https://imgchr.com/i/pZEIGo4)
      

### 四、导出为pdf
   1. 直接右键，利用**Markdown PDF**插件导出
   2. 右键选择**Open in Browser**在浏览器中打开并保存
      [![pZEhNWt.png](https://s41.ax1x.com/2025/11/28/pZEhNWt.png)](https://imgchr.com/i/pZEhNWt)




[^1]: love是爱的意思

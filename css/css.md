# css部分属性

## 文本属性

![font](../img/font.PNG)

`Tips`

1. 一行字居中可以用 line-height 等于父容器的 height
2. <a>不要下划线可以用 text-decoration:none

## 字体属性

![字体font](../img/字体font.PNG)
![font写法](../img/font写法.PNG)

## 背景

![背景属性](../img/背景属性.PNG)

`Tips`

1. 背景图片的填充方式 background-repeat:no-repeat

## 超链接

![超链接](../img/超链接.PNG)

`Tips`

1. CSS超链接必须按一下顺序定义属性：link > visited > hover > active (`L`o`v`e & `Ha`te)

## 列表
|列表|list-style-type|list-style-position|
|-:-|-:-|-:-|
|![列表](../img/列表.PNG)|![liststyletype](../img/liststyletype.PNG)|![liststyleposition](../img/liststyleposition.PNG)|

`Tips`

1. list-style-image: url("路径");

## 表格

`Tips`

1. 表格边框合并： border-collapse:collapse
2. 表格边框样式： ```table,td,th{ border: 1px solid #fff; }```
3. 奇偶选择器隔行显示不同颜色：```tr:nth-child(odd|even){background-color:#eee;}```
	
# css布局与定位

![页面布局](../img/页面布局.PNG)

## 盒子模型

|盒子模型|具体属性|
|-：-|-：-|
|![盒子模型](../img/盒子模型.PNG)|![盒子模型具体](../img/盒子模型具体.PNG)|

`Tips`

1. margin属性上下合并，左右不合并（取margin-top和margin-bottom较大的距离作为上下间距)；水平方向不合并

### overflow

![overflow](../img/overflow.PNG) 

### border

![border](../img/border.PNG)

### 水平居中

![水平居中](../img/水平居中.PNG)

## 定位机制

![定位机制](../img/定位机制.PNG)

### 文档流定位

`Tips`

1. 文档流定位三种方式：block、inline、inline-block
2. block独占一行，可以设置宽高，例如div、table、ul、ol、p等
3. inline不独占一行，不可以设置宽高，例如span、a
4. inline-bloc不独占一行，可以设置宽高，例如img

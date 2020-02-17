# 背景
## 用法一：
   background: color、img、size,repeat、attachment, position
## 用法二：
   background-color: .......
   background-image: url(....)
   background-repeat: repeat-x, repeat-y, no-repeat
   background-position: [left/center/right top/center/bottom],[50% 40%],[300px 400px]
   background-size: [100% 100%],[40px 30px]
   background-attachment: fixed

# 文字
1. color:
2. text-align: center, justify, left, right
3. text-decoration: none/ [overline/underline/line-through red]            
4. text-transform: uppercase, lowercase, capitalize
5. text-indent: [ 50px ]                               //缩进
6. letter-spacing: [ 3 px]
7. line-height:[ 200% ,1px]
8. word-spacing:[ 20px ] //只针对因为单词
9. white-spacing: normal(忽略空格), pre(保留空格), nowrap(不换行直到遇到< br >)
10. text-shadow:[5px 10px 5px red]  //水平移动、垂直移动 模糊 颜色
11. font-family: serif ,Times, "Times New Roman"
12. font-style: normal, italic
13. font-size: 16px(默认值) 100% 1em(16px即默认值) //设置body的字体大小为100%
14. font-weight: 100 .... 
## 设置字体
font: font-style font-variant font-weight font-size/line-height font-family (其中大小和字体是必须的)
## 设置连接
a:link{ ... }      // 没有点的时候
a:visited{ ... }   // 点完之后
a:hover{ ... }     // 悬停的时候
a:active{ ... }    // 点击的时候

# 列表
## 方法一：
1. list-style-type: 
2. list-style-position:
3. list-style-image:

## 方法二：
list-style: 

# 表格
1. border: 1px solid balck (tabel, th, td都生效)
2. border-collapse: collapse(tabel生效，去掉外部框)
3. text-align:
4. vertical-align
5. background-color: 
6. caption-side: (表的标题的位置)

# 图片
1. vertical-align: text-top, text-bottom              

# 盒子模型
简写时4个为顺时针，3个为上，左右，下，2个为上下， 左右
## border
### 简写：
border: width solid red
### 属性
1. border-style: dotted,dash,solid,double,groove
2. border-width:
3. border-color:
4. border-[right, top, left, bootom]-[ style,width,color ]  //设置单边属性
## outline
### 简写
outline: width style color

### 属性
1. outline-style:
2. outline-width:
3. outline-color:

## margin
### 简写
margin: [1px 1cm 25%]

### 属性
1. margin-[bottom, top, left, right]

## padding
### 简写
padding: 1px 1cm 10%
### 属性
padding-[top. bottom, left, right]

# 尺寸
1. height: [1px, 100%]
2. width: 
3. [max, min]-[height, width]:1px, 100%

# 显示
1. display: none(不显示，但是占用空间)， inline(元素为内联)，block(块)
2. visibility: hidden, collapse
3. position: static, fixed, relative(相对位置)，absolute, sticky(必须指定left，right，top，bottom必须指定一个)
4. left, right, top, bottom: 1px
5. z-index: 1（可以有负数） // 用于显示堆叠顺序
6. clip: rect(top-top, right-left, bottom-top, left-left,仅限position为absolute的元素)
7. overflow[overflow-x, overflow-y]: scroll, auto, visible, hidden   (超出部分的显示方法)
8. cursor: crosshair(十字架),move(平移时鼠标的状态)，help（鼠标旁会多一个问号),pointer(小手指),n-resize(只向南北), nw-resize(只想西北-东西),ne-resize(只向东北-西南)，progress(鼠标旁多一个转的圆圈),text(I)，wait(一个旋转的圆圈)
9. float: right,left
10. box-sizing: border-box,content-box;(border-box可以让两个元素并排显示)
11. 居中: margin设置成auto同时设置width；
12. box-shadow 0px(向右平移) 8px(向下平移) 16px(模糊距离) 0px(阴影大小) #123(颜色)

# 选择器
 空格 后代选择器（所有的后代）> 子元素选择器（子元素） + 相邻兄弟选择器 ~ 后续兄弟选择器

# 伪类
1. first-child: 父元素的第一个元素
[!avatar](/伪类.png)
[!avatar](/伪元素.png)
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
7. line-height:[ 200% ]
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
## border
### 简写：
border: width solid red
### 属性
1. border-style: dotted,dash,solid,double,groove
2. border-width:
3. border-color:
4. border-top-style,border-right-style,border-bottom-style,border-left-style:  //设置单边
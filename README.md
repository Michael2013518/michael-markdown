# Markdown
Markdown是一种轻量级标记语言，它以纯文本形式(易读、易写、易更改)编写文档，并最终以HTML格式发布。
Markdown也可以理解为将以MARKDOWN语法编写的语言转换成HTML内容的工具。
# Markdown语法
Markdown语法主要分为如下几大部分： 标题，段落，区块引用，代码区块，强调，列表，分割线，链接，图片，反斜杠 \，符号'`'
## 1. 标题
两种形式  
1）使用= 和 -标记一级和二级标题。

> 一级标题  
> \=======  
> 二级标题  
> \-------  


2)使用#，可表示1-6级标题。

> # 一级标题  
> ## 二级标题  
> ### 三级标题  
> #### 四级标题  
> ##### 五级标题  
> ###### 六级标题

## 2. 段落  
段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用两个以上空格加上回车（引用中换行省略回车）。

## 3. 区块引用  
在段落的每行或者只在第一行使用符号>,还可使用多个嵌套引用

> \> 区块引用  
> \>>嵌套引用  

## 4. 代码区块  
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）,或者，您可以使用 3 个反引号在代码块之前和之后
```
void main()    
{    
printf("Hello, Markdown.");    
}    
```

## 5. 强调  
在强调内容两侧分别加上*或者_, *:斜体，_:粗体

> *斜体*  
> _粗体_

## 6. 列表  
使用*、+、或-标记无序列表，标记后面最少有一个_空格_或_制表符_。若不在引用区块中，必须和前方段落之间存在空行。

> - 第一项  
> * 第二项  
> + 第三项  

有序列表的标记方式是将上述的符号换成数字,并辅以.，  

> 1. 第一项  
> 2. 第二项  
> 3. 第三项

## 7. 分割线  
分割线最常使用就是三个或以上*，还可以使用-和_。

***

## 8. 链接  
链接可以由两种形式生成：行内式和参考式。

行内式：  
> [Markdown语法](https://github.com/Michael2013518)  

参考式：  
> [Markdown语法][1]
> [1]:https:://github.com/Michael2013518 "Markdown"

## 9. 图片  
添加图片的形式和链接相似，只需在链接的基础上前方加一个！

## 10. 反斜杠 \\  
相当于反转义作用。使符号成为普通符号。  

## 11. 符号 '``'  
\` 起到标记作用。  

> `ctr + a`  

## 12. 表格  
用|表示表格纵向边界，表头和表内容用-隔开，并可用:进行对齐设置，两边都有:则表示居中，若不加:则默认左对齐。

| 每天 | 主食 | 价格 |
|--------|--------|--------|
|周一 | 面食 | ￥10|
|周二 | 沙拉 | ￥20 |

[备注：关于其它扩展语法可参见具体工具的使用说明。]

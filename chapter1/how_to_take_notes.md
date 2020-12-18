氨基酸的离开房间
=======================
二级标题
----------------
# 芜湖
## 芜湖
### 芜湖
#### 四级标题
##### 五级标题

啦啦                 啦啦        
啦啦啦

点零四零六       
run

-------------

~~baidu.com~~

<u>baidu.com</u>

-----------------
*斜体*
_xieti_  
lalala
**粗体***斜体*
***粗斜体***

-----------------
*鼠标放在上面看看*[^1]  
[^1] : 这里是脚注

----------
- 第一项
内容
钉钉
    - 啦啦啦
    - 芜湖
    - 济南屁王

- 第二项
1. 啦啦啦
1. 上了飞机
1. slkdjf

# <u> sdfs </u>  

--------------

~~sfsd~~

> 最外 层  
> fsdf
>> 第一次嵌套
>>> 第二层嵌套  
>>> * sss
>>> 1. laalal
>>>> 1. lfs



---------
第三方  

-----------
## Markdown 代码

* 使用 ` 包围函数 
 
例如：`printf()` 函数

* 代码前加上一个tab  

        import numpy as np
        a,b,m_expression = input('输入下限，上限，函数    ').       split        ()
        a = eval(a)
        b = eval(b)
        segs = eval(input('输入精度'))
        count = 0
        area = 0
        for x in np.linspace(a,b,segs):
            aprx_area = exec(m_expression) *(b-a)
            area += aprx_area
            count += 1
        output = area/count
        print(output)

* 代码用三个 ` 包围，并可以标注用哪种语言  
    ```python
    import numpy as np
    a,b,m_expression = input('输入下限，上限，和被积函数').split    ()
    a = eval(a)
    b = eval(b)
    segs = eval(input('输入精度'))
    count = 0
    area = 0
    for x in np.linspace(a,b,segs):
        aprx_area = exec(m_expression) *(b-a)
        area += aprx_area
        count += 1
    output = area/count
    print(output) 
    ```
-------
## Markdown 链接
> 使用方法如下：  
    1. `[链接名称](链接地址)` 
    2. `<链接地址>`   

这是百度的链接[baidu](https://www.baidu.com/)  
<https://www.baidu.com/>

>  ***高级链接：***  

这个链接可以作为网址变量[baidu][1]



[1]: https://www.baidu.com/

-------
## Markdown 图片

> `![alt 属性文本](图片地址 "可选标题")`  

![runoob的图标](http://static.runoob.com/images/runoob-logo.png)  

>*Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 <img> 标签:*  
`<img src="http://static.runoob.com/images/runoob-logo.png" width="50%">`

<img src="http://static.runoob.com/images/runoob-logo.png" width="70% ">  

需要补充html知识

--------
## Markdown 表格

|表头|表头|
|----|----|
|单元格|单元格|
|单元格|单元格|

> 对齐方式  

|左对齐 |右对齐|居中对齐|
|:---|---:|:-----:|
|unit|unit|unit|
|unit|unit|unit|

---------
## Markdown 高级技巧
> 用 \ 转义

**文本加粗**  
\*\*文本加粗\*\*

>插入数学公式 用两个美元$$包裹  


$$ f(x)=sin(x)+12  $$







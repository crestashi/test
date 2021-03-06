# markdown参考文档
## 标题

<pre>
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
*显示效果如下：*
</pre>
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
<pre>
注意：
一共六级标题
#号之后加空格
</pre>
***********
## 分隔线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：

    *******
    ---------------
    _________________
    * * * *

*******
---------------
_________________
* * * *
## 代码区块
    要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以
    或者<pre></pre>
    或者<code></code>
<pre>
fsdfadfd
fdsfsdfs
fsdfsd
dfsdfs              pre
</pre>
<code>
dfdfdfjdffhjdhjkfdjafs       code
</code>

    djfklsdfja
    fdkljklfjsdalfd
    fjklajskldf
    jkdljfad    缩进一个制表符即可
__________________________
## 区块引用
    jkdjkf
    kjfkljds
    jdfklsj
**********************
## 列表
无序列表

    * red
    + green
    - blue
有序列表
    
    1. 你好
    2. hello
    3. my
+ 你好
+ 哥哥
+ 妹妹
5. red
3. green
2. gay
______________
## link
    Markdown 支持两种形式的链接语法： 行内式和参考式两种形式。

    不管是哪一种，链接文字都是用 [方括号] 来标记。

    要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可

    如果你是要链接到同样主机的资源，你可以使用相对路径：

    参考式的链接是在链接文字的括号后面再接上另一个方括号，而在第二个方括号里面要填入用以辨识链接的标记：

    你也可以选择性地在两个方括号中间加上一个空格：

    接着，在文件的任意处，你可以把这个标记的链接内容定义出来：

    链接内容定义的形式为：

    方括号（前面可以选择性地加上至多三个空格来缩进），里面输入链接文字

    接着一个冒号

    接着一个以上的空格或制表符

    接着链接的网址

    选择性地接着 title 内容，可以用单引号、双引号或是括弧包着

    下面这三种链接的定义都是相同：
        [foo]: http://example.com/  "Optional Title Here"
        [foo]: http://example.com/  'Optional Title Here'
        [foo]: http://example.com/  (Optional Title Here)

test:   
[百度](https://www.baidu.com// "baidu")
//行内式    
[百度][https://www.baidu.com//]
_________________
## 强调
    *斜体*  
    **粗体**    
    ***斜体加粗***
*斜体*  
**粗体**    
***斜体加粗***
___________________
## 引用图片
Markdown 使用一种和链接很相似的语法来标记图片，同样也允许两种样式： 行内式和参考式。

    ![Alt text](/path/to/img.jpg)
    ![Alt text](/path/to/img.jpg "Optional title")
    一个惊叹号 !

    接着一个方括号，里面放上图片的替代文字

    接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。 

参考式的图片语法则长得像这样：

    ![Alt text][id]
    [id]: url/to/image  "Optional title attribute"
    到目前为止， Markdown 还没有办法指定图片的宽高，如果你需要的话，你可以使用普通的 <img> 标签。

test:   
![](/E:/project/note/1.jpg)
___________________________







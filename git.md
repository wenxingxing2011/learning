[TOC]
#markdwon学习与使用

##一，文字基本使用
####1.1,字体

*斜体* <br>
**粗体**<br>
~~删除线~~ <br>
<u>下划线</u>

####1.2,引用
>引用内容
>>嵌套引用

行内代码实现
```C
int mian(){
	
	printf("hello word");
}
```

```javascript
var i =0;
var j = 0;
```
####1.3换行
比较简单的办法是连续敲入两个空格然后回车  
本方法是插入<br /\>标签
##二，列表
1. 有序列表
2. 有序列表
3. 有序列表 

##三，表格

| Tables        | Are           | Cool  |
| ------------- |-------------| -----|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |  

****
****
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

##四，链接和图片 
[link]:http://example.com/ "http://example.com/"
[image]:http://img3.fengniao.com/photo2012/200x200c/4/481/3316481.jpg "天坛"
 <!-- 链接有两个参数  第一个是具体要跳转的地址  第二个是鼠标放上去后的提示问题吧 -->
[链接文本][link]
#####放一张天坛的图片<br>
![天坛][image]


##五，目录和脚注
在md文件的最开头位置加上[TOC]即可   
**存储快照**[^flashphoto] *(请点击上面的小1 看脚注)*
[^flashphoto]:关于指定 数据集合的一个完全可用拷贝，该拷贝包括相应数据在某个时间点（拷贝开始的时间点）的映像。快照可以是其所表示的 数据的一个副本，也可以是数据的一个复制品。

##六，分割线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：



##七，示例源码
[源码](http://example.com/ "http://example.com/")

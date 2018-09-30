制作一个HTML5小游戏指南
============

###  STEP 1
* 下载安装construct2

**construct2可以用来制作2D类型的小游戏**

### 点击下面链接

[construct2下载链接](http://example.com/ ) 


### STEP 2

* 建立新文件开始制作游戏

按照图示

FIRST

![](images\filenew.png)

NEXT

![](images\newfile2.png)

AND It's OK!

### STEP 3

* 插入背景图片

按照图示

FIRST

![](images\wu.png)

NEXT

![](images\insertobject.png)

AND THEN

![](images\loadtexturefromfile.png)

然后选择一张游戏背景图片

**例如**

![](images\background.jpg)

然后选择一个恰当的比例

点击背景图片

然后看到

![](images\size.png)

Position是指背景图片所在的位置，调为 0，0

Size是背景图片的大小

点击没有背景图片的空白处

再看左边的Layout Size

![](images\wsize.png)

这是游戏中的object能活动的范围，将背景图片的Size大小写入Layout Size中

### STEP 4

这里对于layer(层)的概念做出一点解释，在construct2中，把object放在类似玻璃一样的layer上，例如背景图片在Layer 0上，锁定，就不会在点击到背景图片。增加另一层“层”，就可以添加其他的object。

* 锁定背景层，然后添加一层“层”

看图

![](images\layer.png)

Layer 0是背景图片所在的层。点击🔒，锁定背景图片层。

然后点击➕号，添加一层“Layer 1”
### STEP ５

 添加object（精灵）到Layer 1上

 可以直接把图片拖到construct2，这样就可以简简单单的添加精灵了

主页君给大家送几个精灵图片

![](images\snowman.png)
![](images\sss.png)
![](images\attack.png)
![](images\1.png)

### STEP 6

给精灵添加行为

接下来简单介绍一下几个常用的“行为”（behave）



 
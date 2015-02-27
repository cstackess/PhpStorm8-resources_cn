# PhpStorm8的汉化包修复

A Chinese resources jar package for PhpStorm 8 of JetBrains, which can translate most vocabularies in GUI to Chinese.


在下[PhpStorm8的汉化包](http://www.newasp.net/soft/100485.html)时，按照步骤

> (1) 找到PhpStorm安装目录下的\lib\resources_en.jar
> (2) 复制一份为resources_cn.jar用rar打开(仅打开而不是解压), 把下载的汉化文件拖到压缩包内的文件夹(\messages)，使得lib中多了一个resources_cn.jar

但是程序启动时会报错。在[此文](http://www.526net.com/blog/biancheng/544.html)中提示

> 仔细检查了下，应该是IdeBundle.properties文件中多了几个空格造成的

用了还是不行，于是自己拷了resourse_en.jar里的IdeBundle.properties出来替换掉之前的汉化包。可以正常启动了，但是这到底是谁干的！！！

![有道](http://ww1.sinaimg.cn/large/005K3Lexgw1ep9a2o2fqbj30yw0k8afz.jpg)
![unicode](http://ww3.sinaimg.cn/large/005K3Lexgw1ep9a2olun5j30zp0lc4ci.jpg)

把所有文件里的用unicode编码的“有道”替换后，终于可以用舒心使用汉化包了～

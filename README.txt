文档包含3个工具

apktool:解压apk文件，查看代码和资源

apktool.bat,apktool.jar

dex2jar:将dex文件转换为jar文件

dex2jar-2.0.zip

jd-gui:Java源码浏览器（需要jar文件）

jd-gui-windows-1.2.0.zip


前置条件：

jdk 1.7+

反编译步骤：

1.将apk文件拷贝到build目录下
2.重命名为.zip
3.解压得到classes.dex文件
4.使用dex2jar中的d2j-dex2jar.bat脚本将classes.dex转为jar文件
5.打开jd-gui，浏览jar文件
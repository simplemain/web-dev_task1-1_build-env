## web开发::Task1-1::搭建环境

老王以Java为例，跟大家一起实际动手开发web服务器，第一步就是先搭建环境<br>
ps：因为老王比较喜欢Java做服务器开发，嘿嘿~ 如果大家用其他语言，也可以搭建其他语言的开发环境，原理是一样的<br>

### 下载并安装java虚拟机
* download: 到oracle官网下载Java SE 8就可以，这里是[下载地址](http://www.oracle.com/technetwork/indexes/downloads/index.html#java)
* install: 按照说明安装即可
* configure path: 在命令行(cmd/shell)中输入java，如果提示没有该命令，需要在PATH环境变量中配置java、javac等的路径，具体可以百度搜索"path环境变量"，或类似关键字
* run test: 在命令行(cmd/shell)中输入javac、java提示相关用法，说明安装成功

### 下载并安装ant : 编译工具
ant类似于c语言的make一样，可以让我们更方便的编译java代码<br>
* download: 到apache官网下载ant，这里是[下载地址](http://ant.apache.org/bindownload.cgi)
* install: 按说明安装即可
* configure path: 在命令行(cmd/shell)中输入ant，如果提示没有该命令，需要在PATH环境变量中配置ant的路径，具体可以百度搜索"path环境变量"，或类似关键字
* run test: 在命令行(cmd/shell)中输入ant提示相关用法，说明安装成功

### 下载并安装jetty : j2ee runtime 环境
jetty是J2EE的运行时框架服务器，和tomcat、resin一样，不过他非常小巧，跑起来很快，老王就特别喜欢简单的东西
* download: 老王比较懒，用的一直是8.0.0的版本，这里是[下载地址](http://repo2.maven.org/maven2/org/mortbay/jetty/jetty-hightide/8.0.0.v20110901/)，现在已经是eclipse的项目了，所以如果想下载新版可以去eclipse官网下载（但是配置和老版本不一样了，所以想复用老王代码的，可以就下载老版本）
* install: 不用安装，解压即可
* configure path: 需要配置JETTY_HOME环境变量，具体可以百度搜索"环境变量配置"，或类似关键字。这是老王的配置：echo $JETTY_HOME
/Users/simplemain/java_soft/jetty-hightide-8.0.0.v20110901

<br><br>
好了，只要安装好以上工具，就可以进行相关web应用的开发了~~

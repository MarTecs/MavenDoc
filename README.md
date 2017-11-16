## MavenDoc
This is to describe how to use maven tool!
<br />
![](https://camo.githubusercontent.com/3ba433e9aaff8fb8749c3fa980ff5839515057f8/687474703a2f2f70726f677265737365642e696f2f6261722f32383f7469746c653d70726f6772657373)&nbsp;![](https://camo.githubusercontent.com/5d1e2146f2113a6c55a81d131ba112462f24f23c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f736976616e5775303232322f48696265726e617465446f632e737667)

<br />

------

## maven下载

<a href="http://maven.apache.org/download.cgi">下载</a>




-------

## maven安装以及目录说明

> maven运行需要Java环境的支持，所以应该先要安装jdk，然后安装maven

### 安装
 解压到任意目录(要求目录路径不可以有中文和空格)

### 目录说明
1. bin 存放一些可执行的二进制文件
2. boot 存放引导文件
3. config 存放配置文件
4. lib 存放运行所需的jar包

### 配置maven的环境变量

1. 配置MAVEN_HOME 为 maven的安装路径
2. 在path中配置添加%MAVEN_HOME%\bin;

### 验证maven是否安装成功
> 命令行下键入 mvn -v 
如果打印出 java的版本以及 maven的版本，则说明安装成功！

### 配置本地仓库
> 打开maven安装目录下的conf中的settings.xml文件,并且配置如下

```XML
<localRepository>本地仓库路径</localRepository>
```

### maven标准目录结构

使用maven创建的工程我们称它为maven工程，maven工程具有一定的目录规范，如下：

src/main/java —— 存放项目的.java文件 <br/>
src/main/resources —— 存放项目资源文件，如spring, hibernate配置文件<br/>
src/test/java —— 存放所有单元测试.java文件，如JUnit测试类<br/>
src/test/resources —— 测试资源文件<br/>
target —— 项目输出位置，编译后的class文件会输出到此目录<br/>
pom.xml——maven项目核心配置文件<br/>

![](http://on3w7gc9m.bkt.clouddn.com/QQ%E5%9B%BE%E7%89%8720171116113335.png)




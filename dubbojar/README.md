#如果maven下载不到这个包
1.可以使用这个,复制到仓库的对应目录
2.也可以自己打包.首先需要到github上下载dubbox的源码，地址为https://github.com/shuvigoss/dubbox。
                 然后解压到我们本地目录，进入到该目录下，通过maven进行编译。使用cmd命令进入到该目录下，或者直接按住shift               和鼠标右键点击使用命令行打开，执行mvn install -Dmaven.test.skip=true进行编译。编译时间较长。当然这里是                 把所有项目都编译了，包括dubbo的控制台等等。
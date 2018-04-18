这里提供很多功能，Windows系统调用bat文件，而MAC系统中则调用sh脚本即可。

1）将apk文件后缀名直接改为.zip，并解压。得到其中的classes.dex文件 ，它就是java源代码经过编译再通过dx工具打包而成的。

2）将classes.dex文件复制到dex2jar所在的文件夹。

3）命令行下定位到dex2jar目录，运行
   `sh d2j-dex2jar.sh classes.dex`
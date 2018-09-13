
### apktool（资源文件获取）
资源文件获取，可以提取出图片文件和布局文件进行使用查看

apktool[下载地址](https://bitbucket.org/iBotPeaches/apktool/downloads)

1. 把apk放在和`apktool.jar`这个文件的同一目录下；

2. 执行`java -jar apktool.jar <filename.apk>`或执行`run.sh`脚本，sh脚本代码如下

		read -p "please input apk name:" apkname
		java -jar apktool.jar d $apkname

### dex2jar（源码文件获取）
将apk反编译成java源码（classes.dex转化成jar文件），dex文件可以从apk中zip解压得到

dex2jar[下载地址](http://sourceforge.net/projects/dex2jar/files/)

1. 把dex放在和dex2jar-x.x.zip这个文件的同一目录下；

2. 执行`sh dex2jar-2.0/d2j-dex2jar.sh <dexname.dex>`

		read -p 'please input .dex file name:' dexname
		sh dex2jar-2.0/d2j-dex2jar.sh $dexname.dex


### jd-gui（源码查看）
查看APK中classes.dex转化成出的jar文件，即源码文件

jd-gui[下载地址](http://jd.benow.ca/)

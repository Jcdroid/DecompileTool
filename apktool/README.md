1. 把apk放在和`apktool.jar`这个文件的同一目录下，

2. 执行`java -jar apktool.jar d <filename.apk>`或执行`run.sh`脚本，sh脚本代码如下

		read -p "please input apk name:" apkname
		java -jar apktool.jar d $apkname

资源文件反编译：

1、下载apktool 并配置  
      &#160;&#160;&#160;&#160;&#160;&#160;[下载链接](https://ibotpeaches.github.io/Apktool/install/)

2、配置apktool 到 /usr/local/bin 目录

sudo cp /Users/samir/apktool/apktool.jar /Users/samir/apktool/apktool.sh /usr/local/bin
3、加权限：
```
    sudo chmod +x apktool.jar 
    sudo chmod +x apktool.sh
```
    
Java 源程序反编译：

方法一：
1、下载dex2jar工具放到HackApk文件夹，并将其解压、重命名为dex2jar
        &#160;&#160;&#160;&#160;&#160;&#160;[下载链接](https://github.com/pxb1988/dex2jar)
2、配置dex2jar 环境变量
```
     #dex2jar 
     export PATH=$PATH:/Users/samir/HackApk/dex2jar  
```
3、使用dex2jar命令反编译
```
    sh d2j-dex2jar.sh your.apk
```

方法二：
1、下载enjarify工具 https://github.com/google/enjarify
2、配置enjarify 环境变量
```
      #enjarify   
      export PATH=$PATH:/Users/samir/HackApk/enjarify  
```
    
3、使用enjarify命令反编译apk
```
     => ：enjarify yourapp.apk
```
    
###查看Java反编译源码
下载JD-JUI 查看:  
 &#160;&#160;&#160;&#160;&#160;&#160;[下载链接]( http://jd.benow.ca/)


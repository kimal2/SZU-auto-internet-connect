# SZU自动联网

在Windows登录时自动执行联网脚本



## 1.首先需要安装Python，然后安装requests

​	1.安装Python，这里不做教程，自行B站

​	2.安装完成后，打开cmd输入以下命令来安装requests库

​	`pip install requests`



## 2.获取url

​	1.进入登录界面按F12选择网络

​	2.输入账号密码点击登录，接着会看到右边有刷新  选择login?callback那一行，复制请求URL里的链接

​



## 3.编辑Python代码

​	1.打开IDLE，可以在Windows桌面搜索框里直接搜索

​	2.点击左上角FIle→Open找到在GitHub里下载的szuconnect.py打开

​	

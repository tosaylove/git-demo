1、安装git
下载地址：https://git-for-windows.github.io
创建一个文件夹（比如Git），把把要控制的资源代码复制过去
2、创建存储文件仓库
右键点击想要存储的目录；（比如Git目录下，自己创建的文件夹），选择Git base here运行程序
命令：git init
此时目录下多出一个.git目录
3、查看文件控制状态
命令：git status
4、把添加控制文件
git add 
5、添加本地忽略文件
命令：echo '' >> .gitignore  （创建一个.gitignore）
打开填写不需要的文件名即可。

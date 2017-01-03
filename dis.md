1、安装git
下载地址：https://git-for-windows.github.io

2、创建存储文件仓库
在项目文件夹下。 右键，选择Git base here运行程序
命令：git init
此时项目下多出一个.git文件夹。（注意是影藏文件夹，设置显示影藏文件夹）；
3、查看文件控制状态
命令：git status
 
4、添加本地忽略文件
命令：echo '' >> .gitignore  （创建一个.gitignore）
打开填写不需要的文件名即可。
5、把控制文件添加进去
命令：git add .  （就是所有的了）
6、提交文件
命令：git commit -m '提示信息随便写'      
成功会提示 creat model 。。。。
7、改动文件试试
8、再次 命令：git status -s   看看 （多个s显示得详细）
会提示改动（modified）的文件，删除会提示删除的文件，
。。。
9、查看修改日志
命令 git log。
**注意**：每次修改过后需要重新  git add .  然后git commit -m '提示信息随便写'。才能保存日志。
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
命令 git log
**注意**：每次修改过后需要重新  git add .  然后git commit -m '提示信息随便写'。才能保存日志。
**因此**：有事情完成后在改动，比如一个图片轮播图效果
10、回到之前状态
  命令：git reset --hard 18eb23  （18eb23是 commit后面值的前六位。）
 11、以上都是在本地，但是项目开发一般是协同开发，因此需要一个git服务器来同步本地的代码 **仓库**
 git服务器有git服务器提供商（githup）。githup是一个网站。githup的东西都是‘免费’的；不开源的需要money。
guihup.com
注册：445223263@qq.com
新建一个仓库
一、推送到远端：
①添加一个远端地址：
命令 ：git remote add origin https://github.com/tosaylove/git-demo.git （网上有代码）
②把本地的推送到远端。
命令：git push origin -u master
会提示输入用户名密码
③刷新浏览器。
二、重远端pull过来
(比如说某某在远端修改了什么就重远端下载过来)
命令：git pull origin master

三、查看\新建分支\切换 分支
命令：git branch
四、新建分支
命令：git branch name
五、切换分支
命令：git checkout v2
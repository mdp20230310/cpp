# cpp
C++ Primer Plus

环境搭建：
1.进入GitHub官网注册账号（https://github.com）。
  点击界面右上角的加号，选择New repository,新建一个仓库。

2.下载GitHub Desktop (https://desktop.github.com)。
  登录账号与网页版相同。刷新一下，右边会出现已有的仓库。可以将官网的仓库克隆到本地文件夹。

3.下载Visual Studio Code。勾选add code to PATH。
  安装插件：1.Chinese  2.C/C++   3.C/C++ Extension Pack   4. Code Runner 

4.下载Windows下的C/C++的gcc编译器MinGW-w64(官方下载网站：https://sourceforge.net/projects/mingw-w64/)。
  解压到自定义的路径，进入bin目录，并将路径复制下来。
  右击我的电脑，属性，点击高级系统设置，环境变量 。
  在系统环境变量窗口选择Path，点击编辑，点击新建，粘贴路径。点击确定，配置完成。
  在命令提示符中输入gcc -v，将会显示MinGW-w64的组件列表。如果命令提示符显示了一大串组件信息，说明安装完成。

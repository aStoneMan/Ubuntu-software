# Ubuntu-software
how to create a environment for your Ubuntu
<br />首先我们使用U盘安装Ubuntu
<br />选择硬盘的空闲区域
<br />分区一：挂载点：“/” 新分区的类型：主分区 新分区的位置：空间起始位置 用于：EXT4日志文件系统
<br />分区二：挂载点：（不设置） 大小：1024MB 新分区的类型：逻辑分区 新分区的位置：空间起始位置 用于：交换空间
<br />分区三：挂载点：/boot  大小：200MB 新分区的类型：逻辑分区 新分区的位置：空间起始位置 用于：EXT4日志文件系统
<br />分区四：挂载点：/home  大小：剩下多少给多少 新分区的类型：逻辑分区 新分区的位置：空间起始位置 用于：EXT4日志文件系统
<br />键盘布局：英语（美国）
<br />安装结束后
<br />按住Ctrl+Alt+T 唤出Terminal 升级你的VIM
<br />输入sudo apt-get install vim-gtk 回车 
<br />输入sudo apt-get install ack-grep ctags 回车
<br />输入sudo apt-get install git 回车 
<br />输入git clone git://github.com/humiaozuzu/dot-vimrc.git ~/.vim 回车 
<br />输入ln -s ~/.vim/vimrc ~/.vimrc 回车
<br />输入git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle 回车 
<br />打开vim，执行:BundleInstall 
<br />以上就完成了VIM的升级
<br />然后我们需要安装xampp
<br />https://www.apachefriends.org/index.html  登陆此网站下载所需内容
<br />输入cd /下载/       转移到下载目录
<br />输入ls              查看下载的文件
<br />输入chmod +x 你下载的文件的名       授权使用该文件
<br />输入sudo ./你下载的文件名           执行你的文件
<br />执行安装
<br />如果你需要一个虚拟机请去看看我的另一篇文章。  
<br />https://github.com/aStoneMan/VMware-Workstation-Ubuntu/blob/master/README.md
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

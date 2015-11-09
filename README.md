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
<br />
<br />
<br />
<br />
<br />
<br />然后我们需要安装xampp
<br />https://www.apachefriends.org/index.html  登陆此网站下载所需内容
<br />输入cd /下载/       转移到下载目录
<br />输入ls              查看下载的文件
<br />输入chmod +x 你下载的文件的名       授权使用该文件
<br />输入sudo ./输入cd /下载/       转移到下载目录你下载的文件名           执行你的文件
<br />执行安装
<br />
<br />
<br />
<br />
<br />
<br />如果你需要一个虚拟机请去看看我的另一篇文章。  
<br />https://github.com/aStoneMan/VMware-Workstation-Ubuntu/blob/master/README.md
<br />
<br />
<br />
<br />
<br />
<br />可能你还需要一款在ubuntu下的词典，你可以搜索星际译王，下载使用。但是你会发现，他里面并没有词典需要自行下载，可是因为它已经失去支持。无法从官方途径下载。你会需要到以下网站下载
<br />到http://abloz.com/huzheng/stardict-dic/zh_CN/ 下载需要的词库
<br />输入cd /下载/       转移到下载目录
<br />输入sudo tar -xjvf stardict-oxford-gb-2.4.2.tar.bz2     进行解压
<br />输入sudo mv stardict-oxford-gb-2.4.2 /usr/share/stardict/dic/ 将解压后的文件夹移动到 /usr/share/stardict/dic/文件夹下面
<br /><pre>如果你的/usr/share/里面没有stardict/dic/目录，进入/usr/share/创建即可
cd /usr/share/
sudo mkdir stardict
cd stardict/
sudo mkdir dic</pre>
<br />重启星际译王即可看到词典
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

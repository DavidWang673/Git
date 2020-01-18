# 一、 安装git for windows

https://git-scm.com/download/win 一路回车

# 二、 配置SSH连接GitHub

右键菜单，打开git bash<br>
输入 ssh-keygen 一路回车<br>
复制id_rsa.pub公钥内容到github(Settings--> SSH and GPG keys--> new SSH key)<br>

# 三、 命令

从GitHub拉取项目到本地： git clone<br> 
从本地push到GitHub： git remote add origin https://github.com/******.git<br>
&nbsp;&nbsp;&nbsp;&nbsp;git push -u origin master<br>



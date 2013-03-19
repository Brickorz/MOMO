仿陌陌的客户端开源   



本人最近开发的仿陌陌客户端（momo）开放源代码


软件功能：模仿陌陌客户端，功能很相似，注册、登陆、上传照片、浏览照片、浏览查找附近会员、关注、取消关注、聊天、语音和文字聊天，还有拼车和搭车的功能，支持微博分享和查找好友。
后台是php＋mysql，前台是xcode工程



ios前台和后台数据库脚本、php文件均已上传，欢迎网友下载和参考使用，完全开源。






更新地址：


前台：


https://github.com/zengchao/MOMO


后台：


https://github.com/zengchao/MOMO_SERVER





安装说明：
1  mysql的数据库名称demo
2  把demo.sql脚本导入mysql
3 安装服务器的php环境，复制webroot目录下的文件到你的主机根目录，我用的是apache php mysql
4 xcode工程中Global.h中定义了host_url，这个变量你需要修改一下，改为你自己的服务器url，比如http://www.yourdomain.com/

# 1

直接运行本项目中的附件[steamcn.html](https://github.com/zhz1237ok/STCN_solution/blob/master/SteamCN.html)

<html>
<head><meta http-equiv="refresh" content="5"></head>
<frameset>
<frame src="https://steamcn.com/" name="iframe">
</frameset></frameset>
</html>

# 2

安装Screen
登录steamcn F12提取自己的cookies FTP传输到服务器

<pre>while : ;do wget -x --load-cookies cookies.txt "https://steamcn.com/"; sleep 600; done;</pre>


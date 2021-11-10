##服务的停止和启动
	net stop MySQL80
	net start MySQL80

##cmd进入和退出MySQL
	进入数据库
	mysql -h localhost -P 3306 -u root -p123456
	mysql -u root -p123456
	cmd或MySQL 8.0 Command Line Client(只适合root用户)退出数据库
	exit/ctrl+C

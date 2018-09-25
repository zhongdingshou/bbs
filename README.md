# bbs
个人学习PHP - 简单论坛小系统 
 
采用原生PHP开发

目录结构：
--bbs
	--admin
	#管理员目录
		--admin.php
		--advices.php
		--index.php
	--configure
	#配置文件目录（常量定义）
		--config.php
	--inc
	#权限验证文件、数据库操作文件、生成验证码文件目录
		--admin_check_session.php
		--common_check_session.php
		--members_check_session.php
		--mysql.php
		--vcode.php
	--public
	#静态资源文件、公共函数文件、接口定义文件目录
		--css
			--admin.css
			--index.css
			--login.csss
			--register.css
			--table.css
		--font
			--ManyGifts.ttf
		--images  
			#图片资源
		--js
			--index.js
			--jquery1.7.js
			--jquery-1.8.2.min.js
		--functions.php
		--operate.php
	--users
	#会员、普通用户目录
		--_upgrade.php
		--admin.php
		--advice.php
		--common.php
		--members.php
		--upgrade.php
	#首页文件
	--index.html
	#登陆前端文件
	--login.html
	#登陆处理文件
	--login.php
	#注销处理文件
	--logout.php
	#注册前端文件
	--register.html
	#注册处理文件
	--register.php
	#路由文件
	--router.js
	#验证码显示处理文件
	--show_code.php


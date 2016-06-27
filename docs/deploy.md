#配置

修改tasks目录**test-deploy.json | production-deploy.json**

	{
	  "host": "192.168.0.53",--远程主机名
	  "username": "root",--用户名
	  "password": "******",--密码
	  "path": "/opt/buildapp/tmp/"--发布目录
	}

#发布

	grunt localDeploy --发布应用到本地测试环境
	grunt productDeploy --发布应用到正式环境
# point
# 基于光透射原理的算法进行判断一个点是否位于多边形里面

# 安装方法：
1.配置vhost文件与host文件
vhost:
		<VirtualHost *:80>
		     ServerName local.point.com
		     DocumentRoot "D:\phpStudy\WWW\point"
		     SetEnv APPLICATION_ENV "development"
		     <Directory "D:\phpStudy\WWW\point">
		         DirectoryIndex index.html
		         AllowOverride All
		         Require all granted
		     </Directory>
		</VirtualHost>
host
		127.0.0.1		local.point.com
2.在输入框输入数值  进行判断

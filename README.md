# middleware_security_check
</br>
主要通过python脚本检测各种中间件的基础安全配置项是否存在安全隐患</br>
比如：</br>
- banner信息是否隐藏
- 默认用户名和密码是否修改
- 默认控制台路径和端口是否修改
- 404页面是否包含敏感信息
- 是否root用户启动中间件
- options、put、delete方法是否开启
- 是否具有正常的安全审计日志
- 是否webroot目录存在备份文件

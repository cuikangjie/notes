#git设置代理

查看git配置

git config --list



git设置代理（一般用于公司内部网络，如果上网正常，不需要设置）

git config --global http.proxy ip:port

git用户名

git config --global user.name "FIRST_NAME LAST_NAME"

配置email

git config --global user.email "MY_NAME@example.com"


====
参考文档：http://www.linuxidc.com/Linux/2015-04/116215.htm

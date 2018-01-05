# mysql笔记

## 一、linux下安装mysql
### 确认是否已经安装过mysql
```
# yum list install mysql
```
### yum安装mysql客户端
```
# yum install mysql
```

### yum安装mysql服务器
```
# yum install mysql-server
# yum install mysql-devel
```

### yum安装mysql-server时报找不到安装包错误的解决办法
<br>
![](../../image/mysql-01.png)

<br>
手动下载并安装mysql-server包
```
# wget http://repo.mysql.com/mysql-community-release-el7-5.noarch.rpm  
# rpm -ivh mysql-community-release-el7-5.noarch.rpm  
```
添加包到yum
```
# ls -1 /etc/yum.repos.d/mysql-community*
```
再执行install命令
```
# yum install mysql-server  
```
<br/>
## 运行mysql
### 启动mysql服务
```
# service mysqld start
# mysql
```

### 设置管理员密码
```
# mysqladmin -u root password "****"
```
管理员登陆
```

```

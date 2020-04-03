# Server-notes
 搭建云服务器学习笔记

## FTP
File Transfer Protocol（文件传输协议）的英文简称，而中文简称为“文传协议”。用于Internet上的控制文件的双向传输。同时，它也是一个应用程序（Application）。基于不同的操作系统有不同的FTP应用程序，而所有这些应用程序都遵守同一种协议以传输文件。

## 常用的web环境
* LAMP
* LNMP（ Ubantu + Nginx + MySQL + PHP）
* JAVA
* Windows
* Node.js Docker

## WordPress
WordPress是使用PHP语言开发的博客平台，用户可以在支持PHP和MySQL数据库的服务器上架设属于自己的网站。也可以把 WordPress当作一个内容管理系统（CMS）来使用。
### 安装条件
推荐服务器运行PHP 7.3或更高版本及MySQL 5.6或更高版本。

## MySQL登录与退出
登录mysql：“输入mysql -u帐号 -p密码 
退出mysql：mysql > exit; 

以下是实例参考下：
登录Mysql：“输入mysql -uroot -p -P3306 -h127.0.0.1”表示超级用户名root,密码稍后输入，端口号3306（不输入P默认为3306）， 主机地址127.0.0.1（若使用本机作为主机，h默认127.0.0.1）

### mysql退出三种方法：
```
mysql > exit;
mysql > quit;
mysql > \q;
```
## CentOS相关指令
```
#安装压缩解压包工具
yum install -y unzip zip

#安装vim
yum install vimy
```
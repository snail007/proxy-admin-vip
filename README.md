# proxy-admin-vip
proxy-admin vip 版本,`功能和免费版一致，服务数量无限制`.

首次使用，直接在命令行执行proxy-admin，等待程序自己退出，会在下面的目录生成id.txt文件，把里面的内容绑定到授权平台即可。   
Windows：C:\gpa\id.txt  
Linux & MacOS : /etc/gpa/id.txt  

[Manual](https://snail.gitee.io/proxy/manual/) ｜ [参考手册](https://snail.gitee.io/proxy/manual/zh/)

手册同时适用于命令行goproxy和proxyadmin面板，控制面板只是命令行goproxy的界面化，使用参数完全一样。

## 国内下载

请在github的下载链接前面加上: `https://mirrors.host900.com/` 。

比如`v2.8`的github下载链接是：

`https://github.com/snail007/proxy-admin-vip/releases/download/v2.8/proxy-admin_linux-amd64.tar.gz`

那么国内下载地址就是：

`https://mirrors.host900.com/https://github.com/snail007/proxy-admin-vip/releases/download/v2.8/proxy-admin_linux-amd64.tar.gz`

此地址也适用于wget，curl直接命令行下载。


## 下载

[点击下载](https://github.com/snail007/proxy-admin-vip/releases)

国内请参考上面的国内下载。

## 安装

[点击查看安装教程](https://github.com/snail007/proxy_admin_free/blob/master/README_ZH.md#%E5%BC%80%E5%A7%8B%E4%BD%BF%E7%94%A8) 

## 购买
  
1. 授权平台可以在线自助购买，点击进入[授权平台](https://gpm.host900.com/)。

2. 特殊需求请发送邮件到：`arraykeys@gmail.com`  

## 升级更新

### Linux
用`root`打开一个终端。

```shell
proxy-admin update
```

已经安装了最新的版本，默认不会更新，如果想强制更新加上 -f 参数即可。

```shell
proxy-admin update -f
```

### Windows
用`管理员`权限打开命令提示符窗口。

```bat
c:\
cd gpa
proxy-admin update
```

已经安装了最新的版本，默认不会更新，如果想强制更新加上 -f 参数即可。

```shell
c:\
cd gpa
proxy-admin update -f
```

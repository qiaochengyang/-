# samba配置

## 安装

* sudo apt-get update
* sudo apt-get install samba samba-common-bin

## 修改配置文件/etc/samba/smb.conf

* sudo vim /etc/samba/smb.conf
* “read only = no”
* sudo /etc/init.d/samba restart
* sudo smbpasswd -a pi

## 检查电脑配置

* 启用Windows功能 SMB文件共享支持
* 打开服务 Function Discovery Provider Host
* 输入"\\\computername\pi"
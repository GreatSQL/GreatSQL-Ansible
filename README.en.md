# GreatSQL-Ansible

## Introduction

How to install GreatSQL and setup a MGR cluster by ansible.

## How to use GreatSQL-Ansible
[ansible一键安装GreatSQL 8.0.27并构建MGR集群](https://gitee.com/GreatSQL/GreatSQL-Ansible/wikis/ansible%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85GreatSQL%208.0.27%E5%B9%B6%E6%9E%84%E5%BB%BAMGR%E9%9B%86%E7%BE%A4?sort_id=5444992)

## Attention
It is recommended to upgrade the jemalloc version up to 5.2.1+, and modify the following line of the file *mysql-support-files/sysconfig/mysql*:
```
#LD_ PRELOAD=/usr/lib64/libjemalloc.so.1
LD_ PRELOAD=/usr/lib64/libjemalloc.so.2
```
Keep the correct one according to the actual situation.

## Contact Us
please scan the qr code with wechat

![输入图片说明](https://images.gitee.com/uploads/images/2021/0802/143402_f9d6cb61_8779455.jpeg "greatsql社区-wx-qrcode-0.5m.jpg")

mail: greatsql@greatdb.com

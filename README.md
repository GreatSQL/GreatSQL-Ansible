# GreatSQL-Ansible

## 介绍
利用ansible一键安装GreatSQL并完成MGR部署。

## 文档
[ansible一键安装GreatSQL 8.0.25并构建MGR集群](https://gitee.com/GreatSQL/GreatSQL-Ansible/wikis/ansible%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85GreatSQL%208.0.25%E5%B9%B6%E6%9E%84%E5%BB%BAMGR%E9%9B%86%E7%BE%A4)

## 注意
推荐升级jemalloc版本，不低于5.2.1，并自行修改文件 *mysql-support-files/sysconfig/mysql* 下面这行：
```
#LD_PRELOAD=/usr/lib64/libjemalloc.so.1
LD_PRELOAD=/usr/lib64/libjemalloc.so.2
```
根据实际情况保留正确的那行即可。

## 联系我们
扫码关注微信公众号

![输入图片说明](https://images.gitee.com/uploads/images/2021/0802/143402_f9d6cb61_8779455.jpeg "greatsql社区-wx-qrcode-0.5m.jpg")

邮箱：greatsql@greatdb.com

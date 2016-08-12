操作步骤
====

1. 按照[一键搭建适用于Ubuntu/CentOS的IKEV2/L2TP的VPN](https://github.com/quericy/one-key-ikev2-vpn)的步骤安装环境
2. 按照[解决CentOS下yum不能使用的错误thread.error: can’t start new thread](http://www.xxkwz.cn/1583.html)来解决低vps内存下yum无法启动的问题
3. yum install git
4. git push origin master 到git仓库，以github作为文件服务器，取到[ca.cert.pem](https://raw.githubusercontent.com/luchigster/myvpn/master/my_key/ca.cert.pem)的地址，用手机扫描二维即可安装证书

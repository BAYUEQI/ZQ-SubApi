# ZQ-SubApi
利用CF Worker搭建的反代订阅转换工具，通过随机化服务器地址和节点账号密码，解决用户转换订阅的隐私问题

### 演示网站
https://subapi.vpnjacky.dpdns.org

### 变量绑定

环境变量名：`BACKEND`

KV或R2变量名：`SUB_BUCKET`

### 支持反代转换的协议
 - shadowsocks
 - shadowsocksR
 - vmess
 - trojan
 - vless(取决于后端)
 - hysteria(取决于后端)

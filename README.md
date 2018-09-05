## 部署v2ray到Heroku的Docker学习示例。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

1.部署时配置 VER(v2ray core 的版本)、UUID(Vmess协议的UUID)。

2.打开APP URL，显示 Bad Request，表示部署成功。

3.客户端配置 ws+443+tls。

nslookup  APPURL.herokuapp.com 8.8.8.8

## 参考
 
* https://github.com/v2ray/v2ray-core

* https://github.com/onplus/v2hero

* https://github.com/wangyi2005/v2ray-heroku

* https://github.com/lnterface/ssr-with-net_speeder
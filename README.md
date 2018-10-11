部署Docker镜像文件到OpenShift的学习示例。


1.部署时配置 VER(v2ray core 的版本)、UUID(Vmess协议的UUID)。

2.服务端使用docker-hub的Image部署,镜像为 [icegreen/websocket-proxy:v2ray-openshift](https://hub.docker.com/r/icegreen/websocket-proxy) 

3.创建Route(secure route->ws->edge )并打开URL，显示 Bad Request，表示部署成功。

## 参考

 
* https://docs.docker.com/docker-hub

* https://docs.openshift.com/online/getting_started/basic_walkthrough.html

* https://github.com/lnterface/ssr-with-net_speeder

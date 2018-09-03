# 一键部署 v2ray 到 heroku [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

1.部署时配置 v2ray core 的版本、Vmess协议的UUID（"alterId"默认为64）和连接缓存。

2.服务端部署后，应 open app ，显示 Bad Request，表示部署成功。

3.更新 v2ray 版本，修改 app settings-->Config Vars-->VER，程序自动重启，通过view Logs确认。


# 参考 
https://v2ray.com/chapter_02/protocols/mtproto.html

https://github.com/yaohunzhanyue/multi-v2ray

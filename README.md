# 一键部署 v2ray 到 heroku [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

1.部署时配置 v2ray core 的版本、Vmess协议的UUID（"alterId"默认为64）和连接缓存。

2.服务端部署后，应 open app ，显示 Bad Request，表示部署成功。

3.更新 v2ray 版本，修改 app settings-->Config Vars-->VER，程序自动重启，通过view Logs确认。

4.客户端配置模版client_config.json（修改//标记行的参数）, 建议使用 cn_sniproxy+websocket+tls 传输协议。


# 参考 
https://github.com/v2ray/v2ray-core

https://github.com/onplus/v2hero/

# v2rayN客户端设置参考
https://github.com/onplus/v2hero/wiki/Deploy-V2ray-To-Heroku


ps:
安卓端BifrostV导入配置成功使用
windows上使用官方客户端时，firefox无法打开外网，显示证书错误，chrome正常；v2rayN可以导入自定义配置，但是也只有chrome能正常使用

# 小程序FAQ
##1、启动白屏
检查白名单是否配置
检查网络情况
是否在后台配置了启动地址


## 2、POST请求报文体为空，接口访问失败
使用xpRequest转发

## 3、JSAPI调用失败
后台是否申请、配置了相关JSAPI权限？
JSSDK引入是否正常？
点开日志查看日志是否被拒绝调用

## 4、日志功能？
点开菜单具备清理缓存和日志查看功能。
如需要自定义日志，请申请xpLogger权限。

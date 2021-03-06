# Ping++ 支付集成插件

## 安装

将 `pingpp` 目录放到 `/wp-content/plugins/` 下， 登录 wordpress 后台，启用Ping++（即pingxx）插件

<img src="https://raw.githubusercontent.com/PingPlusPlus/pingpp-wordpress/master/pingxx-wp-plugin-screenshot-1.png" width="500">

## 配置

登录 [Ping++管理平台](https://dashboard.pingxx.com/)， 将对应的 test/live keys 填入插件配置页面

<img src="https://raw.githubusercontent.com/PingPlusPlus/pingpp-wordpress/master/pingxx-wp-plugin-screenshot-2.png" width="300">

## 使用 

在文章中插入一句短代码(shortcode)：

```
[pingpp amount=100]
[pingpp amount=100 channel="alipay_pc_direct"]
[pingpp amount=100 selectable=true]
```

即可生成一个支付按钮，实现轻松支付：

<img src="https://raw.githubusercontent.com/PingPlusPlus/pingpp-wordpress/master/pingxx-wp-plugin-screenshot-3.png" width="350">

## 更新日志

**0.1.0** 发布日期: 2016年03月22日

* 支持支付宝即时到账, 微信公众号扫码, 银联网关, 企业付款四个PC端渠道的一键付款
* 支付用户自定义 shortcode 等



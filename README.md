# Reborn

## 功能介绍

Reborn 是一款 macOS 上的透明代理

* 对用户无感知，无需配置系统代理，自动接管所有应用程序（如浏览器和终端工具）流量
* 支持根据 IP、域名、GEOIP 规则进行分流，屏蔽特定网站
* DNS 解析对 CDN 友好

## 注意事项

配置规则仓库下有个模版文件，大概看看就能看懂了，配置文件放到 Profiles 目录下就好了。

由于是通过虚拟网卡实现的，所有如果要用 ping, traceroute 等功能，加 -S/-s 指定具体网卡吧。

最后说明一下，内置了 crash 上报会上传到 hockeyapp 和版本升级检测的，没有其他额外的网络功能了。


**希望碰到图标自动变灰（服务挂了）的情况能够反馈下如何出现的，比如访问某个网站，使用了某个工具**

## 导航

**Telegram**

https://t.me/joinchat/F8pm8hBZ7vroteDNeBJwfQ


**配置详解**

https://github.com/langyanduan/Reborn/blob/master/DETAIL.md


**基础配置模版**

https://github.com/langyanduan/Reborn/blob/master/template.yaml


**下载地址**

https://github.com/langyanduan/Reborn/releases


## 更新记录

* 0.4.21  
支持根据进程名分流，具体见[配置详解](https://github.com/langyanduan/Reborn/blob/master/DETAIL.md)
* 0.4.2  
增加 udp 转发支持，默认关闭，具体见[配置详解](https://github.com/langyanduan/Reborn/blob/master/DETAIL.md)
* 0.4.1  
dns 解析支持返回多组ip，自动将无法连接ip加入黑名单

## 后续计划

* simple-obfs  
* 流量统计  
* 配置方案
...

# Reborn

Reborn 是一款 macOS 上的透明代理

具体就不介绍了，类似 surge for mac。全局接管分流，对于一些命令行工具就不用自己在配置了，方便开发吧。当然还有一些功能需要完善，可以提出来，有空我加上去。

配置规则仓库下有个模版文件，大概看看就能看懂了，配置文件放到 Profiles 目录下就好了。配置读写真是花时间，各位大佬有没有推荐的配置格式。

由于是通过虚拟网卡实现的，所有如果要用 ping, traceroute 等功能，加 -S/-s 指定具体网卡吧。

最后说明一下，内置了 crash 上报会上传到 hockeyapp 和版本升级检测的，没有其他额外的网络功能了。


**Telegram**

https://t.me/joinchat/F8pm8hBZ7vroteDNeBJwfQ


**配置详解：**

[detail](./DETAIL.md)


**下载地址：**

https://github.com/langyanduan/Reborn/releases

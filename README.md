<p align="center">
<img width="768" src="https://raw.githubusercontent.com/QiuSimons/Others/master/YAOF.png" >
</p>
<p align="center">
<img src="https://forthebadge.com/images/badges/built-with-love.svg">
<p>
<p align="center">
<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/QiuSimons/YAOF/total?style=for-the-badge">
<img alt="GitHub" src="https://img.shields.io/github/license/QiuSimons/YAOF?style=for-the-badge">
<p>
<p align="center">
<img src="https://github.com/QiuSimons/YAOF/workflows/R2C-OpenWrt/badge.svg">
<img src="https://github.com/QiuSimons/YAOF/workflows/R2S-OpenWrt/badge.svg">
<img src="https://github.com/QiuSimons/YAOF/workflows/R4S-OpenWrt/badge.svg">
<img src="https://github.com/QiuSimons/YAOF/workflows/X86-OpenWrt/badge.svg">
<p>


<h1 align="center">请勿用于商业用途!!!</h1>



### 特性

- 基于原生 OpenWrt 21.02 编译，默认管理地址192.168.1.1
- 默认开启了 Software Offload
- 内置升级功能可用，物理 Reset 按键可用
- 预配置了部分插件<b>(注意，使用MosDNS同时作为广告过滤手段及dns分流措施。)</b>
- 可无脑 opkg kmod
- R2C/R2S核心频率1.6（交换了LAN WAN），R4S核心频率2.2/1.8（建议使用5v4a电源，死机大多数情况下，都是因为<b>你用的电源过于垃圾</b>，另外，你也可以选择使用<b>自带的app限制最大频率</b>，茄子🍆）
- O3 编译，CFLAG优化
- 插件包含：SSRP，PassWall，OpenClash，AdguardHome，微信推送，网易云解锁，SQM，DNSProxy，网络唤醒，DDNS，迅雷快鸟，UPNP，FullCone(防火墙中开启，默认开启)，流量分载，irq优化，京东签到，Zerotier，FRPC，FRPS，无线打印，流量监控，过滤军刀，R2S-OLED
- ss协议在armv8上实现了aes硬件加速（请<b>仅使用aead加密</b>的连接方式）
- 集成并默认启用了UKSM，BBRv2，LRNG，以及CacULE Scheduler
- 如有任何问题，请先尝试ssh进入后台，输入fuck后回车，等待机器重启后确认问题是否已经解决

### 说明

由于个人学习，需要将YAOF固件单独定制，请勿下载，请转至 QiuSimons/YAOF 原版固件下载

### 鸣谢

转至：QiuSimons/YAOF <b>原固件</b>，[下载](https://github.com/QiuSimons/R2S-R4S-OpenWrt/releases)

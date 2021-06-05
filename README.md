![GitHub Repo stars](https://img.shields.io/github/stars/insChow/Actions-OpenWrt?color=Blue&label=Stars&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/insChow/Actions-OpenWrt?color=Blue&label=Fork&style=for-the-badge)
![GitHub](https://img.shields.io/github/license/insChow/Actions-OpenWrt?color=Blue&style=for-the-badge)


-- 关于第三方全家桶软件仓库更新的说明 [![](https://img.shields.io/badge/-软件库更新说明-lightgrey.svg)](#软件库更新说明-)
-------------

- 每日两次自动拉取更新所有上游源码至上方软件仓库，所以此软件仓库永远都是最新的。
- 云编译脚本会调用此仓库软件编译OpenWrt固件，每日一次编译。

第二部分
======================
默认IP： 10.0.0.1  默认密码：password
-------------
Actions-OpenWrt — 多设备固件自动云编译 [![](https://img.shields.io/badge/-云编译固件-green.svg)](#云编译固件-)
======================

-- 支持的设备平台以及固件下载地址 [![](https://img.shields.io/badge/-设备及固件列表下载-lightgrey.svg)](#设备及固件列表下载-)
-------------

|    序号   |     平台+设备名称     |   编译状态+下载链接 |  
| :-----------------: | :-------------: |:-----------------: | 
| 1 |   [![](https://img.shields.io/badge/OpenWrt-%E6%9E%81%E8%B7%AF%E7%94%B1%20HC5962-yellowgreen.svg)](https://github.com/insChow/Actions-OpenWrt/actions?query=workflow%3A%22Build+HiWiFi+HC5962+OpenWrt%22)    | [![Build HiWiFi HC5962 OpenWrt](https://github.com/insChow/Actions-OpenWrt/workflows/Build%20HiWiFi%20HC5962%20OpenWrt/badge.svg)](https://github.com/insChow/Actions-OpenWrt/actions?query=workflow%3A%22Build+HiWiFi+HC5962+OpenWrt%22) |
| 2 |   [![](https://img.shields.io/badge/OpenWrt-x86%E5%A4%9A%E6%8B%A8%E6%9E%81%E7%AE%80%E7%89%88-lightgrey.svg)](https://github.com/insChow/Actions-OpenWrt/actions?query=workflow%3A%22x86%E5%A4%9A%E6%8B%A8%E6%9E%81%E7%AE%80+OpenWrt%22)    | [![x86full OpenWrt](https://github.com/insChow/Actions-OpenWrt/actions/workflows/x86full.yml/badge.svg)](https://github.com/insChow/Actions-OpenWrt/actions/workflows/x86full.yml) |
| 3 |   [![](https://img.shields.io/badge/OpenWrt-x86%E6%97%81%E8%B7%AF%E7%94%B1%E6%9E%81%E7%AE%80%E7%89%88-yellowgreen.svg)](https://github.com/insChow/Actions-OpenWrt/actions?query=workflow%3A%22x86%E6%97%81%E8%B7%AF%E7%94%B1%E6%9E%81%E7%AE%80+OpenWrt%22)    | [![x86simple OpenWrt](https://github.com/insChow/Actions-OpenWrt/actions/workflows/x86simple.yml/badge.svg)](https://github.com/insChow/Actions-OpenWrt/actions/workflows/x86simple.yml) |
| 4 |   [![](https://img.shields.io/badge/OpenWrt-XIAOMI--AX3600-yellowgreen)](https://github.com/insChow/Actions-OpenWrt/actions/workflows/mi_ax3600.yml)    | [![Build Xiaomi AX3600 OpenWrt](https://github.com/insChow/Actions-OpenWrt/actions/workflows/mi_ax3600.yml/badge.svg)](https://github.com/insChow/Actions-OpenWrt/actions/workflows/mi_ax3600.yml) |


-- 百度云盘下载 （测试）
-------------

链接: https://pan.baidu.com/s/1e89hoFkzR3kBsf7oHlTdKw 提取码: ctw4 

-- 微软 OneDrive 下载地址 （测试）
-------------

https://losaiiis-my.sharepoint.com/:f:/g/personal/hzj_ouuo_ml/Eu2LuOIwJpBMrNQd7tst1hsBZj8SujgtZn_QjaXIT31y7Q?e=jDXq0x

-- 关于自动编译固件的说明 [![](https://img.shields.io/badge/-自动编译说明-lightgrey.svg)](#自动编译说明-)
-------------

- 不建议Fork，按需下载即可。
- 自动编译，自动拉取最新版本插件。
- x86多拨极简版为自用固件仅包含 （pw,S,上网时间控制，upnp,ddns,去广告，多拨，负载均衡，流量监控，主题只加入了默认主题以及自己比较喜欢的edge主题）
- x86旁路由极简版为自用，建议配合爱快使用，仅包含（pw，S，去广告，主题只加入了默认主题以及自己比较喜欢的edge主题）
- 请注意脚本不编译x86-32位版本。
- 经过几天的观察发现，部分固件编译结果显示失败，但是实际上是成功的，具体情况请点击进入下载链接查看。

======================

免责声明 [![](https://img.shields.io/badge/-免责声明-green.svg)](#免责声明-)
======================
***- 由于本人小白，有可能使用到了大神的代码，没有放进鸣谢名单里的，请联系添加，再次感谢各位大神的贡献***

***- 请务必遵从‘不涉及政治，不涉及宗教，不涉及黄赌毒’的三不原则***



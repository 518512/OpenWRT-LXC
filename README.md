# 简介
### 小白一枚，根据各路大神教程，编译自用PVE CT / LXC 模板，Arm&x86_x64版 ROOTFS。
**OpenWRT v22 Fork [xYx-c/build-openwrt](https://github.com/xYx-c/build-openwrt)，使用OpenWRT官方源码编译**
  
**OpenWRT v23 / v24 为缝合产物，搞了两天没搞定，因为同样的配置文件v23.05会编译错误。**

  |名称|说明|用户|密码|备选|
  |:----|:----|:----|:----|:----|
  | IP| 10.5.2.1| root| password| 192.168.1.1|
## 固件下载 [![](https://img.shields.io/badge/-编译状态及下载链接-FFFFFF.svg)](#固件下载-)
点击下表中 [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?style=flat&logo=hack-the-box)](https://github.com/518512/My-ROOTFS/releases) 即可跳转到该设备固件下载页面
| 平台+设备名称 | 固件编译状态 | 下载 |
| :------------- | :------------- | :------------- |
| [![](https://img.shields.io/badge/OpenWrt-Arm_x64-32C955.svg?logo=openwrt)](#) |[![](https://github.com/518512/OpenWRT-LXC/actions/workflows/OpenWrt.Matrix.yaml/badge.svg)](#) [![](https://github.com/518512/OpenWRT-LXC/actions/workflows/Arm64.v23%20.yaml/badge.svg)](#) | [![](https://img.shields.io/badge/下载--blueviolet.svg?logo=hack-the-box)](https://github.com/518512/OpenWRT-LXC/releases) |

- 为什么要有三个版本的OpenWRT？
- 仅限于就**自身**使用需求来看，ImmortalWrt更适合作为主路由，LEDE更适合旁路网关，或者无IPV6 RA设置需求的。
- 另外的OpenWRT官方版如**xYx-c所说**很清爽。

## OpenWRT Official - ARM
> [!TIP]
> **插件：基础功能、IPV6、OC、AdguardHome、MosDNS、Agron主题**

**仅适用于ARMv8的CPU，且只提供LXC所需的rootfs.**

**用于x86_x64的的请到原作者处[xYx-c/build-openwrt/releases](https://github.com/xYx-c/build-openwrt/releases)下载.**

> **说明**:构建本openwrt目的是自己使用,没有太多功能比较清爽,仅仅适用我个人使用 - **附议原作者xYx-c，的确清爽**.

## 感谢

**[xYx-c/build-openwrt](https://github.com/xYx-c/build-openwrt) 、[Zane-E/ROOTFS](https://github.com/Zane-E/ROOTFS) 、[217heidai/OpenWrt-Builder](https://github.com/217heidai/OpenWrt-Builder) 、[db-one/OpenWrt-AutoBuild](https://github.com/db-one/OpenWrt-AutoBuild) 、[shidahuilang/openwrt](https://github.com/shidahuilang/openwrt) 、[haiibo/OpenWrt](https://github.com/haiibo/OpenWrt) 、[ophub/amlogic-s9xxx-openwrt](https://github.com/ophub/amlogic-s9xxx-openwrt) 等等无私的大神分享及教程**

## 鸣谢

- 感谢[openwrt源码](https://github.com/openwrt/openwrt) 、[LEDE源码](https://github.com/coolsnowwolf/lede) 、[ImmortalWrt源码](https://github.com/immortalwrt/immortalwrt)
- 感谢[@P3TERX](https://github.com/P3TERX),[P3TERX大佬的云编译](https://github.com/P3TERX/Actions-OpenWrt)



## Credits
- [@P3TERX](https://github.com/P3TERX)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [Zane-E/ROOTFS](https://github.com/Zane-E/ROOTFS)
- [haiibo/OpenWrt](https://github.com/haiibo/OpenWrt)
- [xYx-c/build-openwrt](https://github.com/xYx-c/build-openwrt)
## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)


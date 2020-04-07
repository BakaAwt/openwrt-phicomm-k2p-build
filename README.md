# openwrt-phicomm-k2p-build
OpenWrt/LEDE build config and prebuilt images for Phicomm K2P wireless router.
## 斐讯K2P的OpenWrt/LEDE编译配置文件及预编译固件（自用&备份用）

如果你要用本仓库的配置文件编译，建议先去[lean的仓库](https://github.com/coolsnowwolf/lede/)看一下相关说明，本配置文件为lean的OpenWrt源码生成，本意是个人使用以及备份。

~~出于稳定性考虑暂时不使用mt76开源驱动，请使用此处的[闭源驱动](https://github.com/MeIsReallyBa/k2p-openwrt-mt7615_5.0.2.0)。~~
目前使用Lean已在源码中集成的驱动(package/lean/mt)，如出现问题请及时向上游反馈。
如需已编译好的固件请在[releases](https://github.com/KevinMX/openwrt-phicomm-k2p-build/releases/)中自取。
请自行斟酌使用，如出现任何问题后果自负。

自用插件列表：

```luci-app-accesscontrol
luci-app-arpbind
luci-app-autoreboot
luci-app-ddns (包含额外的ddns脚本)
luci-app-firewall
luci-app-flowoffload
luci-app-ramfree
luci-app-sqm
luci-app-ssr-plus (v2ray+trojan+ShadowsocksR&服务端)
luci-app-v2ray-server
luci-app-upnp
luci-app-vlmcsd (KMS服务器)
luci-app-wifischedule
luci-app-wol (网络唤醒)
luci-theme-argon
ipv6helper
集成无线驱动
```

## 本脚本来源于lgs2007m二次修改
- https://github.com/lgs2007m/Actions-OpenWrt
- -------
- 全工作流采用了4g25dbm,5g24dbm-eeprom如无需要请在编译时取消打勾‘Use nx30pro eeprom and fixed WiFi MAC address’，除25db.yml使用的双频25dbm
- 加入了h3c-nx30pro-5g25db-eeprom，如有需要编译时请选择25db.yml（默认使用hanwckf源码）
- 顾名思义hanwckf.yml使用的是hanwckf源码，padawanonly使用的237源码
- 插件尽量不要加的太多，可能编译超时导致失败，我的建议是加入istore商店和一些其他插件，刷机以后去软件包/商店下载安装/使用.run（尽量不要编译网易云解灰，大概率超时）
- part1已经添加了自用的几个插件地址，按需增减
- -------
## 感谢p大的云编译项目
- https://p3terx.com/archives/build-openwrt-with-github-actions.html
## padavanonly源码
- https://github.com/padavanonly/immortalwrt-mt798x
## hanwckf源码
- https://github.com/hanwckf/immortalwrt-mt798x
- -------
## 其他资源汇总（瞎整）
- https://www.yuque.com/yuqueyonghullvctc/lddvzm/cwqxrg9zh55k4ri5

# 大气层整合包
=====
本整合包根据 [NH Switch Guide](https://nh-server.github.io/switch-guide/user_guide/emummc/sd_preparation/)整理，并包含了以下插件：
- 最新的发行版 [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/releases) (Download the atmosphere-(version)-master-(version)+hbl-(version)+hbmenu-(version).zip).
- 最新的发行版 [Hekate](https://github.com/CTCaer/Hekate/releases) (Download the hekate_ctcaer_(version).zip).
- Hekate 配置文件：[hekate_ipl.ini](https://nh-server.github.io/switch-guide/files/sys/hekate_ipl.ini).
- 图标压缩文件：[bootlogos.zip](https://nh-server.github.io/switch-guide/files/bootlogos.zip).
- 屏蔽网站列表：[emummc.txt](https://nh-server.github.io/switch-guide/files/emummc.txt).

- 最新的发行版 [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM/releases) (Download the Lockpick_RCM.bin release of Lockpick).
- 最新的发行版 [JKSV](https://github.com/J-D-K/JKSV/releases) (Download the JKSV.nro release of JKSV).
- 最新的发行版 [FTPD](https://github.com/mtheall/ftpd/releases) (Download the ftpd.nro release of FTPD).
- 最新的发行版 [DBI](https://github.com/rashevskyv/dbi/releases) (Download the DBI.nro release of DBI).
- 最新的发行版[hbappstore](https://github.com/fortheusers/hb-appstore/releases)(Download the appstore.nro release of hbappstore)
- 最新的发行版 [Sys-botbase](https://github.com/olliz0r/sys-botbase/releases).
- 最新的发行版 [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm/releases).
- 最新的发行版 [sigmapatches](https://sigmapatches.coomer.party).


## 其他可能需要的插件：
- [Tinfoil](https://tinfoil.io/Download) 
- [EdiZon](https://github.com/WerWolv/EdiZon) 
- [Emuiibo](https://github.com/XorTroll/emuiibo) 
- [NX-Shell](https://github.com/joel16/NX-Shell)
- [sys-clk](https://github.com/retronx-team/sys-clk)
- [sys-con](https://github.com/cathery/sys-con)
- [sys-ftpd-light](https://github.com/cathery/sys-ftpd-light)
- [Tesla-Menu](https://github.com/WerWolv/Tesla-Menu)


## 如何使用
首先，您需要有一台破解版NS，可以根据[教程](http://switch.homebrew.guide)进行破解。</br>
下载最新版压缩包，并放到SC卡中。</br>
在 RCM 模式下将 Hekate 有效负载发送到您的 Switch 并启动 CFW。

## Note: 
本整合包默认禁止联网。为了连接到互联网，您需要删除[default.txt](https://github.com/FireJoker/AMS_SD_Package/tree/main/atmosphere/hosts)文件。
**不要** 在虚拟系统连接网络，不然后果自负。</br>
在系统设置中，如果在当前系统后有后缀**E**，则表示当前为虚拟系统；</br>
例如：当前系统：16.0.0|AMS 1.5.0|E</br>
如果在当前系统后有后缀**S**，则表示当前为真实系统；</br>
例如：当前系统：16.0.0|AMS 1.5.0|S</br>
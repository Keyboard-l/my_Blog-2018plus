# 软路由与NAS 软件平台搭建

---

## 后记

最开始真正接触软路由，是大二的时候，在科协。尹大人在一台老旧的主机上跑个 OpenWrt ，那个机子有四个网卡（两LAN两WAN）。两个WAN一个走翼讯出，一个走校园网出，两个LAN接两个无线AP。效果就是睿思等校内流量走校园网，其他流量走翼讯，两个WiFi中一个是普通的，一个是带透明代理（可以访问国际互联网那种）的。初见很是惊奇，未曾想过竟能如此优雅地配置网络。

再后来，尹大人把它配置得更复杂了，把 OpenWrt 装进虚拟机里，四个网卡桥接进虚拟机里。

那时的我，刚好大一结束的暑假刚看完一本计算机网络的入门教材（也是尹大人推荐的，《计算机网络 自顶向下方法》），对计算机网络充满兴趣。而 OpenWrt 在那时的我看来是一个完美的学习平台，可以检验我对很多计算机网络基础知识的认识。所以从那时起我就慢慢玩起了 OpenWrt 
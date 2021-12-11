---
title: 成功修复砖头 Dell TrueMobile 2300
author: kxn
type: post
date: -001-11-30T00:00:00+00:00
url: /index.php/archives/32
categories:
  - Uncategorized

---
**成功修复砖头路由器 Dell TrueMobile 2300**

前天晚上我 blog 上面记载了把我的 Dell TrueMobile 2300 给[刷成砖头][1]了的事情，不得已又买了一个。今天中午回来无事，在网上找了一些资料，自己动手制作了一根简易 JTAG 线，将变砖的路由器成功修复。

我参考的文章主要是以下几个

[http://www.right.com.cn/forum/viewthread.php?tid=6016&highlight=jtag][2]  
[http://www.right.com.cn/forum/viewthread.php?tid=5872&highlight=jtag][3]  
[http://wiki.openwrt.org/OpenWrtDocs/Customizing/Hardware/JTAG_Cable][4] 

此外还使用了下面这个文章里面 qwea 网友针对 Dell TrueMobile 2300 修改的 jtag debrick 工具。

[http://www.right.com.cn/forum/viewthread.php?tid=12838][5] 

因为这个 blog 不是用来贴技术相关内容的，详细过程就不写了，放几个图出来。

JTAG 刷机中

<div style="padding:1em;text-align:left">
  <img style="width:640px;height:480px" src="http://docs.google.com/File?id=ddnd9fqr_45c4cswqhk" />
</div>

土造 JTAG 线

<div style="padding:1em 0pt;text-align:left">
  <img style="width:640px;height:480px" src="http://docs.google.com/File?id=ddnd9fqr_46dbkm37gr" />
</div>

然后有 JTAG 在手，心里也比较有底，于是平时不敢做的危险动作比如在 Dell 这个上面刷 openwrt 也做了，很好很强大！

PS: 这下我就有两个一样的 Dell TrueMobile 2300 路由器了，有点想把新买的那个卖了，谁最近要买无线路由器么？原价 170， 我降价 5 块卖了好了。 RMB 165 不包运费不送货。预置 dd-wrt 已经升级到最新的 RC 6.2，能满足一般用户需要。

Update: 路由器已经卖掉了.

 [1]: http://kxn.spaces.live.com/blog/cns!626140570A4EA541!1083.entry "刷成砖头"
 [2]: http://www.right.com.cn/forum/viewthread.php?tid=6016&highlight=jtag "http://www.right.com.cn/forum/viewthread.php?tid=6016&highlight=jtag"
 [3]: http://www.right.com.cn/forum/viewthread.php?tid=5872&highlight=jtag "http://www.right.com.cn/forum/viewthread.php?tid=5872&highlight=jtag"
 [4]: http://wiki.openwrt.org/OpenWrtDocs/Customizing/Hardware/JTAG_Cable "http://wiki.openwrt.org/OpenWrtDocs/Customizing/Hardware/JTAG_Cable"
 [5]: http://www.right.com.cn/forum/viewthread.php?tid=12838 "http://www.right.com.cn/forum/viewthread.php?tid=12838"
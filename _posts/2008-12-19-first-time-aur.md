---
title: "第一次管理AUR里的包"
date: 2008-12-19 17:17
categories:
- Linux
- 生活
tags:
- arch
- aur
- svn
---

ArchLinux真是神奇，自从安装后连连给我惊喜，在这次的惊喜过后，我终于忍不住发一篇文章。

感觉在用Ubuntu的时候根本不是在用Linux，虽然有很多新鲜的东西，但都是别人定好的，说白了安个软件跟Windows没有什么区别，只不过一个是从下载站下载，一个是从源里下载而已。

不过在Archlinux里，这完全不一样了。

起因是我想安装kiba-dock，这本来是好久以前就瞻仰的东西，不过先前网卡不行，只能望而生叹。而且Ubuntu
64bit根本安不上，源码编译都不行。

想一想，ArchLinux里，其他人应该有解决办法吧，去AUR里看看，果然支持x86\_64，那基本上就意味着有人安装成功了。于是乎赶紧yaourt -S，然后发现，它所依赖的包akamaru-svn不支持64位，汗～

本来这种事改个arch就好了，可是改了之后又有问题，忙了半天发现是源码包需要改一下……

我就想，这谁管的包啊，这么不负责，一看，没人……再汗～

于是我很疑惑，上面有个按钮是干什么的，点了，发现我成了那个包的主人了，瀑布汗……

以前根本没有经验，只好照着别的包抄了一下PKGBUILD的写法，总算把那个BUG修复了，传上去，嘿，我这已经安装上的包也更新了……爽啊～

虽然这是个可能永远不能更新的软件（SVN才到3），但是管理还是很有成就感，以后要一定要学学SVN～

最后，发现安了这个包根本没有起到应有的作用，可爱的物理特效根本没有开，也就是说，这是个名存实亡，根本没用的包……成吉思汗……

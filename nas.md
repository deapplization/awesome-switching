# awesome-switching

Switching from the *pple ecosystem to Windows / Linux / Android or BSD

从 *果生态系统 迁移到 Windows 或者 Linux / Android / BSD

## NAS和私有云, Homelab
如果能妥善做好备份的话，数据掌握在自己手里总比放在别人手里好，对吧？如果你确实在意数据所有权和隐私，那么NAS/私有云是很好的选择。
大多数常见服务都已经有了开源替代品，也都提供了比较方便的Docker部署方式，几乎不需要太多背景知识即可一件安装。

部署这些服务，可以使用成熟而商品化程度高的NAS，也可以用一台闲置PC安装Linux/BSD作为私有云，或者更复杂一些变成Homelab玩家。

在开始这些之前，请先默念以下口诀10遍 ;)

**“备份不做，十恶不赦”**

---------

### 基本概念

### 硬件选择
不论是自己DIY还是购买成品NAS，总体原则：1、功耗较低，静音。2、千兆的有线网口。 3、至少有两个硬盘接口。

### 软件和服务
- [Nextcloud](https://nextcloud.com/) - 全功能私有云，文件存储和共享，日历，联系人，邮件等。 ([Demo](https://demo.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- [TrueNAS Core](https://www.truenas.com) - 原名 FreeNAS，存储服务器操作系统，基于 FreeBSD 和 OpenZFS。适合想自己搭键 NAS，但是又懒得折腾 ZFS/RAID 的人。([Source Code](https://github.com/truenas/)) `BSD-2` 
- [TrueNAS SCALE] 同样为TrueNas出品，但系统已经切换为基于Debian的Linux。2021年初刚刚推出，优势是具有ZFS的同时，硬件驱动也支持的较好。
- [XigmaNas](https://xigmanas.com/) - 早年从FreeNAS分支出来的版本，2018年以前叫做Nas4Free现已改名为XigmaNas。界面比较老旧遵循以前FreeNAS的结构，同样支持ZFS。系统虽然比较老，但硬件需求比较低，由于ZFSPool的影响TrueNAS需要8G内存，但XigmaNas4G内存就可以顺利运行了。([Source Code])(https://sourceforge.net/p/xigmanas/code/HEAD/tree/)`	BSD license`

## Other resources
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)

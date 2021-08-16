# awesome-switching

Switching from the *pple ecosystem to Windows / Linux / Android or BSD

从 *果生态系统 迁移到 Windows 或者 Linux / Android / BSD

## Tips

0. 安全和隐私须知：使用任何系统（包括被宣称更隐私和安全的）都无法带来真正的隐私和安全。只有一个办法是有用的： **少用电子设备，保持更多离线时间，多读纸书**

--------------------

## Table of contents

--------------------

## Alternative To...

* [Keychain|密码管理](#password-managers)
* [Airdrop|自组网服务](#ad-hoc-service)
* [Safari|浏览器](#browser)
* [iCloud Photos|相册](#photos)
* [Touchpad|触摸板](#touchpad)
* [iCloud|云服务](nas.md)

## Professional Users
 
 - 专业用户装机指南[pugetsystems](https://www.pugetsystems.com/all_articles.php) 是美国专业装机商，客户遍布各专业领域。他们提供了按照不同专业软件分类的配置指南和评测。包括图形图像/视频/建筑/工业/科学/游戏/直播等各领域

## Caution

 * [Windows防踩坑注意事项](windows-notes.md)
 * [Android防踩坑注意事项](android-notes.md)

## Computer

### All In One

## Computer Peripheral

### Touchpad
- 触摸板主要是 Synaptics 和 Elan 两家的产品，可以通过安装对应的精确式触控提升体验
  - [觉得 Windows 笔记本的触控板不好用？你可以试试装个新驱动](https://zhuanlan.zhihu.com/p/38249316)
  - [Windows 10触控板竟然如此好用](https://www.bilibili.com/read/cv5845861)
  - [Linux Touchegg](https://wiki.archlinux.org/title/touchegg) Linux多点触摸手势支持，但不支持Wayland ([Source Code](https://github.com/JoseExposito/touchegg))
  - [Linux Touchpad Synaptics](https://wiki.archlinux.org/title/Touchpad_Synaptics)
  - [Linux Libinput](https://wiki.archlinux.org/title/Libinput)

## Mobile

### Hardware
- [PinePhone](https://www.pine64.org/pinephone/)
- [Librem 5](https://shop.puri.sm/shop/librem-5/)

以上两家公司也提供笔记本电脑。

### Operating system
- [Lineage OS](https://lineageos.org/) A free and open-source operating system for various devices, based on the Android mobile platform. 支持多种Android设备。
- [Postmarket OS](https://postmarketos.org/) postmarketOS extends Alpine Linux to run on smartphones and other mobile devices.
- [Mobian](https://mobian-project.org/) Debian for mobile.
- [Calyxos](https://calyxos.org/)

## Software

<!-- BEGIN SOFTWARE LIST -->

### Password Managers

- [Bitwarden](https://bitwarden.com/) 开源的密码管理器，支持网页，浏览器扩展，手机。可以使用官方服务或自建服务。 ([Source Code](https://github.com/bitwarden/server)) `AGPL-3.0`
- [keepass](https://keepass.info/) 开源的密码管理器，可单机离线使用，也有各种第三方工具支持各平台，定制性很强，但略微复杂。[awesome-keepass](https://github.com/lgg/awesome-keepass)
- [Enpass](https://www.enpass.io/) 全平台，甚至有WIN10 UWP版本，桌面版免费，移动端买断制收费。支持通过 Drobox，Google Drive 等服务同步，官方宣称不存储任何数据。
- [Vault](https://www.vaultproject.io) HashiCorp 的企业级安全平台，可以架在私有云上使用，自带 web 客户端，在合适的配置下可以作为密码管理工具使用。优点：企业级安全特性（比如基于 [Shamir 秘密共享](https://en.wikipedia.org/wiki/Shamir's_Secret_Sharing)的[多人规则](https://en.wikipedia.org/wiki/Two-man_rule)），灵活（key-value 引擎可以存储任何键值，不仅仅是密码），可以作为整个家庭的安全基础架构（自带 PKI 和 TOTP 引擎）；缺点：需要手动配置用户和权限，需要自己写 native 客户端。

### Ad-hoc Service

- [Google Nearby](https://en.wikipedia.org/wiki/Nearby_Share) Android系统内置。介绍: 来自 [Google 的「隔空投送」](https://sspai.com/post/61450)
- [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole) wormhole是点对点安全文件/消息直传工具，在有网络的情况下可以代替airdrop。
  - [wormhole-william](https://github.com/psanford/wormhole-william) wormhole的go语言实现，安装使用更简单，此处是命令行版本，和官方python版本兼容。
  - [wormhole-gui](https://github.com/Jacalz/wormhole-gui) wormhole图形界面版，可在Windows/Linux/Mac使用。
  - [mobile-wormhole](https://play.google.com/store/apps/details?id=com.pavelsof.wormhole) wormhole Android版本，和以上各版本兼容。[Fdroid安装](https://f-droid.org/packages/com.pavelsof.wormhole/) ([Source Code](https://github.com/pavelsof/mobile-wormhole))

### Browser

- [Chrome](https://www.google.com/chrome)  Google Chrome 是基于目前最流行的内核Chromium开发的浏览器产品。有桌面和手机版，全平台。
- [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser) 基于 Chromuim 内核的安卓浏览器，比起 Chrome 增加了安装扩展的功能。
- [Edge](https://microsoftedgewelcome.microsoft.com) Edge 是微软在 Chromium 基础上开发的浏览器。支持DRM，可以看各种流媒体服务的高清版本。全平台。
- [Firefox](https://www.mozilla.org/en-US/firefox/new/) Firefox 是开源社区更为喜爱的浏览器，有更激进的安全策略。全平台。
- [Firefox Focus for Android](https://play.google.com/store/apps/details?id=org.mozilla.focus) Firefox 为移动平台推出的轻量级，注重隐私浏览器。特点是每次退出会清空历史记录和cookies，本地不留痕迹。
- [Firefox Nightly for Android](https://play.google.com/store/apps/details?id=org.mozilla.fenix) Firefox 为移动平台的测试版。比起普通版本多加了安装插件功能，可以按需安装插件。

### Photos

- [iCloud相册] 如果你有使用iCloud来备份照片，并且开启了“优化iPhone存储”的选项，那就必须要先去【设置】-【账户】-【iCloud】-【照片】中选择【下载并保留原件】，保证手机空间大于iCloud的照片空间，将所有的图片原件下载到手机本地。完成操作之后拷贝到计算机或者NAS上即可。
- [icloud_photos_downloader](https://github.com/icloud-photos-downloader/icloud_photos_downloader) 从 iCloud 相册迁移出海量照片，可以直接在 NAS 里跑，下载完成即完成迁移。
- [photoprism](https://photoprism.app/features) 自建私有云照片服务，带有基本AI照片识别模型。可以通过docker部署于Linux/群晖/树莓派。FreeBSD/FreeNAS用户可以使用[非官方Port](https://github.com/huo-ju/photoprism-freebsd-port) ([Demo](https://demo.photoprism.org)) ([Source Code](https://github.com/photoprism/photoprism))
- [photosync](https://www.photosync-app.com/) (Android) 基于 ssid 或者 schedule 自动备份手机照片到电脑，NAS或者第三方云服务。Android 版可以用 $3.99 买断。

## Other related repos
- [awesome-privacy](https://github.com/pluja/awesome-privacy)

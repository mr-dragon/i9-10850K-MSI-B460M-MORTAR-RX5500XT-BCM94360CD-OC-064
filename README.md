# i9-10850K-MSI-B460M-MORTAR-RX5500XT-BCM94360CD-OC-064

---
Hackintosh 黑苹果 EFI 配置：
<br/>

CPU：i9-10850K 主板：微星 B460M MORTAR 显卡：RX 5500XT 无线网卡：BCM94360CD（FV-HB1200(1200M黑苹果免驱版)）

---
CPU: i9-10850K，Mainboard：MSI - B460M - MORTAR，Video: RX5500XT，Wireless Network Card: BCM94360CD;

<span style='color:red;font-size:24px;'>
注意：本人是个对硬件一无所知的小白，初次组装电脑，以下所有的文字都是个人操作经验做下记录。
文中出现的商品链接皆为个人搜索看到的，仅供参考无任何广告嫌疑！
任何地方出任何问题，概不负责！如不同意请勿观看，即刻关闭</span>

---
黑果折腾记录：（2020-12 ～ 2021-01）

前言：

本人16年接触过黑苹果，一直没有设备支持可以安装的. 现在家里需要一台电脑，用惯了 `MacBookPro`，不想再用 `Windows` 系统了. 就想组装个台式机，安装个高配置黑果用，预算 1.2w.

## 一、需求

- 软件开发(开发工具、docker……)
- 显卡可以支持绝大部分软件，虽然不玩游戏;但是需要随便改改图片，或者看电影啥的也要基本支持效果好一点的
- CPU 10代，线程多一点，性价比高点的，不用 AMD，防止Mac下一些软件出问题(AMD5800价格是真的香)

## 二、购置硬件、机箱

请记住：<span style='color:red;font-size:26px;'>看尺寸！看尺寸！看尺寸！</span>

尤其是：主板，电源，显卡，风扇！

我是这样选购的：

1. 先看看机箱大小（吐血预警：别想高性能但机箱小，可以带着走的，这是不该有的傻屌想法）
2. 买了机箱根据机箱支持的东西&尺寸，去买所有硬件！（如果买了ATX机箱，就基本随便了，可以不看尺寸，买的时候跟上商家确认下能不能用就行）

### 尺寸表

- 机箱：机身：320*200*270mm
  - 建议高性能直接买ATX机箱，至少MATX机箱，不要想买 ITX机箱，不可能的了，别浪费时间
- 主板：24.4cm x 24.4cm
  - 1,ATX:305mmX244mmm
  - 2,Micro-ATX规格:243mm*214mm
  - 3,mini-atx:170mmx170mm
- 显卡（蓝宝石5500xt）：234 x 117 x 40 mm
- 电源：标准ATX电源尺寸（长城这款商品详情写的：150*140*86 mm ）

### 硬件列表

#### 机箱

- [先马巴德机箱台式机电脑双面钢化玻璃透明全透M-ATX开放式主机箱](https://detail.tmall.com/item.htm?id=631018872337&spm=a1z09.2.0.0.96dd2e8d1D8FTO&_u=i27qkbsfee48)
  - 372(L)*190(W)*365(H)mm
  - 仓位扩展:1*3.5英寸位、2*2.5英寸位 4PC位
  - 前置接口:1*USB3.0接口、2*USB2.0接口
  - 高清音频接口(耳机接口与麦克风接口)
  - 内部散热:前板2*12cm风扇位，后板1*8cm风扇位

#### 电源

- [长城猎金V6电源额定600W金牌电源台式机电脑电源静音主机电源模组,金牌认证600W 单路12V 全电压,499](https://detail.tmall.com/item.htm?id=609231267839&spm=a1z09.2.0.0.96dd2e8d1D8FTO&_u=i27qkbsff79a)
  - SFX电源，指的是三围尺寸大概为125mm × 100mm × 63.5mm身材的小尺寸电源，也有部分大功率产品使用125mm x 130mm x 63.5mm的尺寸，比如SilverStone SST-SX800），被称为SFX-L电源。
  - ATX电源：
    - ATX电源作用是把交流220V的电源转换为计算机内部使用的直流5V，12V，24V的电源。
    - ATX电源主要有两个版本，一种是ATX1.01版，另一种是ATX2.01版。2.01版与1.01版的ATX电源除散热风扇的位置不一样外，它们的激活电流也不同。1.01版只有100mA，2.01版则有500mA～720mA。这意味着2.01版的ATX电源不会像1.01版那样"过敏"，经常会受外界电压波动的影响而自行启动计算机。
    - ATX电源的标准尺寸主要是150*140*86mm（W*D*H），而150*86是关乎到ATX的机箱的尺寸，它主要是电源和机箱后面靠接部分的尺寸大小，而140mm就是机箱内部电源的长度，所以一般的机箱尺寸都是适合150*140*86的ATX电源。如果你购买的ATX电源超过这个尺寸，就要对你购买的机箱尺寸进行调整了，不然会造成放不下的情况。一般情况H和W是不变的，D为高度，就会根据你个人购买电脑情况而有改变。

#### CPU

- [CPU：英特尔（Intel）i9-10850K 10核20线程 盒装CPU处理器，3099](https://item.jd.com/100008072593.html)
- [*CPU：Intel/英特尔i9 10850K散片CPU i910850K 10核心20线程，2799](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.96dd2e8d1D8FTO&id=633125464492&_u=i27qkbsf90c9)

#### 主板

- [*主板：MSI/微星MAG B460M MORTAR 迫击炮电脑台式机电竞游戏电竞办公MATX主板1200针，699](https://item.jd.com/100007074505.html)
- [主板：华硕（ASUS）TUF GAMING B460M-PLUS重炮手主板 支持 CPU 10500/10400/10400F（Intel B460/LGA, 659.00](https://item.jd.com/100013209266.html)
  - 主板只有10~20W，如没有独显建议的电源是300W，有独显根据独显购买电源
  - 尺寸：24.4cm x 24.4cm
  - 4 x ddr4内存插槽，最大内存容量，128GB
  - 1 x PS/2键鼠接口，6 x USB接口，3 x 3.5mm接口，1 x RJ45接口，1 x HDMI接口

#### 内存

- [内存：金士顿(Kingston) DDR4 2666 32GB(16G×2)套装 台式机内存条 骇客神条 Fury雷电系列，759](https://item.jd.com/100012856316.html)

#### 显卡(GPU)

- [显卡：蓝宝石（Sapphire）RX 5500 XT 8G D6 白金版OC 1737-1845MHz/14Gbps 128bit GDDR6,1699](https://item.jd.com/100010515956.html)
  - A卡(AMD)：`rx560、570、590、5500xt、5600xt、5700xt、Vega56、Vega64、VII显卡`
  - 最新 `rx590 GME`和`rx580 2048sp`驱动不了，景讯这个牌子不能买，黑屏！可以安装最新！！！！

#### 网卡

- [*Fenvi FV-T919适用黑苹果MAC免驱 BCM94360CD 芯片 台式机内置pcie无线网卡 千兆1750M电脑蓝牙4.0 WiFi接收器,219](https://detail.tmall.com/item.htm?id=569974443985&spm=a1z09.2.0.0.96dd2e8d1D8FTO&_u=i27qkbsf1a0c)

#### 固态硬盘

- [*三星（SAMSUNG）500GB SSD固态硬盘 M.2接口(NVMe协议) 970 EVO，599](https://item.jd.com/7234518.html)
- [西部数据（Western Digital）250GB SSD固态硬盘 M.2接口（NVMe协议）WD Blue SN550，309](https://item.jd.com/100010653792.html)

#### 机械硬盘

- [西部数据(WD)红盘Pro 4TB 网络储存硬盘(NAS硬盘/SATA6Gb/s/256M缓存/WD4003FFBX,1129)](https://item.jd.com/8703820.html)
- [新买的移动硬盘该格式化为 NTFS 还是 exFAT？](https://www.zhihu.com/question/20448164)
- [U盘和硬盘如何选择格式，FAT32、exFAT、NTFS、HFS+和APFS有何区别？](http://www.360doc.com/content/19/0120/16/11698101_810192393.shtml)
- [mac电脑用移动硬盘什么格式最稳？](https://www.zhihu.com/question/387279588)
- [mac格式化移动硬盘什么格式最好](https://zhidao.baidu.com/question/1707033508324793100.html)
- [HDD格成HFS+好还是APFS好？](https://www.zhihu.com/question/316795817/answer/631892767)
  - APFS还是专门为SSD优化设计的，对机械盘没啥提升

- MacBook支持以下的格式：
  - 老款的Fat32格式，这个格式的好处是在MAC和Windows电脑都能使用，但缺点是FAT32分区，只能支持单个4GB以下的文件，不是很方便；
  - HFS格式，这个是Mac专用的分区格式，与MAC系统最匹配，但是Windows的电脑，就无法识别使用了；
  - 最新的exFAT格式，OS X 10.6.3 以上直接就支持了exFAT格式，而Windows也是从windows xp sp2就支持了，推荐使用这个格式给移动硬盘使用。

如果你只是备份自己Mac的数据，那么HFS+足够了。
（PS：新的格式是 `APFS` ，不过是给固态硬盘用的，`Windows` 识别不了）

`eXFAT` 也是微软的，macOS 10.6.5（2010年）苹果自己系统自带支持，不需要任何第三方软件。
exFAT是对闪存更友好的非日志型文件系统（区别于NTFS/HFS+），**不太建议用于机械硬盘的大量数据存储**。

---

硬盘购买的时候是不需要分格式卖，你想用什么格式就自己用相关的工具去格式化。
`macOS`自带的磁盘工具就可以，你可以根据自己的需要去选择
`NTFS` 在mac上确实没有苹果官方的读写支持，第三方的应用可以解决一些问题，但你需要大量在macOS下读写数据的情况下依然不太推荐用NTFS。 即使大部分情况下不会出问题

疑惑：移动硬盘不要用exfat，这是给U盘用的??? macbook可以分一个区用mac os格式给时间机器备份电脑

#### 散热

- [水冷：海盗船H60/H80iV2水冷120mm CPU水冷散热器电脑台式机一体式，399](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.96dd2e8d1D8FTO&id=547311718970&_u=i27qkbsf35b1)
- [*机箱风扇：超频三（PCCOOLER）疾风F-85 8cm机箱风扇（CPU散热风扇/电脑电源风扇/配螺丝），19.9](https://item.jd.com/550266.html)

#### 其他

- [显示器：戴尔（DELL）27英寸 2K IPS 广色域，2599](https://item.jd.com/100002019331.html)
- [机械键盘：ikbc 正版授权RX-78-2高达无线办公键盘游戏樱桃轴机械键盘红轴，409](https://item.jd.com/100013485652.html)
- [鼠标：雷柏（Rapoo） MT750L 无线鼠标 蓝牙鼠标 办公鼠标 人体工程学 充电鼠标 电脑鼠标，139](https://item.jd.com/100013077446.html)
- [漫步者 （EDIFIER） R101V 蓝牙版多媒体2.1音箱 蓝牙音箱 音响 电脑音箱 黑色，169](https://item.jd.com/100009642308.html)

##### 实际下单价格

xxx

## 三、硬件组装

<span style='color:red;font-size:26px;'>先看机箱说明书！先看机箱安排的各个硬件位置！先看机箱位置！</span>

### 主板

看说明书

<span style='color:red;font-size:22px;'>B460M MORTAR 睡眠唤醒重启问题解决方案</span>

1. 微星进入BIOS是DEL，华硕是DEL/F2，快速选择驱动盘是F11 部分型号是F9
2. 首先更新官10月最新BIOS版本
3. 更新完以后进入BIOS,按F7,回车进入高级模式,唤醒时间设定,把从USB设备唤醒打开
4. 按ESC(第二步操作完的情况下),打开D.T.M(微星主板里的D.T.M), F10保存重启
5. 再进入macos 测试睡眠

### 水冷

看说明书

### 机箱风扇

看看机箱说明，风扇位置在哪，扭螺丝就完事了。

### BIOS设置

- [华硕主板BIOS关闭安全启动方法图解](http://www.winwin7.com/JC/AnZhuang-14238.html)
- [黑苹果之华硕主板BIOS设置详细指导篇](https://www.bilibili.com/read/cv7739198/)

del / F2 进入 BIOS，看界面，搜索关键字，进行设置。 一般按：F1，会显示帮助！

遇到问题全部百度，加交流群问人。

<span style='color:red;font-size:30px;'>微星主板：2020-10月的开始及以后`BIOS`版本，基本不用设置什么，看文章！！！[黑苹果超详细BIOS设置防踩坑指南-微星（MSI）主板BIOS篇](https://www.bilibili.com/read/cv7670096/)</span>

## 四、安装黑果，优化系统

有人推荐这个，我是手动弄的，可以下载试试：

[【AMD&intel】聪聪黑苹果安装工具3.0 零基础一键安装 全网最简单教程 兼容OpenCore及Clover EFI AMD3700X Rx5700 cc](https://www.bilibili.com/video/BV1iE41157Vd)

### OpenCore 配置

- [手把手教你安装黑苹果之openCore-0.6.3 EFI制作全过程，非常详细](https://blog.csdn.net/lxyoucan/article/details/110730680)
- [【macOS平台】如何定制自己的OpenCore macOS启动盘](https://post.smzdm.com/p/a785e48l/)
- [OC Gen X详细讲解教程----目前最小白的黑苹果OC引导定制工具（真的没有更简单了）：https://github.com/Pavo-IM/OC-Gen-X](https://www.bilibili.com/read/cv7581784)
- [【司波图】CometLake十代Intel平台台式机Opencore黑苹果通用配置教程（附安装包）](https://www.bilibili.com/video/BV1uf4y1X7MT?t=36)
- [OpenCore 配置文件检查：OpenCore config.plist Sanity Checker](https://opencore.slowgeek.com/)
- [官方英文教程：OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [OpenCore 简体中文参考手册 | OpenCore 简体中文参考手册(非官方)](https://oc.skk.moe/)
- [SukkaW/OpenCore-Document-zh_Hans: [非官方/Unofficial] OpenCore Bootloader 参考手册简体中文翻译](https://github.com/SukkaW/OpenCore-Document-zh_Hans)
- [验证OpenCore配置是否配置正常：Emulated NVRAM | OpenCore Post-Install]()
- [升级OC引导视频教程](https://blog.csdn.net/lxyoucan/article/details/110958426)
- [OpenCore 版本升级实例 - 0.6.3 升级至 0.6.4](https://www.bilibili.com/video/BV1a54y167Ee)
- [AMD 安装黑果论坛（英文）](https://forum.amd-osx.com/index.php)

### 有线/无线网卡、蓝牙、音频

有线网卡安装玩系统就好了，但是要设置下才能识别！ 无线网卡WiFI 一般主板的都用不了，需要另外买个无线网卡+蓝牙的，推荐：博通芯片（白果就是用的这个，所以可以免驱）

- [【黑苹果必看】有线网卡一定要检查硬件设置](http://imacos.top/2020/09/13/1211-2/)
- [【司波图】10代平台黑苹果Opencore6.0下的声卡驱动&USB定制](https://www.bilibili.com/video/BV1Aa4y1j7CL?t=795)
- [黑苹果无线网卡选择intel还是博通？及其驱动方式详解](https://www.bilibili.com/read/cv8786552)

### 显卡

- [【必看】黑苹果安装显卡支持列表](http://imacosx.com/scb/627.html)
- [各品牌AMD显卡macOS&windows兼容性调查--- AMD、ASUS 、ASrock、MSI、GIGA、XFX等](https://www.bilibili.com/read/cv8648817)
- [【黑苹果系列】AMD显卡性能优化 | 3分钟操作性能提升15%-50%](https://www.bilibili.com/video/BV1mk4y1676k?t=247)
- [【黑苹果系列】AMD显卡性能优化 | 3分钟操作性能提升15%-50%](https://www.bilibili.com/video/BV1S54y1U7Ga?t=116)

## 五、参考资料/文档

### 机箱，主板，CPU、装机推荐等

- [M-ATX 的小机箱推荐？](https://www.zhihu.com/question/320322248)
- [常见的主板规格ATX与mATX比较，各有什么优缺点，选哪个好？](https://www.zhihu.com/question/59271080)
- [Intel-装机推荐](https://osx.cx/retail.html)
- [INTEL史上最全，最详细名称科普](https://www.bilibili.com/read/cv7257556/)
- [i9 10850K和i9 10900K性能区别对比评测](http://www.lotpc.com/yjpc/9066.html)
- [AMD5800x-装机推荐](https://github.com/mrdear/Ryzen-5800x-X570-AORUS-PRO-WIFI-OC0.6.4)

### 完整安装教程

- [macOS Catalina安装教程：联想小新PRO 13 2019/2020兼macOS Catalina安装教程](https://blog.daliansky.net/Lenovo-Xiaoxin-PRO-13-2019-and-macOS-Catalina-Installation-Tutorial.html)
- [macOS BigSur安装教程：天逸510s Mini兼macOS BigSur安装教程](https://blog.daliansky.net/Lenovo-Tianyi-510s-Mini-and-macOS-BigSur-Installation-Tutorial.html)

### 安装好macOS之后要做的系统优化操作

- [安装好macOS之后要做的系统优化操作](https://www.bilibili.com/read/cv8920537)
- [一键开启 macOS HiDPI](https://github.com/xzhih/one-key-hidpi/blob/master/README-zh.md)
- [配合：RDM使用可以快速修改分辨率: https://github.com/avibrazil/RDM](http://avi.alkalay.net/software/RDM/)
- 时间同步，一般在：`Windows` 下修改注册表，然后在 `Mac` 设置下时区就可以了

```shell
# 新建 文本，输入以下内容：

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\TimeZoneInformation]
"RealTimeIsUniversal"=dword:00000001

# 重命名文件： xxx.reg，右键管理员运行 即可！
```

### 其他教程

- [使用 OpenCore 引导黑苹果](https://blog.xjn819.com/post/opencore-guide.html)
- [小白黑苹果驱动常见kext驱动解析](https://www.systemos.cc/xtjc/3612.html)
- [黑苹果常见.kext驱动解读下载](http://bbs.pcbeta.com/viewthread-1860093-1-1.html)
- [黑苹果万能驱动，解读你驱动的含义，声卡、网卡、WiFi、蓝牙、电源、主板、显卡多驱动集结](http://imacos.top/2019/08/01/0914/)
- [MaciASL：提取 DSDT](https://github.com/acidanthera/MaciASL)
- [Getting started with ACPI](https://github.com/dortania/Getting-Started-With-ACPI)
- [OpenCore 0.5+ 部件补丁](https://github.com/daliansky/OC-little)
- [gfxutil](https://github.com/acidanthera/gfxutil/releases)
- [解决安装黑苹果macOS Mojave 10.15 USB3.0或USB3.1无法使用](https://osx.cx/fix-hackintosh-macos-catalina-10-15-beta1-usb3-0.html)
- [开发机黑苹果搭配推荐：专注 macOS，专注代码用途，不搞花里胡哨](https://github.com/cdk8s/cdk8s-team-style/blob/master/other/hardware.md)
- [ProperTree-CN中文版](https://gitee.com/btwise/ProperTree-CN/)

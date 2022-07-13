# Asrock-Z490M-Pro4-AC

显卡：AMD Radeon RX 6800XT

CPU：i9 10900ES（QTB1）

主板：ASrock Z490M Pro4 AC/without AC

硬盘： SN 550 1TB + SN 570 1TB

电源：TT 850W 白金牌

无线网卡和蓝牙：BCM94360CS2

内存：海盗船 16GB 3000 DDR4 x2

# 版本

Mac：12.4
OpenCore：0.8.2

# Bios设置

CFGLOCK——关

主图形适配器——板载（这个选项不会影响独显使用，如果不设置此选项核显无法驱动，不排除是ES CPU的问题）

Secure BOOT——关

# 说明

一切工作良好，除了后面板的USB接口，因为具有过多的USB接口，只能将最上方两个USB接口定义为2.0，舍弃3.0通道，用来连接鼠标键盘。前置包含一个使用转换器转换得到的Type-C接口和一个USB3.0，如果需要使用此EFI，请重新定制USB。

![截屏2022-07-13 22 57 29](https://user-images.githubusercontent.com/100589466/178768142-bda20084-255c-4f77-8755-0a68ec7025b9.png)

![截屏2022-07-13 22 57 51](https://user-images.githubusercontent.com/100589466/178768071-eb9c8e5f-46cf-43f8-b9f7-40936b773f2d.png)

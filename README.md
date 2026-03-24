本方法只用于解决已解锁bootloader
且刷入欧版系统的一加（oneplus）ace3系列手机
无法识别中国运营商的问题
搜寻你需要下载oplusstanvbk.img文件
然后安装adb到你的电脑并且打开手机的adb模式
之后输入以下代码
```adb reboot bootloader
# 刷入 A 分区
fastboot flash oplusstanvbk_a oplusstanvbk.img
# 刷入 B 分区
fastboot flash oplusstanvbk_b oplusstanvbk.img
fastboot reboot
```
此方法操作得当不会抹除手机数据
本人在此声明：刷机需谨慎，如有问题本人概不负责

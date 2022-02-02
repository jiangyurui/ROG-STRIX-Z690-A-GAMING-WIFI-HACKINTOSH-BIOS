# ROG-STRIX-Z690-A-GAMING-WIFI-免引导黑苹果BIOS（目前支持BigSur和Monterey系统）

# 目的
为了建立一个黑苹果新手使用macOS系统的方式（类似于以前OZMOSIS一样），可以让使用者不用去关心bootloader设置问题，直接使用即好（当然万事万物都是一分为二，因为深度定制导致灵活性会差一些，你觉得不好可能是因为你没有这方面的需求，这个对黑苹果新手来说是非常友好的）；

It's a thing like OMOSIS,you can flash it then you can install macOS without bootloader anymore.
# 如果需要定制其他主板BIOS可咨询https://jiangyurui.taobao.com/ ；

# 硬件支持列表：

1.CPU目前支持12代酷睿全系，但因为定制的原因，请使用I7-12700KF以达到最佳效果；

2.显卡支持RX460，470，480，560，570，580，590，5500xt，5600xt，5700xt，6600，6600xt，6800xt，6900xt等免驱显卡；

3.其他硬件请选择黑苹果支持的型号即可；

4.板载WIFI和蓝牙无法驱动（请更换免驱一体卡）；

# 功能支持列表：

1.支持Catalina，BigSur和Monterey系统；

2.CPU超线程和全核心都可正常使用（I7-12700KF，其他CPU应该也可以，但是CPU显示会有问题）；

3.声卡和有线网卡正常使用；

4.定制USB2.0和USB3.0（由于数量超15个，所以主板后置USB3.0上有部分无法使用USB2.0设备，前置USB3.0无此问题）；

5.macOS和Windows双系统（需要使用BootCamp来安装）；

6.Appstore正常使用，AppleID正常登录；

7.istat menus正常使用；

8.12代核显无法驱动，所以必须用免驱独显；

9.睡眠，休眠未测试（对台式机而言不太重要）；

8.其余无法使用可留言；

# 使用方法：

1.请下载对应自身显卡的BIOS文件，用华硕的Flash Back功能刷入主板（具体方法请搜索各大搜索引擎查看）；

2.刷入成功后，请准备一个Fat32格式U盘，把附带的EFI文件或者任意黑苹果引导EFI文件拷贝到U盘，然后用此U盘引导（引导后的第一个界面即可，无需进入系统)进行主板免引导激活，激活后就不再需要U盘，以后都是直接安装系统和使用系统；

3.如果安装了双系统后需要切换系统的话，在开机出现主板LOGO时点击OPTION健（PC键盘为windows键或ALT键），直到左上角出现盘符选择界面即可；


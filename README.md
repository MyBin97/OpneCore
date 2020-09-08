## 通用版

### 适用于微星B450M系列主板

#### 一、说明

1.当前OC版本：正式版0.6.0，支持Catalina 15.6及以下系统（需要引导BigSur请下载[Beat](https://github.com/MyBin97/OpneCore/tree/Beat)分支版引导文件)

2.如果你的主板、显卡和我一模一样，那你可以下载[Perfect](https://github.com/MyBin97/OpneCore/tree/Perfect)版本，这个是我自己使用的，比较完善，并且会优先更新；如果只有主板一样也可以用，只需要把显卡注入项删除

3.我的配置:


| 主板  |          MSI B450M MORTAR MAX 迫击炮          |
| :--: | :-------------------------: |
| 显卡 | 蓝宝石 RX580超白金满血版 |


----------------------

#### 二、使用前必读

1.只是个人兴趣分享，每个人具体配置不同，会出现的问题也不一样，有问题可以跟我说，能解决就解决

2.默认开启-v跑码、显示Nvram等启动项，安装成功后可自行关闭

3.安装成功后请自行更改三码

4.安装成功后自行注入声卡、网卡、显卡地址以及USB定制（可解决声音、Siri、iMessage、发挥显卡win下性能、睡眠唤醒），参考**其它**或自行搜索相关教程

5.测试主板：MSI B450 PRO VDH、B450M MORTAR MAX，在这两块主板上各项工能都正常

6.因为没有无线网卡，所以相关功能无法测试


#### 三、更新内容

##### 2020.9.4日

1.更新正式版OC0.6.0

2.更新全部KEXT驱动为最新

3.添加主题


#### 四、系统截图

![](https://thumbnail0.baidupcs.com/thumbnail/a7d2d8449t0113e313d1b768b3f409d2?fid=414463553-250528-1102366017834459&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-LRR81kci4BDHVI2c3M89F7TixZo%3d&expires=8h&chkbd=0&chkv=0&dp-logid=5832568173608378738&dp-callid=0&time=1599534000&size=c10000_u10000&quality=90&vuk=414463553&ft=image)



#### 五、其它

**大致步骤**

1.网卡内建：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第二个里面

2.声卡注入：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第一个里面

3.USB定制：打开Hackintool,点击USB选项，点击下面扫帚按钮，然后再点击刷新按钮，分别用usb2.0和3.0插入每一个端口，2.0端口选择2.0；3.0端口保留两个，一个选择2.0一个3.0；键盘、鼠标、蓝牙、音箱等选择内建，所有端口保留15个以内，完成后点击导出按钮，把生成的usnports.kext加载到OC配置文件config.plist的Kernel-Add里面（红色口usb3.1可以不定制，只要设备不插在3.1口里就可以正常睡眠）

4.显卡注入：打开Hackintool，点击PCIe找到自己对应显卡，然后复制Device path，添加到config.plist的DeviceProperties-Add第三个，根据你的显卡型号，去下载白苹果数据，找到显卡参数，对应复制到Add第三个里面






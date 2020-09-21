## 通用版

### 适用于微星B450M系列主板

#### 一、说明

1.当前OC版本：正式版0.6.1，支持BigSur、Catalina 15.6及以下系统

2.我的配置:


| CPU  |          AMD 2600          |
| :--: | :-------------------------: |
| 主板 | MSI B450M MORTAR MAX 迫击炮 |
| 显卡 | 蓝宝石 RX580超白金满血版 |



----------------------

#### 二、使用前必读

1.只是个人兴趣分享，每个人具体配置不同，会出现的问题也不一样，有问题可以跟我说，能解决就解决

2.安装成功后请自行更改三码

3.安装成功后自行注入声卡、网卡、显卡地址以及USB定制（可解决声音、Siri、iMessage、发挥显卡win下性能、睡眠唤醒），参考**其它**或自行搜索相关教程

4.测试主板：MSI B450 PRO VDH、B450M MORTAR MAX，在这两块主板上各项工能都正常

5.因为没有无线网卡，所以相关功能无法测试

6.默认关闭-v跑码，隐藏Nvram、Recovery等多余盘符（全新安装建议打开-v）


#### 三、更新内容

##### 2020.9.19日

1.更新正式版 OC0.6.1

2.同步KEXT驱动更新

3.更新OC主题图标

4.支持BigSur和Catalina

5.添加amd传感器驱动

##### 2020.9.4日

1.更新正式版 OC0.6.0

2.更新全部KEXT驱动为最新

3.添加主题


#### 四、系统截图

![](https://github.com/MyBin97/OpneCore/blob/master/截图/1.png)

![](https://github.com/MyBin97/OpneCore/blob/master/截图/2.png)

![](https://github.com/MyBin97/OpneCore/blob/master/截图/3.png)

![](https://github.com/MyBin97/OpneCore/blob/master/截图/4.png)



#### 五、其它

**大致步骤**

1.声卡注入：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第一个里面

2.网卡内建：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第二个里面

3.USB定制：打开Hackintool,点击USB选项，点击下面扫帚按钮，然后再点击刷新按钮，分别用usb2.0和3.0插入每一个端口，2.0端口选择2.0；3.0端口保留两个，一个选择2.0一个3.0；键盘、鼠标、蓝牙、音箱等选择内建，所有端口保留15个以内，完成后点击导出按钮，把生成的usnports.kext加载到OC配置文件config.plist的Kernel-Add里面（红色口usb3.1可以不定制，只要设备不插在3.1口里就可以正常睡眠）

4.显卡注入：打开Hackintool，点击PCIe找到自己对应显卡，然后复制Device path，添加到config.plist的DeviceProperties-Add第三个，根据你的显卡型号，去下载白苹果数据，找到显卡参数，对应复制到Add第三个里面（rx580显卡可以直接粘贴Device path到这里，这里的参数我设置好的）


#### 六、相关链接

1.[远景论坛帖子](http://bbs.pcbeta.com/forum-561-1.html)

2.[使用OpenCore引导黑苹果 BY XJN](https://blog.xjn819.com/?p=543)

3.[精解OpenCore BY 黑果小兵](https://blog.daliansky.net/OpenCore-BootLoader.html)





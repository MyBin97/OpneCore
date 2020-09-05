## 通用版

### 适用于微星B450M系列主板

#### 一、说明

1.当前OC版本：正式版0.6.0，支持Catalina 15.6及以下系统（需要引导BigSur请下载[Beat](https://github.com/MyBin97/OpneCore/tree/Beat)分支版引导文件)

2.如果你的主板、显卡和我一模一样，那你可以下载[Perfect](https://github.com/MyBin97/OpneCore/tree/Perfect)版本，这个是我自己使用的，比较完善，并且会优先更新

3.我的配置:


| 主板  |          MSI B450M MORTAR MAX 迫击炮          |
| :--: | :-------------------------: |
| 显卡 | 蓝宝石 RX580超白金满血版 |


----------------------

#### 二、使用前必读

1.我也刚接触黑苹果不久，资料也全靠爬帖得来，这个只是个人兴趣分享，如果使用有问题可以跟我说，能解决就解决

2.默认开启-v跑码、显示Nvram等启动项，安装成功后可自行关闭

3.安装成功后请自行更改三码

4.安装成功后自行注入声卡、网卡、显卡以及USB定制（可解决声音、Siri、iMessage、发挥显卡win下性能、睡眠唤醒），参考**其它**或自行搜索相关教程

5.测试主板：MSI B450 PRO VDH、B450M MORTAR MAX，在这两块主板上各项工能都正常

6.因为没有无线网卡，所以相关功能无法测试


#### 三、更新内容

##### 2020.9.4日

1.更新正式版OC0.6.0

2.更新全部KEXT驱动为最新

3.添加主题


#### 四、系统截图

![](https://qdall01.baidupcs.com/file/12dffdff4ka657eb59607802273f49f4?bkt=en-864c1d195a8f2f41f3ad75527987fd64d983278e958933d64a839ff27f45fdeb9fcabc966221da608aaae051f7a4f29919a31b20bc7685117147c4a314ff95f1&fid=414463553-250528-577164214933907&time=1599270585&sign=FDTAXUGERLQlBHSKfW-DCb740ccc5511e5e8fedcff06b081203-8V6z93sqZkw1fL5n3gEVV7mKNnU%3D&to=92&size=37903&sta_dx=37903&sta_cs=1&sta_ft=jpg&sta_ct=0&sta_mt=0&fm2=MH%2CXian%2CAnywhere%2C%2Canhui%2Cct&ctime=1599228062&mtime=1599228062&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=37903&vuk=414463553&iv=-2&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-f109e6bd104be8c79cb4ab5f8f4ef3fc580caad2dbfa5573fc2f695844f7ad7a66e14ac94e1f572099a7efb638b4eefc7bd212b8146cc0bc305a5e1275657320&sl=81002574&expires=8h&rt=pr&r=855235725&vbdid=4239290275&fin=1599227647473.jpg&fn=1599227647473.jpg&rtype=1&dp-logid=5761318893435224334&dp-callid=0.1&hps=1&tsl=11&csl=58&fsl=-1&csign=ls%2FEEWYp8Pt9LKajDfuiglqWobw%3D&so=0&ut=8&uter=4&serv=0&uc=1311220622&ti=1d93a8f0247a7ec18b6145fd911d785d9f211298bfff6134&hflag=30&adg=c_afb2a47deb9e0a04f4f761aa1c6c5437&reqlabel=250528_f_b2e1a3b622b48d3cb60d45c70fa00a43_-1_2b4cb3f821a4034952cc1102168be04e&by=themis)



#### 五、其它

**大致步骤**

1.网卡内建：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第二个里面

2.声卡注入：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第一个里面

3.USB定制：打开Hackintool,点击USB选项，点击下面扫帚按钮，然后再点击刷新按钮，分别用usb2.0和3.0插入每一个端口，2.0端口选择2.0；3.0端口保留两个，一个选择2.0一个3.0；键盘、鼠标、蓝牙、音箱等选择内建，所有端口保留15个以内，完成后点击导出按钮，把生成的usnports.kext加载到OC配置文件config.plist的Kernel-Add里面（红色口usb3.1可以不定制，只要设备不插在3.1口里就可以正常睡眠）

4.显卡注入：打开Hackintool，点击PCIe找到自己对应显卡，然后复制Device path，添加到config.plist的DeviceProperties-Add第三个，根据你的显卡型号，去下载白苹果数据，找到显卡参数，对应复制到Add第三个里面






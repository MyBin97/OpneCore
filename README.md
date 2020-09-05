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

1.个人兴趣分享，给刚接触的小白提供方便，不过还是建议还是自行学习

2.默认开启-v跑码、显示Nvram等启动项，安装成功后可自行关闭

3.安装成功后请自行更改三码

4.安装成功后自行注入声卡、网卡以及USB定制（可解决声音、Siri、iMessage、睡眠唤醒），参考**其它**或自行搜索相关教程

5.测试主板：MSI B450 PRO VDH、B450M MORTAR MAX，在这两块主板上各项工能都正常

6.因为没有无线网卡，所以相关功能无法测试


#### 三、更新内容

##### 2020.9.4日

1.更新正式版OC0.6.0

2.更新全部KEXT驱动为最新


#### 四、系统截图

![](https://qdall01.baidupcs.com/file/12dffdff4ka657eb59607802273f49f4?bkt=en-864c1d195a8f2f41f3ad75527987fd64d983278e958933d64a839ff27f45fdeb9fcabc966221da608aaae051f7a4f29919a31b20bc7685117147c4a314ff95f1&fid=414463553-250528-577164214933907&time=1599228279&sign=FDTAXUGERLQlBHSKfW-DCb740ccc5511e5e8fedcff06b081203-3fB1%2BhOJp53lazm9VQF3nOxUkrY%3D&to=92&size=37903&sta_dx=37903&sta_cs=1&sta_ft=jpg&sta_ct=0&sta_mt=0&fm2=MH%2CXian%2CAnywhere%2C%2Cjiangsu%2Ccmnet&ctime=1599228062&mtime=1599228062&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=37903&vuk=414463553&iv=-2&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-f109e6bd104be8c79cb4ab5f8f4ef3fc580caad2dbfa5573fc2f695844f7ad7a66e14ac94e1f572099a7efb638b4eefc7bd212b8146cc0bc305a5e1275657320&sl=81002574&expires=8h&rt=pr&r=349841284&vbdid=3792876375&fin=1599227647473.jpg&fn=1599227647473.jpg&rtype=1&dp-logid=5749962308263101554&dp-callid=0.1&hps=1&tsl=11&csl=58&fsl=-1&csign=ls%2FEEWYp8Pt9LKajDfuiglqWobw%3D&so=0&ut=8&uter=4&serv=0&uc=134589567&ti=0887d9faa0e99264b9f8627355853f1f0956db0b742f90b7305a5e1275657320&hflag=30&adg=c_06d7cc2bf4fc7c5b9ca320df6d532e55&reqlabel=250528_f_47a0a04c20a7697413b45a7eeae444b7_-1_4613b9798bb552a0b3fbe8de2d66e1dc&by=themis)

![](https://qdall01.baidupcs.com/file/a7d2d8449t0113e313d1b768b3f409d2?bkt=en-40ebf341379bd9a0c8fb6f908b1b94b16d180dfb1a1e7d75ba580419262776874f1837f36d75e34c4e72c22c8fba358219a31b20bc7685119ef4b4969ec17ba0&fid=414463553-250528-1102366017834459&time=1599229905&sign=FDTAXUGERLQlBHSKfW-DCb740ccc5511e5e8fedcff06b081203-RJck4%2FZa5Og2b%2FSJmbJ%2FgMJRsHg%3D&to=92&size=40875&sta_dx=40875&sta_cs=0&sta_ft=jpg&sta_ct=0&sta_mt=0&fm2=MH%2CXian%2CAnywhere%2C%2Cjiangsu%2Ccmnet&ctime=1599229883&mtime=1599229883&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=40875&vuk=414463553&iv=-2&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-570fd61358594dbe4945418d31010a0b46c9df087747f727cdb7a9b2ae268763ae881c3b35abf0dbb33d0541ea6b143e429f31265ea4666b305a5e1275657320&sl=81002574&expires=8h&rt=pr&r=466258698&vbdid=3792876375&fin=1599229829610.jpg&fn=1599229829610.jpg&rtype=1&dp-logid=5750398629358683670&dp-callid=0.1&hps=1&tsl=11&csl=58&fsl=-1&csign=ls%2FEEWYp8Pt9LKajDfuiglqWobw%3D&so=0&ut=8&uter=4&serv=0&uc=134589567&ti=0887d9faa0e99264fc0f156d407f1bc1746569d4e559a455305a5e1275657320&hflag=30&adg=c_06d7cc2bf4fc7c5b9ca320df6d532e55&reqlabel=250528_f_47a0a04c20a7697413b45a7eeae444b7_-1_4613b9798bb552a0b3fbe8de2d66e1dc&by=themis)

![](https://qdall01.baidupcs.com/file/911df4d2aj5d140d00efd355f54e4933?bkt=en-6f7dc9883530f8c9b27ea9a3e427f0690a092c7e808a2ad41d9e6213ef6802932e2be0295641e46ee20d07287f1e07306dca165a5306a3d6b1af39619019fe0f&fid=414463553-250528-466487941272303&time=1599229897&sign=FDTAXUGERLQlBHSKfW-DCb740ccc5511e5e8fedcff06b081203-4Mf4Ja7onZPtewICcNcPSpsVXLU%3D&to=92&size=29165&sta_dx=29165&sta_cs=0&sta_ft=jpg&sta_ct=0&sta_mt=0&fm2=MH%2CXian%2CAnywhere%2C%2Cjiangsu%2Ccmnet&ctime=1599229882&mtime=1599229882&resv0=-1&resv1=0&resv2=rlim&resv3=5&resv4=29165&vuk=414463553&iv=-2&htype=&randtype=&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=en-bf4fbff5df0d701ad8829dc7368dc7d545f6089678fddd0b0e958ed087ab70100e7030e34dfeec1f6bc945fe1551c264a688ac0504516944305a5e1275657320&sl=81002574&expires=8h&rt=pr&r=755781730&vbdid=3792876375&fin=1599229812322.jpg&fn=1599229812322.jpg&rtype=1&dp-logid=5750396530500797981&dp-callid=0.1&hps=1&tsl=11&csl=58&fsl=-1&csign=ls%2FEEWYp8Pt9LKajDfuiglqWobw%3D&so=0&ut=8&uter=4&serv=0&uc=134589567&ti=206be03c6e9448454b6505f440d420d34fe6dc80c7f86068&hflag=30&adg=c_06d7cc2bf4fc7c5b9ca320df6d532e55&reqlabel=250528_f_47a0a04c20a7697413b45a7eeae444b7_-1_4613b9798bb552a0b3fbe8de2d66e1dc&by=themis)

#### 五、其它

1.网卡内建：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第二个里面

2.声卡注入：打开Hackintool，点击PCIe找到自己对应网卡，然后复制Device path，然后填写到OC配置文件config.plist的DeviceProperties-Add第一个里面

3.USB定制：打开Hackintool,点击USB选项，点击下面扫帚按钮，然后再点击刷新按钮，分别用usb2.0和3.0插入每一个端口，2.0端口选择2.0；3.0端口保留两个，一个选择2.0一个3.0；键盘、鼠标、蓝牙、音箱等选择内建，所有端口保留15个以内，完成后点击导出按钮，把生成的usnports.kext加载到OC配置文件config.plist的Kernel-Add里面（红色口usb3.1可以不定制，只要设备不插在3.1口里就可以正常睡眠）






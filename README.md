# 注：企业微信-2.4.22版本后，因公司不再使用企业微信，所以后续版本无法进行验证是否可以继续使用。
因为hook的是腾讯地图的定位方法，所以如果腾讯地图没有大的变化，后续版本应该也可使用。

# weworktweak
逆向破解企业微信定位，在家就能打卡了！

双击底部消息按钮即可进入设置页面。

![设置界面](/img/set.PNG)

重签名安装
下载`wework.zip`文件链接:https://share.weiyun.com/5zs5jij 密码：4us4d9

解压`wework.zip`，然后打开 `iOS App Signer`，选择`wework.app`和你要使用的证书和对应的配置文件，不能选错哦。最后start保存就可以导出ipa了。

![打包界面](/img/package.png)

打开xcode，window - Devices - 选择你的设备 - 点击 `+` - 选择ipa - 就可以安装了。如果安装不上通常是证书和配置文件有问题，没有选择对。

![安装界面](/img/install.png)

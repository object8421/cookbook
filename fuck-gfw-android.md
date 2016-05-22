# Android 设备科学上网配置教程

## 第 0 步：下载安装 Shadowsocks APP

Android 下的 Shadowsocks APP 中文名叫做影梭，由于众所周知的原因，国内的应用商店可能无法下载，你可以通过 Google Play 或百度网盘进行下载。

- 百度网盘下载地址：[https://pan.baidu.com/s/1eRqsmWi](https://pan.baidu.com/s/1eRqsmWi)
- Google Play 下载地址：[https://play.google.com/store/apps/details?id=com.github.shadowsocks](https://play.google.com/store/apps/details?id=com.github.shadowsocks)

## 第 1 步：配置服务器设置

第一种方法：最快捷的方式就是扫描二维码配置，打开影梭手机客户端-添加配置文件-扫描二维码（二维码在 PC 端“接点列表”）可一步完成配置。

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/4328214.jpg)

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/56309703.jpg)

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/42679383.jpg)

第二种方法：按图示填写您的 Shadowsocks 服务器地址，远程端口，密码和加密方式。本地端口为 1080，无需更改。

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/18984590.jpg)

## 第 2 步：感受 biu~ 的一声，畅游世界

服务器设置配置完成后，打开右上角代理开关。如果遇到类似下方的安全提示，勾选「我信任此软件」，点「确定」开始连接。

此刻你会听到来自 ZacPark Team 首席客服 Roc.Fang 小伙子发自内心的 biu~ 的一声，没错，那是自由的声音。

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/28351479.jpg)

## 第 3 部分：享受自由

打开浏览器，试着输入 facebook.com，年轻人，是时候跟世界 Say Hi 了。

## 第 4 部分：关于「自动代理模式」和「全局模式」

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/16632375.jpg)

顾名思义，自动代理模式「影梭名字更为直观：绕过局域网及中国大陆地址」通过判断你访问的网络是否被中国大陆特别关怀，从而自动选择是否走代理访问。在自动代理模式下，访问国内网站或者国外没有被特别关怀的网站是不通过代理的，因此，使用自动代理模式不会影响到正常网站的访问速度，只有遇到需要走代理的网站才会走 Shadowsocks 代理。

全局模式则不分什么网站、不管国内国外、不管是否被中国大陆特别关怀，都一律强制走代理模式。全局模式可能造成的后果是开启 Shadowsocks 后访问国内网站会通过代理，从而降低访问速度，如没有特殊情况，我们不建议使用全局模式来进行上网。

Shadowsocks 菜单中的「从 GFWList 更新 PAC」是指自动更新需要走代理访问的网站列表。GFWList 是一个记录哪些网站被中国大陆特别关怀的列表服务，建议经常更新。

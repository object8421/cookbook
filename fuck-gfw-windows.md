# Windows 设备科学上网配置教程

## 第 0 步：下载 Shadowsocks 软件

Windows 7 及以下版本下载链接：https://pan.baidu.com/s/1sjUXhqX
Windows 8及以上版本下载链接：https://pan.baidu.com/s/1qXG2ssk

## 第 1 步：解压并运行

把下载过来的 Shadowsocks 解压到任意目录，运行其中的 Shadowsocks.exe。

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/24964148.jpg)

## 第 2 步：配置服务器设置

首次运行 Shadowsocks 会弹出编辑服务器的窗口，按图示填写你的 Shadowsocks 服务器地址、服务器端口、密码和加密方式，点确定。

底部的代理端口设置为 1080，无需改变。

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/26383434.jpg)

点确定后，会如下提示：

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/39998350.jpg)

## 第 3 步：感受 biu~ 的一声，畅游世界

按提示右键程序图标，弹出菜单，勾选“启用系统代理”

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/76411001.jpg)

此刻你会听到来自 ZacPark Team 首席客服 Roc.Fang 小伙子发自内心的 biu~ 的一声，没错，那是自由的声音。

## 第 4 步：享受自由

打开浏览器，试着输入 facebook.com，年轻人，是时候跟世界 Say Hi 了。

## 第 5 步：关于「自动代理模式」和「全局模式」

顾名思义，自动代理模式通过判断你访问的网络是否被中国大陆特别关怀，从而自动选择是否走代理访问。在自动代理模式下，访问国内网站或者国外没有被特别关怀的网站是不通过代理的，因此，使用自动代理模式不会影响到正常网站的访问速度，只有遇到需要走代理的网站才会走 Shadowsocks 代理。

全局模式则不分什么网站、不管国内国外、不管是否被中国大陆特别关怀，都一律强制走代理模式。全局模式可能造成的后果是开启 Shadowsocks 后访问国内网站会通过代理，从而降低访问速度，如没有特殊情况，我们不建议使用全局模式来进行上网。

Shadowsocks 菜单中的「从 GFWList 更新 PAC」是指自动更新需要走代理访问的网站列表。GFWList 是一个记录哪些网站被中国大陆特别关怀的列表服务，建议经常更新。

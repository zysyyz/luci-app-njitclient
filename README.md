luci-app-njitclient
===================

LuCI configuration pages for <a href="https://github.com/liuqun/njit8021xclient/" target="_blank">njit8021xclient</a> (NJIT 802.1X Client)

适用于<a href="https://github.com/liuqun/njit8021xclient" target="_blank">njit8021xclient</a> (NJIT 802.1X Client) 的LuCI网页管理界面，支持设置是否自启动NJIT Client、保存用户配置信息等。

luci-app-njitclient 1.0 编译后的文件：<a href="http://pan.baidu.com/s/1CbPal" target="_blank">http://pan.baidu.com/s/1CbPal</a>

由于代码中只包含Lua和Bash脚本，所以不受限于平台，编译后的文件可以在任何平台安装：<br/>
opkg install luci-app-njitclient_1.0-1_all.ipk<br/>
同时由于没有设置依赖包，所以可以直接安装。

安装后请访问LuCI中的“系统”->“启动项”，并将“njitclient”设置为启用。<br/>
本插件界面如下：
<img src="http://fmn.rrimg.com/fmn056/20131206/2350/large_NXd0_4b74000045e3125d.jpg" width="720" height="380" alt="preview" />

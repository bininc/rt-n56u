<h1>Padavan修改版本 by Bininc</h1>
<p>更新日期：2017/10/17</p>

<p>刷了恩山论坛里的带APP控制的ROM，发现这个固件性能很不错，占用内存少，网速快，但是有些许Bug，<br>
所以就自己动手编译啦，目前不知道为什么编译出来的，手机APP并不能发现</p>
<p>本人刚刚开始入门，以后慢慢学习进步</p>

------------------------------------------------------------------------------------------
<h2>Padavan修改源码 by bkye</h2>
------------------------------------------
<p>Update:20170608</p>
------------------------------------------<br>
20170608:增加ngrok（可选编译）,写了一个web界面，目前限制最多可以加入5条规则。<br>
加入Transmission和升级WEB管理界面，替换aria2和Transmission的源码为编译好的文件，避免一些朋友因环境问题编译失败。<br>
升级Dnsmasq为2.77，增加了一个FQ规则（具体哪个好自己测试），增加自定义hosts规则（注意格式）。<br>
增加adbyby和koolproxy的自定义规则web界面<br>
把KMS也分离成可选编译<br>
加入lrzsz软件，具体使用方法请百度。<br>
还有一些小问题的修复等等.......<br>
不想要哪个功能就在哪个功能前面加上#号：以下是解释<br>
CONFIG_FIRMWARE_INCLUDE_TRANSMISSION=y（TRANSMISSION）<br>
CONFIG_FIRMWARE_INCLUDE_TRANSMISSION_WEB_CONTROL=y（TRANSMISSION WEB界面）<br>
CONFIG_FIRMWARE_INCLUDE_ARIA=y（Aria2）<br>
CONFIG_FIRMWARE_INCLUDE_ARIA_WEB_CONTROL=y（Aira2 WEB界面）<br>
CONFIG_FIRMWARE_INCLUDE_ADBYBY=y（广告屏蔽）<br>
CONFIG_FIRMWARE_INCLUDE_KMS=y（KMS）<br>
CONFIG_FIRMWARE_INCLUDE_NGROK=y（NGROK）<br>
CONFIG_FIRMWARE_INCLUDE_XUNLEI=y（迅雷）<br>
CONFIG_FIRMWARE_INCLUDE_LRZSZ=y（lrzsz）<br>
原项目地址: https://bitbucket.org/padavan/rt-n56u<br>
汉化文件项目地址:https://git.oschina.net/gorden5566/padavan <br>
源码更新介绍地址（update):http://www.right.com.cn/forum/thread-216667-1-1.html

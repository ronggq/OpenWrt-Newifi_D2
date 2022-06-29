# OpenWrt firmware for Newifi D2
参考使用237176253 大佬的教程：教程：mtk 7621 将openwrt的开源hwnat替换为mtk sdk版本 https://www.right.com.cn/forum/thread-8235037-1-1.html  
采用大佬的源码，配合github的Action功能，实现在线编译。自己的网络老是不行，用在线编译避免网络的问题。
my.config  只有主路由的基本功能加打印机服务，自己用，其他功能用旁路由解决；只有10M不到
open.config 主要功能都有，有待测试。有20几M

本项目只是因为genko大佬的固件没有打印机功能，花了几天时间，学习了其他大佬的代码，组装起来，满足自己需求。
分享出来供有基本需求的大佬使用。
大家可以自己fork后diy固件了。
编译好的固件在两个地方可以下载：

# jgm_autoload
家国梦云手机版

1. 实现自动收货，
收货方式为当出现不想要的货物时，本轮收完所需货物立即重启游戏。
2. 自动升级政策中心
政策中心升级策略为从左到右，从上到下依次升级。
3. 自动升级指定建筑，默认为右上角9号，程序内id=8，可改为任意建筑，以及多个建筑。
4. 自动收钱，执行间隔为2分钟，可通过更改iter值改变。

一. 自动更换建筑版本2.2

1. 目前只能通过固定位置更换，因此只适用于右上角零件厂的情形。
一键换装还在调试中，手头没有趁手的工具，还有些建筑识别错误。
2. 修复了进入政策中心卡死的BUG。


二. 
只收货不换建筑2.2

修复了一个导致大面积收货故障的错误。

只收货不换建筑2.1

1. 重构了代码，能够自动适配各种分辨率，横版除外。已测试720* 1280， 1080* 1920。
2. 修复了进入政策中心卡死的BUG。


******************************************************
备注:
1. 当出现杀进程后，重复登录卡死，请适当延长重启后等待时间，如果机器比较卡，请进一步延长到10秒
2. 如果登录出现故障，请确认手动重复登录授权可用。
3. 如果杀进程后没能重启游戏，请检查按键精灵和游戏是否有唤醒权限以及后台弹出权限。

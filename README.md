# jgm_autoload

家国梦云手机版

3.3
1. 初步优化了一键换装的逻辑，现在可以自动识别该位置是否需要换建筑了。
2. 进一步延长了重启游戏的延时到15秒，以避免意外的卡顿造成在登陆页面点击的众多BUG，未来将进一步优化防卡顿逻辑。


3.2新增指定政策优先升级，修复了开红包的一个低级错误，重新抓取了坐标点，优化了代码逻辑，现在更不容易卡死。




1. 自动适配分辨率，已测试720* 1280， 1080* 1920
2. 实现自动收货，
收货方式为当出现不想要的货物时，本轮收完所需货物立即重启游戏。
只收橙色，只收橙紫，全收三种模式可选。把收货函数里不需要的两种模式注释掉即可。

3. 自动升级政策中心
实现优先升级指定政策。
指定政策优先，可依次指定全部5个，也可以指定最前面的1个或者2个。如果指定政策已满，自动按顺序升级其他政策。

4. 自动升级指定建筑，默认为右上角9号，程序内id=8，可改为任意建筑，以及多个建筑。
5. 自动收钱，执行间隔为2分钟，可通过更改iter值改变。



一. 一件换装收货3.0

1. 新增一键换装
指定收货配置和平时配置，即可一件换装收货，收完又自动换回来。
2. 新增分辨率适配
3. 新增指定政策升级

自动更换建筑版本2.2

修复了进去政策中心后立刻退出的BUG。
1. 目前只能通过固定位置更换，因此只适用于右上角零件厂的情形。
一键换装还在调试中，手头没有趁手的工具，还有些建筑识别错误。
2. 修复了进入政策中心卡死的BUG。


二. 只收货不换建筑3.0

1. 新增指定政策升级

只收货不换建筑2.2
修复了进去政策中心后立刻退出的BUG。
修复了一个导致大面积收货故障的错误。

只收货不换建筑2.1

1. 重构了代码，能够自动适配各种分辨率，横版除外。已测试720* 1280， 1080* 1920。
2. 修复了进入政策中心卡死的BUG。

三. 自动收红包
1. 新增分辨率适配
******************************************************
备注:
1. 当出现杀进程后，重复登录卡死，请适当延长重启后等待时间，如果机器比较卡，请进一步延长到10秒
2. 如果登录出现故障，请确认手动重复登录授权可用。
3. 如果杀进程后没能重启游戏，请检查按键精灵和游戏是否有唤醒权限以及后台弹出权限。

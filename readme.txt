技嘉Gaming5 Z370 + Intel i7 8700k

opencore 0.8.5

macOS 13 Ventura bate7 - bate 9 - bate10 - bate11 - rc2

机型iMac 19,1

***主板上的lockcfk要打开。

***用DP线连接至显示器。

1、USB 已经定制
2、无线蓝牙正常 867M
3、声卡 正常 要修改 id为28(可实现所有端口打开但每次开机自动跳到耳机接口）。常用设置为27.
4、显卡N1080 未能驱动
5、休眠时间长了会启动黑屏。（2022-10-14日更换ssdt，待测试）
6、外接罗技摄像 正常
7、Windows macOS 启动正常
8、sensei(监控软件）可以识别出显卡。
9、调整kexts顺序。
10、修改NVMExpress里的SSD为Apple。
11、DP HDMI 双路输出。
12、替换SSDT-PLUG、SSDT-AWAC。
13、清理tools、Drivers目录。
14、HiDpi 3440x1440 2560x1072 5120x2144 3058x1280可以启动图标。
15、Hackintool 电源后3项为1改成0。（休眠情况待观察）
16、KEXT加入CPUFried,进一步改善睿频。最低评率下降至0.7及变频更积极。
17、至2022年10月19日 睡眠正常。

2022年10月25日 更新

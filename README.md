# G150T-4720hq-hackintosh
```
Laptop model                Thunderobot G150T  
CPU                         Intel Core i7 4720hq
Operate System              macOS BigSur11.1 + Windows 10 
Main board                  N155SD
Discret egraphics           Nvidia GeForce GTX 960M
Integrated graphics         Intel Graphics HD4600
Audio                       Realtek High Definition Audio (ALC269) 
Ethernet                    Realtek RTL8111
Wireless network adapter    DW1820A
```
 
opencore0.6.4 BigSur11.1 DW1820A模拟BCM4350

睡眠唤醒正常，亮度正常，CPU睿频正常，WiFi蓝牙正常，显示接口正常

如需使用iMessage需注入三码

待解决问题：HD4600已驱动但内部屏有屏闪问题，在BigSur以下版本无此问题
已解决！！（bigsur下会屏闪的更换显卡id：0D260007或者bios下UEFI开启CSM）

理论上4代U通用，测试了多台机子，如不是DW1820A的需删除kexts下bcrm驱动。

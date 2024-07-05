# 联想ideapad Y480完美

## 系统配置
- CPU:i5 3210m
- GPU:HD4000
- 内存：4G*2
- 硬盘：金士顿S400 120G
- 系统：macOS Mojave 10.14.6
- WiFi&BT：不支持，更换免驱网卡可以使用
## 运行问题说明
- 原生WiFi&蓝牙无法支持
- 免驱网卡不需要修改网卡白名单，EFI启动会跳过硬件白名单验证
- GT640M LE属于特供本联想机型，故也无法驱动
## 升级说明
同类硬件的MacBook Pro仅支持到macOS Catalina，同时想要流畅运行Catalina是必须要有8G运存，即便如此仍然不能保证流畅，最适合的系统就是10.14.6的Mojave

同时，本EFI仅完美支持的Mojave，升级Catalina需要修改config.plist才能实现，kexts、drivers已经是最新的了（支持Catalina系统）。
  
  

# WD2_fix
看门狗2的相关修复
本脚本用于解决启动游戏后，出现了个看门狗2的小弹窗，但又没进入游戏加载的情况

安装方法：
1.用记事本或者其它文本编辑器打开WD2_fix.bat
2.找到“set LAUNCHER_PATH”开头的那一行
3.把UbisoftConnect.exe的路径，复制到双引号中，示例：
set LAUNCHER_PATH="C:\Program Files (x86)\Ubisoft\Ubisoft Game Launcher\UbisoftConnect.exe"
或set LAUNCHER_PATH="D:\Ubisoft\Ubisoft Game Launcher\UbisoftConnect.exe"
如果安装育碧启动器时使用了默认的路径则不用改（C盘x86.....），如果是自定义安装路径则要自己重新填写。

使用方法：
1.选中WD2_fix脚本右键，“以管理员身份运行”
2.脚本挂着别动，打开uplay，在游戏库中找到看门狗2然后运行（注意不要以其它方式比如exe直接启动，且确保启动没有带参数比如-eac_launcher）
3.如果没问题的话，过一会应该就能进游戏了。每次进游戏要先运行脚本，只要脚本没关闭，再次从uplay中打开游戏也不需要重新打开脚本

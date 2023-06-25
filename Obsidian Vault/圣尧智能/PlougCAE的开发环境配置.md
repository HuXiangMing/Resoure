开发环境
	Qt 5.12.9                      [Index of /archive/qt](https://download.qt.io/archive/qt/)
	OpenCascade 7.5.0      [Download - Open CASCADE Technology](https://dev.opencascade.org/release)
	VS 2015                        [MSDN, 我告诉你 - 做一个安静的工具站 (itellyou.cn)](https://msdn.itellyou.cn/)
	VS开发QT的插件（qt vs tools）
	
环境配置联调
	配置qt vs tools 插件		
		![](Pasted%20image%2020230621131057.png)
		找到Qt安装路径，选择对应版本的qmake.exe
		![](Pasted%20image%2020230621131305.png)
		加载外部项目时这里的版本需要与Qt Installation的版本一致!
		![](Pasted%20image%2020230621131746.png)
		![](Pasted%20image%2020230621131211.png)
	配置c++ 和 occ
		创建一个Qt Widgets Application项目
		![](Pasted%20image%2020230621132137.png)
		配置OCC的动态库DLL，动态库为OCC文件夹下面所有子文件夹里的所有Bin文件里的所有文件，如下，这里存放在里occ_dll文件夹里
		![](Pasted%20image%2020230621132551.png)
		![](Pasted%20image%2020230621132710.png)
		配置头文件目录：如下
		![](Pasted%20image%2020230621132950.png)
		配置静态库目录：如下
		![](Pasted%20image%2020230621133126.png)
		配置静态库的输入：如下
		![](Pasted%20image%2020230621133327.png)
		![](occlib.txt)

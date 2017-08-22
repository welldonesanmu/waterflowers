# 树莓派浇花系统

## 功能：
	可用于浇花等
## 硬件要求：
	树莓派3b，杜邦线（公对母）若干，面包板一个，1路继电器一个，带电源水泵一个，pvc水管，脸盆+塑料水桶
## 语言：
	python 2.7+
## 原理：
树莓派控制继电器，继电器控制水泵工作。	
	（python程序给树莓派gpio发送高或低电平，控制继电器闭合、开启，间接控制水泵工作）

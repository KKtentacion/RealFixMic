# 实时修音麦克风
## 项目简介
整个项目以STM32F407ZGT6为基本平台 通过I2S总线来接受外部经过麦克风ADC转换的数字信号 经过MCU的修音处理 再通过另一根I2S总线传递信号 最后由DAC执行模块将修音过后的数字信号做DAC转换为我们的模拟信号
## 硬件资源
* STM32F407ZGT6
* I2S2 I2S3
* ADC模块:INMP441
* DAC模块:MAX98357
* USB串行接口总线
## 软件环境
* Windows 10
* STM32CubeMX
* Clion-2019
* MinGW
* OpenOCD
* arm-none-eabi-gcc
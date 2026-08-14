# LazyWater🌱💧

LazyWater 是一个基于 STM32F031 的低成本电池供电自动浇水控制器。

项目主要用于盆栽植物的定时浇水，通过锂电池供电，并集成 USB-C 充电、电源管理、水泵驱动和基础控制功能。

## 项目目标

* 使用 STM32F031C6T6 作为主控
* 使用单节锂电池供电
* 支持 USB-C 充电
* 控制低压直流水泵
* 支持定时自动浇水
* 支持手动启动浇水
* 尽可能降低成本和功耗
* 保持硬件结构简单、可靠

## 硬件

主要硬件包括：

* STM32F031C6T6
* 单节锂电池
* 锂电池充电管理电路
* 3.3V 电源电路
* MOSFET 水泵驱动电路
* USB-C 接口
* 手动控制按键
* 状态指示 LED
* SWD 调试接口

后续可预留：

* 土壤湿度传感器
* 水箱液位传感器

## 项目结构

* `Hardware/`：原理图、PCB 和硬件相关文件
* `Firmware/`：STM32 固件
* `.gitignore`：Git 忽略规则
* `README.md`：项目说明

## 当前状态

项目正在开发中。

当前阶段：

* [x] 项目建立
* [ ] 原理图设计
* [ ] PCB 设计
* [ ] PCB 制板
* [ ] 硬件焊接
* [ ] 固件开发
* [ ] 功能测试

## License

This project is currently for personal learning and development.

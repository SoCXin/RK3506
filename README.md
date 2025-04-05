# [RK3506](https://github.com/SoCXin/RK3506)

* [rock-chips](https://www.rock-chips.com/)：[Cortex-A7 + Cortex-M0](https://github.com/SoCXin/Cortex)
* [L5R5](https://github.com/SoCXin/Level): 1.5GHz/200MHz 

## [简介](https://github.com/SoCXin/RK3506/wiki)

[RK3506B](https://www.scensmart.com/general-description-of-soc/rockchip-rk3506/)是瑞芯微Rockchip在2024年第四季度全新推出的Arm嵌入式芯片平台，三核Cortex-A7+单核Cortex-M0多核异构设计，CPU频率达1.5Ghz, M0 MCU为200Mhz。

基于 22nm 先进制程工艺，集成了三核 ARM Cortex-A7 加单核 Cortex-M0，主频高达 1.5GHz。支持 AMP 多核异构架构，一颗芯片可支持 Linux、RTOS、Bare-metal 灵活组合搭配，如 2×Cortex-A7 Linux + 1×Cortex-A7 RTOS + Cortex-M0 HAL 或 3×Cortex-A7 RTOS + Cortex-M0 HAL 等组合，采用标准 RPMsg 核间通信机制。

SDK 原生支持 LVGL 轻量级 UI 框架，并结合芯片内部 2D 硬件加速，让 LVGL 运行更加流畅，从硬件上电到引导程序加载及内核加载，最后到 UI 显示，全链路启动优化。

``` mermaid
gantt
    title RK3506 EVT
    dateFormat  YYYY-MM-DD
    section Mainline Release
    v1.0           :a1, 2024-04-05, 2025-04-05
    v1.1           :a2, 2025-04-05, 2025-12-30
```

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin)

### 开发板

#### Luckfox Lyra

Luckfox Lyra 支持 Buildroot 和 Ubuntu22.04 系统
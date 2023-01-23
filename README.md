# [分级策略](https://github.com/SoCXin/Level)


| 分级梯度 | 性能分级L | 价格分级R |
| ------- | -------- |  ------ |
| Level 1 | Fmax ≤ 60 MHz |   ≤$0.5 |
| Level 2 | Fmax ≤ 120 MHz |  ≤$1.0 |
| Level 3 | Fmax ≤ 200 MHz  | ≤$2.0 |
| Level 4 | [CoreMark](#CoreMark) ≤ 2000 | ≤$3.0  |
| Level 5 | [CoreMark](#CoreMark) ≤ 5000 | ≤$4.0  |
| Level 6 | [CoreMark](#CoreMark) ＞5000 | ≤$6.0  |
| Level 7 | [Geekbench](#Geekbench)＞1000 |   |
| Level 8 | [Geekbench](#Geekbench)＞2000 |   |
| Level 9 | [Geekbench](#Geekbench)＞4000 |   |

* 性能等级 L
* 价格等级 R


|  Architecture  | DMIPS/MHz | CoreMark/MHz | Representative  |
| --------- | --------- | ------------ | ------------ |
| Cortex-M0+ |   0.95    |     2.39  | [RP2040](https://github.com/SoCXin/RP2040) |
| [Cortex-M23](https://www.arm.com/products/silicon-ip-cpu/cortex-m/cortex-m23) |  1.03    |  2.64  | [GD32E231](https://github.com/SoCXin/GD32E231) |
| Cortex-M3 |   1.24    |     3.45  |
| Cortex-M4 |   1.26    |     3.54  |
| Cortex-M33 |  1.54    |     4.10  |
| Cortex-M55 |  1.69    |    4.40   |
| Cortex-M7 |   2.14    |     5.29  | [STM32H730](https://github.com/SoCXin/STM32H730) |
| Cortex-M85 |   3.13   |    6.28   |
| 24KEc |   1.46    |     3.05    | [MT7628](https://github.com/SoCXin/MT7628) |
| 1004KEc |   1.55    |     3.20    | [MT7621](https://github.com/SoCXin/MT7621) |
| Xtensa LX6 |       |    2.07   | [ESP32](https://github.com/SoCXin/ESP32) |
| Xtensa LX7 |       |    2.56   | [ESP32-S3](https://github.com/SoCXin/ESP32S3) |
| [Andes D45](http://www.andestech.com/cn/risc-vandes/) |  2.86  |     5.67    | [HPM6750](https://github.com/SoCXin/HPM6750) |
| C910 |   5.8    |     7.0    |
| C906 |   2.4   |   3.8  |
| E907 |   2.0   |  3.8   |
| E902 |   1.55    |     2.69    |
| [RISC-V4F](https://doc.soc.xin/wch/riscv) |      |    3.19   |[CH32V307](https://github.com/SoCXin/CH32V307) |


## Geekbench

[Geekbench5](https://browser.geekbench.com/v5/cpu/search) 是一款多平台的性能测试工具。与同类软件不同的是，它几乎可以运行在所有的已知PC架构系统上，包括了Windows、Mac OSX、以及各种Linux发行版。Geekbench的测试项目重点考察CPU和内存系统的运算能力，在测试完成后会给出具体得分供用户参考比对。

* Broadcom BCM2711(1500 MHz) Multi-Core : 536 (Single-Core : 178)


## CoreMark

[CoreMark](https://www.eembc.org/coremark/index.php) 是用来衡量嵌入式系统中中心处理单元（CPU，或微控制器MCU）性能的标准，该标准于2009年由EEMBC组织的Shay Gla-On提出，并且试图将其发展成为工业标准，从而代替陈旧的Dhrystone标准。

* Broadcom BCM2711(1500 MHz) EEMBC CoreMark : 33073 (22.049 CoreMark/MHz)


### [www.SoC.xin](http://www.SoC.Xin)

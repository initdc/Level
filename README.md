# [平台分级策略](https://github.com/SoCXin/Level)

* 特别标记 S
* 性能标记 L
* 价格标记 R


| 性能分级 | 最高频率 | DMIPS | CoreMark | 接口数 | FLASH | RAM | 价格分级 |
| ------- | -------- | ---- | --------- | ----- | ----- | ---- | ------ |
| Level 1 | 20 MHz   | X    | X         | X   |   8K |    1K |   ￥2.0 |
| Level 2 | 40 MHz   | X    | X         | X   |  32K |    4K |   ￥4.0 |
| Level 3 | 80 MHz   | 60   | 160       | √   |  64K |   10K |   ￥8.0 |
| Level 4 | 160 MHz  | 150  | √         | √   |  64K |   20K |  ￥16.0 |
| Level 5 | 240 MHz  | √    | √         | √   | 128K |   50K |  ￥30.0 |
| Level 6 | 400 MHz  | √    | √         | √   |  √   |  100K |  ￥50.0 |
| Level 7 | 800 MHz  | √    | √         | √   |  X   |    X  |  ￥80.0 |
| Level 8 | 1.50 GHz | √    | √         | √   |  X   |    X  | ￥100.0 |
| Level 9 | 2.00 GHz | √    | √         | √   |  X   |    X  | ￥160.0 |


---

## 备注

* [CoreMark](https://www.eembc.org/coremark/index.php) 是用来衡量嵌入式系统中中心处理单元（CPU，或微控制器MCU）性能的标准，该标准于2009年由EEMBC组织的Shay Gla-On提出，并且试图将其发展成为工业标准，从而代替陈旧的Dhrystone标准。

* DMIPS (Dhrystone Million Instructions executed Per Second) 用来计算同一秒内系统的处理能力，它的单位以百万来计算，也就是(MIPS)。主要用于测整数计算能力。

### 性能参考

|  内核架构  | DMIPS/MHz | CoreMark/MHz |
| --------- | --------- | ------------ |
| Cortex-M0 |   0.95    |       1.62  |
| Cortex-M3 |   1.25    |     2.19    |
| Cortex-M4 |   1.25    |     2.19    |
| Cortex-M33 |   1.5    |         |
| Cortex-M7 |   2.14    |         |
| 24KEc |   1.55    |     3.05    |

### [探索芯世界 www.SoC.xin](http://www.SoC.Xin)

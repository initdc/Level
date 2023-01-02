# [平台分级策略](https://github.com/SoCXin/Level)

* 性能等级 L
* 价格等级 R

| 分级梯度 | 性能分级 | 价格分级 |
| ------- | -------- |  ------ |
| Level 1 | ≤ 60 MHz |   $0.3 |
| Level 2 | ≤ 120 MHz |  $0.6 |
| Level 3 | ≤ 200 MHz  | $1.0 |
| Level 4 | CoreMark≤ 2000 | $2.0  |
| Level 5 | CoreMark≤ 5000 | $3.0  |
| Level 6 | CoreMark＞5000 | $4.0  |
| Level 7 | Geekbench＞1000 |   |
| Level 8 | Geekbench＞2000 |   |
| Level 9 | Geekbench＞4000 |   |



## CoreMark

[CoreMark](https://www.eembc.org/coremark/index.php) 是用来衡量嵌入式系统中中心处理单元（CPU，或微控制器MCU）性能的标准，该标准于2009年由EEMBC组织的Shay Gla-On提出，并且试图将其发展成为工业标准，从而代替陈旧的Dhrystone标准。

BCM2711(1500 MHz)

* EEMBC CoreMark 33073 (22.049 CoreMark/MHz)

## Geekbench

[Geekbench5](https://browser.geekbench.com/v5/cpu/search) 是一款多平台的性能测试工具。与同类软件不同的是，它几乎可以运行在所有的已知PC架构系统上，包括了Windows、Mac OSX、以及各种Linux发行版。Geekbench的测试项目重点考察CPU和内存系统的运算能力，在测试完成后会给出具体得分供用户参考比对。

BCM2711(1500 MHz)

* Single-Core Score : 178
* Multi-Core Score : 536


### 性能参考

|  Architecture  | DMIPS/MHz | CoreMark/MHz |
| --------- | --------- | ------------ |
| Cortex-M0 |   0.95    |       1.62  |
| Cortex-M3 |   1.25    |     2.19    |
| Cortex-M4 |   1.25    |     2.19    |
| Cortex-M33 |   1.5    |         |
| Cortex-M7 |   2.14    |         |
| 24KEc |   1.55    |     3.05    |
| C906 |   2.4   |   3.8  |
| E907 |   2.0   |  3.8   |
| E902 |   1.55    |     2.69    |
| C910 |   5.8    |     7.0    |



### [www.SoC.xin](http://www.SoC.Xin)

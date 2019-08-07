# [Level](https://github.com/sochub/Level) 
[![sites](SoC/SoC.png)](http://www.qitas.cn) 
## [分级目的](https://github.com/sochub/Level/wiki)

对本平台的各种处理器进行一定的层级划分，更便于评估和选型替换

共分为9级平台，主要的参考指标包括处理能力，成本及用途，SoC资源集成度等。

### MCU

#### L1 

基于主频和外设分类，可编程控制器单核主频0-50MHz归于此处，多核设备主频叠加计算

#### L2

基于主频和资源分类，主频50-200MHz

#### L3

基于主频和性能分类，主频200-800MHz

### APU

#### L4

基于性能分类，主要包括多核心A类高性价比架构产品

#### L5

基于性能分类，主要包括多核心A类高阶架构产品

#### L6

基于算力分类，主要包括多核心异构类产品

### CPU

#### L7

基于性能分类，入门级X86平台

#### L8

基于性能分类，主流X86平台

#### L9

基于性能分类，高阶X86平台

### 参考指标

DMIPS(Dhrystone Million Instructions executed Per Second)

Dhrystone是测量处理器运算能力的最常见基准程序之一，常用于处理器的整型运算性能的测量。Dhrystone是一种整数运算测试程序。

MIPS(Million Instructions executed Per Second) 每秒执行百万条指令，用来计算同一秒内系统的处理能力，即每秒执行了多少百万条指令。

MFLOPS（Million Floating-point Operations per Second），主要用于测浮点计算能力。

MIPS，DMIPS和MFLOPS是常用的CPU性能评估标准。

###  [SoC资源平台](http://www.qitas.cn)  

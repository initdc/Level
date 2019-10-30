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


Family	Model Variant

RISC-V Models    	
RISC-V Models aliases RV32I RV32IM RV32IMC RV32IMAC RV32G RV32GC RV32GCN RV32E RV32EC RV64I RV64IM RV64IMC RV64IMAC RV64G RV64GC RV64GCN (aliases)
MIPS Models    	

MIPS Models aliases ISA M14K M14KcTLB M14KcFMM 4KEc 4KEm 4KEp M4K 4Kc 4Km 4Kp 24Kc 24Kf 24KEc 24KEf 34Kc 34Kf 34Kn 74Kc 74Kf 1004Kc 1004Kf 1074Kc 1074Kf microAptivC microAptivP microAptivCF interAptiv interAptivUP proAptiv 5Kf 5Kc 5KEf 5KEc M5100 M5150 M6200 M6250 MIPS32R6 P5600 P6600 I6400 MIPS64R6 I6500 (aliases)

ARM Models    	
ARM Models aliases ARMv4T ARMv4xM ARMv4 ARMv4TxM ARMv5xM ARMv5 ARMv5TxM ARMv5T ARMv5TExP ARMv5TE ARMv5TEJ ARMv6 ARMv6K ARMv6T2 ARMv6KZ ARMv7 ARM7TDMI ARM7EJ-S ARM720T ARM920T ARM922T ARM926EJ-S ARM940T ARM946E ARM966E ARM968E-S ARM1020E ARM1022E ARM1026EJ-S ARM1136J-S ARM1156T2-S ARM1176JZ-S Cortex-R4 Cortex-R4F Cortex-A5UP Cortex-A5MPx1 Cortex-A5MPx2 Cortex-A5MPx3 Cortex-A5MPx4 Cortex-A8 Cortex-A9UP Cortex-A9MPx1 Cortex-A9MPx2 Cortex-A9MPx3 Cortex-A9MPx4 Cortex-A7UP Cortex-A7MPx1 Cortex-A7MPx2 Cortex-A7MPx3 Cortex-A7MPx4 Cortex-A15UP Cortex-A15MPx1 Cortex-A15MPx2 Cortex-A15MPx3 Cortex-A15MPx4 Cortex-A17MPx1 Cortex-A17MPx2 Cortex-A17MPx3 Cortex-A17MPx4 AArch32 AArch64 Cortex-A32MPx1 Cortex-A32MPx2 Cortex-A32MPx3 Cortex-A32MPx4 Cortex-A35MPx1 Cortex-A35MPx2 Cortex-A35MPx3 Cortex-A35MPx4 Cortex-A53MPx1 Cortex-A53MPx2 Cortex-A53MPx3 Cortex-A53MPx4 Cortex-A55MPx1 Cortex-A55MPx2 Cortex-A55MPx3 Cortex-A55MPx4 Cortex-A57MPx1 Cortex-A57MPx2 Cortex-A57MPx3 Cortex-A57MPx4 Cortex-A72MPx1 Cortex-A72MPx2 Cortex-A72MPx3 Cortex-A72MPx4 Cortex-A73MPx1 Cortex-A73MPx2 Cortex-A73MPx3 Cortex-A73MPx4 Cortex-A75MPx1 Cortex-A75MPx2 Cortex-A75MPx3 Cortex-A75MPx4 MultiCluster ARMv6-M ARMv7-M Cortex-M0 Cortex-M0plus Cortex-M1 Cortex-M3 Cortex-M4 Cortex-M4F (aliases)

POWER Models    	

POWER Models aliases mpc82x UISA m476 m470 m460 m440 (aliases)

Renesas Models    	

Renesas Models aliases V850 V850E1 V850E1F V850ES V850E2 V850E2M V850E2R RH850G3M m16c r8c RL78-S1 RL78-S2 RL78-S3 (aliases)

Other Models    	
Other Models aliases Synopsys ARC_600 Synopsys ARC_605 Synopsys ARC_700 Synopsys ARC_0x21 Synopsys ARC_0x22 Synopsys ARC_0x31 Synopsys ARC_0x32 openCores_generic Andes_N25 Andes_NX25 Microsemi_CoreRISCV Microsemi_MiV_RV32IMA SiFive_E31 SiFive_E51 SiFive_U54 Xilinx MicroBlaze_V7_00 Xilinx MicroBlaze_V7_10 Xilinx MicroBlaze_V7_20 Xilinx MicroBlaze_V7_30 Xilinx MicroBlaze_V8_00 Xilinx MicroBlaze_V8_10 Xilinx MicroBlaze_V8_20 Xilinx MicroBlaze_V9_50 Xilinx MicroBlaze_V10_00 Xilinx MicroBlaze_ISA Altera Nios II_Nios_II_F Altera Nios II_Nios_II_S Altera Nios II_Nios_II_E (aliases)



###  [SoC资源平台](http://www.qitas.cn)  

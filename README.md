# Mixed Signal SoC (RISC-V based Code + PLL) on FPGA
### Presented by Shivani Shah (VSD)
[Github](https://github.com/shivanishah269/risc-v-core)
[Blog](https://www.vlsisystemdesign.com/what-i-did-in-5-day-vsd-workshop-designed-basic-risc-v-core/)

## Objectives

- Integrating RISC-V plus PLL
- rvmyth developed during MYTH Workshop 
- avsdpll_1v8 (analog IP) designed in house by VSD
- RTL plus FPGA flow integration

## RVMYTH RISC-V Core features

- RISC-V ISA - Base Integer RV32I
- Written in Transaction-Level Verilog
- 5 stage pipelined processor
- Register File Bypass technique is used to mitigate data hazards
- B-Type and J-Type Instructions takes extra 2-cyles delay
- RVMYTH currently supports only the CPU core itself, with a small instruction memory anda data memory

## TL-Verilog features

- Transaction-Level Verilog
- Developed by Steve Hoover ([RedwoodEDA](https://www.redwoodeda.com/tl-verilog))
- Powerful to pipeline implementations
- Flexible
- Easy to use

## FPGAs

FPGAs represent a modern alternative to digital implementations, as compared to ASIC, with the following advantages:

- Fast time to market
- Reconfigurable
- Full of resources
  - Configurable blocks
  - Memory
  - Hardcore Processors
  - DSP multipliers
  - PLL
  - Memory interfaces
  - etc.

## TVL to RTL steps

[Link](http://github.com/shivanishas269/RVMYTH_PLL#steps-to-convert-tl-verilog-to-verilog-or-systemverilog)

## Makerchip

MSFPGA_L5 - Makerchip



http://makerchip.com/sandbox/0lYfohqZD/0Wnh58x


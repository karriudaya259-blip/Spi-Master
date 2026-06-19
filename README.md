# SPI Master - Configurable Serial Peripheral Interface Controller

**Brief:** A configurable SPI Master controller designed in Verilog supporting all 4 SPI modes (CPOL/CPHA), programmable clock divider, and 8/16/32-bit transaction lengths. Validated with a self-checking testbench across all modes.

**Tools Used:** Verilog HDL, Icarus Verilog, GTKWave.

**Quick Run:**
```bash
iverilog -o spi_sim spi_master.v tb_spi_master.v
vvp spi_sim
gtkwave dump.vcd

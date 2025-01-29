# Advanced physical design
## <ins>Topic 1 : Inception of open source EDA , OpenLANE and Sky130</ins>
### Introduction to chip and its parts: 
**Introduction to Package**  
 The chips are embedded in a board called package.The chip along with all peripherals connected to it together is a processor / SoC.QFN-48 is one of the example Package.
The chip is connected to the peripherals attached to the processor.The chip consists of a DIE , a CORE and PADS . CORE consists of the logical gates embedded in it and PADS collect the inputs from external and connect it to the internal chip via netlists.Core and Pads make up a die.  
**Componenets of Core**  
Components of Core includes Macros and Foundry IP's.Examples of MACROS include RISCV SoC and FOUNDRY IP's(Intelligent Property) include PLL , SRAM , adc 0 , adc 1 etc.Peripherals like gpio0 , gpio1 , gpio 2 etc are connected to core using pads.  
![Chipconnected](<Screenshot 2025-01-29 201010.png>)
### RISC-V Architecture :
First the code is created using C or C++. Then it is implemented using picorv32 cpu core and finally it is embedded in qflow.
![RISC-V image](<Screenshot2 2025-01-29 205044.png>)
# Direct-Memory-Access-DMA-Programming-with-STM32F4xx
This examples is all about understanding the Direct Memory Access Controller of a microcontroller (here, STM32F407VG) and how to use it in the embedded applications.
**Direct memory access (DMA)** is used in order to provide high-speed data transfer between peripherals and memory as well as memory to memory. 
Data can be quickly moved by DMA without any CPU actions. This keeps CPU resources free for other operations.

**Purpose of SRAM in a microcontroller**
It is used for "non volatile data storage". i.e. it survives after power has been removed. 
It is slower to read and much slower to write than RAM is. All the high speed temporary storage used by a program is in RAM.

An **SRAM** is designed to fill two needs: to provide a direct interface with the CPU at speeds not attainable by DRAMs and 
to replace DRAMs in systems that require very low power consumption. In the first role, the SRAM serves as cache memory, 
interfacing between DRAMs and the CPU.

There will be additional examples of ADC with DMA, USART with DMA exercises.

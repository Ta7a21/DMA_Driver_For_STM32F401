# DMA_Driver_For_STM32F401
## Project description:
A complete software driver for the DMA peripheral in the STM32F401 MCU.
## Project details:
The driver provides the following APIs and more:
* A function to initialize the DMA driver.
* A function to initialize the DMA channel parameters, DMA Peripheral ID, Trigger Source, Source address, a destination address, number of transfers, transfer item size, transfer mode, transfer type(Single or burst).
* A function to request from the driver to start software transfer (memory to memory).
* A function to check the transfer state.

My test code is a dummy client that creates two arrays of integers of size 100 elements, one of them initialized with numbers of 100, 200 till the end, which is the source array. The second one is the destination array with the same type and size and initialized by all zeros. The DMA driver is then used to copy the source array into the destination array.
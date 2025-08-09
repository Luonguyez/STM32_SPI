# STM32 SPI Master with ADC Reading

A simple STM32F411 Discovery project that reads analog input from ADC and sends data over SPI1 .

## Features
- Read ADC value
- Transmit ADC value over SPI
- Control LED follow ADC value

## Tools

- **IDE:** STM32CubeIDE, Arduino IDE (build, debug, flash)  
- **Editor:** Visual Studio Code (coding)  
- **Library:** STM32 HAL, SPI  

## What I Learned

- Configuring ADC using HAL and registers (ADC_SR, ADC_CR2, ADC_SMPRx)  
- Setting up SPI peripheral in master mode with manual NSS control (SPI_CR1, SPI_CR2)  
- Initializing GPIO pins for SPI alternate function and output (GPIOx_MODER, GPIOx_AFRL, GPIOx_ODR)  
- Polling mode ADC conversion and SPI data transmission  


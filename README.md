# stm32-adc-dma

ADC values via DMA

- ADC values on _PA0_ are output to an LED on _PA5_
- ADC values on _PA1_ are output to an LED on _PA6_
- The comparator, on interrupt, outputs high to _PA7_ if _PA0_ has a higher voltage than _PA1_

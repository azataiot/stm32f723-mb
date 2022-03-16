# stm32f723-mb



## uart-tx-dma-poll-ir

Three methods of transferring data on UART:

`HAL_UART_Transmit(huart, pData, Size, Timeout);`  – Poll
`HAL_UART_Transmit_DMA(huart, pData, Size);` – DMA
`HAL_UART_Transmit_IT(huart, pData, Size);` – Interrupt

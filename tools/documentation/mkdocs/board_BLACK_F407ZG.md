#BLACK F407ZG (M4 DEMO)

Below are the pins usable for the peripherals. Pins in **bold** are the default.

## SPI

Instance |MOSI|MISO|SCK|
-|-|-|-|
SPI1|**PA7**, PB5|**PA6**, PB4|**PA5**, PB3|
SPI2|**PB15**, PC3|**PB14**, PC2|**PB10**, PB13|
SPI3|**PB5**, PC12|**PB4**, PC11|**PB3**, PC10|

## I2C

Instance |SDA|SCL|
-|-|-|
I2C1|**PB7**, PB9|**PB6**, PB8|
I2C2|**PB11**, PF0|**PB10**, PF1|
I2C3|**PC9**|**PA8**|

## USART

Instance |RX|TX|
-|-|-|
UART4|**PA1**, PC11|**PA0**, PC10|
UART5|**PD2**|**PC12**|
USART1|**PA10**, PB7|**PA9**, PB6|
USART2|**PA3**, PD6|**PA2**, PD5|
USART3|**PB11**, PC11, PD9|**PB10**, PC10, PD8|
USART6|**PC7**, PG9|**PC6**, PG14|

## I2S

Instance |CK|SD|WS|MCK|
-|-|-|-|-|
I2S2|**PB10**, PB13|**PB15**, PC3|**PB9**, PB12|**PC6**|
I2S3|**PB3**, PC10|**PB5**, PC12|**PA4**, PA15|**PC7**|

## TIM

Instance |CH1|CH2|CH3|CH4|
-|-|-|-|-|
TIM1|**PA8**, PE9, <span style="text-decoration: overline">PA7</span>, <span style="text-decoration: overline">PB13</span>, <span style="text-decoration: overline">PE8</span>|**PA9**, PE11, <span style="text-decoration: overline">PB0</span>, <span style="text-decoration: overline">PB14</span>, <span style="text-decoration: overline">PE10</span>|**PA10**, PE13, <span style="text-decoration: overline">PB1</span>, <span style="text-decoration: overline">PB15</span>, <span style="text-decoration: overline">PE12</span>|**PA11**, PE14|
TIM2|**PA0**, PA5, PA15|**PA1**, PB3|**PA2**, PB10|**PA3**, PB11|
TIM3|**PA6**, PB4, PC6|**PA7**, PB5, PC7|**PB0**, PC8|**PB1**, PC9|
TIM4|**PB6**, PD12|**PB7**, PD13|**PB8**, PD14|**PB9**, PD15|
TIM5|**PA0**|**PA1**|**PA2**|**PA3**|
TIM8|**PC6**, <span style="text-decoration: overline">PA5</span>, <span style="text-decoration: overline">PA7</span>|**PC7**, <span style="text-decoration: overline">PB0</span>, <span style="text-decoration: overline">PB14</span>|**PC8**, <span style="text-decoration: overline">PB1</span>, <span style="text-decoration: overline">PB15</span>|**PC9**|
TIM9|**PA2**, PE5|**PA3**, PE6|||
TIM10|**PB8**, PF6||||
TIM11|**PB9**, PF7||||
TIM12|**PB14**|**PB15**|||
TIM13|**PA6**, PF8||||
TIM14|**PA7**, PF9||||

## ADC 

Instance | Channel | Pin
-|-|-
ADC1|IN0|PA0|
ADC1|IN1|PA1|
ADC1|IN2|PA2|
ADC1|IN3|PA3|
ADC1|IN4|PA4|
ADC1|IN5|PA5|
ADC1|IN6|PA6|
ADC1|IN7|PA7|
ADC1|IN8|PB0|
ADC1|IN9|PB1|
ADC1|IN10|PC0|
ADC1|IN11|PC1|
ADC1|IN12|PC2|
ADC1|IN13|PC3|
ADC1|IN14|PC4|
ADC1|IN15|PC5|
ADC2|IN0|PA0|
ADC2|IN1|PA1|
ADC2|IN2|PA2|
ADC2|IN3|PA3|
ADC2|IN4|PA4|
ADC2|IN5|PA5|
ADC2|IN6|PA6|
ADC2|IN7|PA7|
ADC2|IN8|PB0|
ADC2|IN9|PB1|
ADC2|IN10|PC0|
ADC2|IN11|PC1|
ADC2|IN12|PC2|
ADC2|IN13|PC3|
ADC2|IN14|PC4|
ADC2|IN15|PC5|
ADC3|IN0|PA0|
ADC3|IN1|PA1|
ADC3|IN2|PA2|
ADC3|IN3|PA3|
ADC3|IN4|PF6|
ADC3|IN5|PF7|
ADC3|IN6|PF8|
ADC3|IN7|PF9|
ADC3|IN8|PF10|
ADC3|IN9|PF3|
ADC3|IN10|PC0|
ADC3|IN11|PC1|
ADC3|IN12|PC2|
ADC3|IN13|PC3|
ADC3|IN14|PF4|
ADC3|IN15|PF5|

## GPIO 

Pin | Peripheral signal available on the pin | Board macro
-|-|-
PA0 |ADC1_IN0, ADC2_IN0, ADC3_IN0, ETH_CRS, SYS_WKUP, TIM2_CH1, TIM2_ETR, TIM5_CH1, TIM8_ETR, UART4_TX, USART2_CTS||
PA1 |ADC1_IN1, ADC2_IN1, ADC3_IN1, ETH_REF_CLK, ETH_RX_CLK, TIM2_CH2, TIM5_CH2, UART4_RX, USART2_RTS||
PA2 |ADC1_IN2, ADC2_IN2, ADC3_IN2, ETH_MDIO, TIM2_CH3, TIM5_CH3, TIM9_CH1, USART2_TX||
PA3 |ADC1_IN3, ADC2_IN3, ADC3_IN3, ETH_COL, TIM2_CH4, TIM5_CH4, TIM9_CH2, USART2_RX, USB_OTG_HS_ULPI_D0||
PA4 |ADC1_IN4, ADC2_IN4, DAC_OUT1, DCMI_HSYNC, I2S3_WS, SPI1_NSS, SPI3_NSS, USART2_CK, USB_OTG_HS_SOF|**SS**|
PA5 |ADC1_IN5, ADC2_IN5, DAC_OUT2, SPI1_SCK, TIM2_CH1, TIM2_ETR, TIM8_CH1N, USB_OTG_HS_ULPI_CK|**SCK**|
PA6 |ADC1_IN6, ADC2_IN6, DCMI_PIXCK, SPI1_MISO, TIM1_BKIN, TIM3_CH1, TIM8_BKIN, TIM13_CH1|**MISO**|
PA7 |ADC1_IN7, ADC2_IN7, ETH_CRS_DV, ETH_RX_DV, SPI1_MOSI, TIM1_CH1N, TIM3_CH2, TIM8_CH1N, TIM14_CH1|**MOSI**|
PA8 |I2C3_SCL, RCC_MCO_1, TIM1_CH1, USART1_CK, USB_OTG_FS_SOF||
PA9 |DCMI_D0, I2C3_SMBA, TIM1_CH2, USART1_TX, USB_OTG_FS_VBUS||
PA10 |DCMI_D1, TIM1_CH3, USART1_RX, USB_OTG_FS_ID||
PA11 |CAN1_RX, TIM1_CH4, USART1_CTS, USB_OTG_FS_DM||
PA12 |CAN1_TX, TIM1_ETR, USART1_RTS, USB_OTG_FS_DP||
PA13 |SYS_JTMS-SWDIO||
PA14 |SYS_JTCK-SWCLK||
PA15 |I2S3_WS, SPI1_NSS, SPI3_NSS, SYS_JTDI, TIM2_CH1, TIM2_ETR||
PB0 |ADC1_IN8, ADC2_IN8, ETH_RXD2, TIM1_CH2N, TIM3_CH3, TIM8_CH2N, USB_OTG_HS_ULPI_D1||
PB1 |ADC1_IN9, ADC2_IN9, ETH_RXD3, TIM1_CH3N, TIM3_CH4, TIM8_CH3N, USB_OTG_HS_ULPI_D2||
PB2 |||
PB3 |I2S3_CK, SPI1_SCK, SPI3_SCK, SYS_JTDO-SWO, TIM2_CH2||
PB4 |I2S3_ext_SD, SPI1_MISO, SPI3_MISO, SYS_JTRST, TIM3_CH1||
PB5 |CAN2_RX, DCMI_D10, ETH_PPS_OUT, I2C1_SMBA, I2S3_SD, SPI1_MOSI, SPI3_MOSI, TIM3_CH2, USB_OTG_HS_ULPI_D7||
PB6 |CAN2_TX, DCMI_D5, I2C1_SCL, TIM4_CH1, USART1_TX|**SCL**|
PB7 |DCMI_VSYNC, FSMC_NL, I2C1_SDA, TIM4_CH2, USART1_RX|**SDA**|
PB8 |CAN1_RX, DCMI_D6, ETH_TXD3, I2C1_SCL, SDIO_D4, TIM4_CH3, TIM10_CH1||
PB9 |CAN1_TX, DCMI_D7, I2C1_SDA, I2S2_WS, SDIO_D5, SPI2_NSS, TIM4_CH4, TIM11_CH1||
PB10 |ETH_RX_ER, I2C2_SCL, I2S2_CK, SPI2_SCK, TIM2_CH3, USART3_TX, USB_OTG_HS_ULPI_D3||
PB11 |ETH_TX_EN, I2C2_SDA, TIM2_CH4, USART3_RX, USB_OTG_HS_ULPI_D4||
PB12 |CAN2_RX, ETH_TXD0, I2C2_SMBA, I2S2_WS, SPI2_NSS, TIM1_BKIN, USART3_CK, USB_OTG_HS_ID, USB_OTG_HS_ULPI_D5||
PB13 |CAN2_TX, ETH_TXD1, I2S2_CK, SPI2_SCK, TIM1_CH1N, USART3_CTS, USB_OTG_HS_ULPI_D6, USB_OTG_HS_VBUS||
PB14 |I2S2_ext_SD, SPI2_MISO, TIM1_CH2N, TIM8_CH2N, TIM12_CH1, USART3_RTS, USB_OTG_HS_DM||
PB15 |I2S2_SD, RTC_REFIN, SPI2_MOSI, TIM1_CH3N, TIM8_CH3N, TIM12_CH2, USB_OTG_HS_DP||
PC0 |ADC1_IN10, ADC2_IN10, ADC3_IN10, USB_OTG_HS_ULPI_STP|**LED_BUILTIN**|
PC1 |ADC1_IN11, ADC2_IN11, ADC3_IN11, ETH_MDC||
PC2 |ADC1_IN12, ADC2_IN12, ADC3_IN12, ETH_TXD2, I2S2_ext_SD, SPI2_MISO, USB_OTG_HS_ULPI_DIR||
PC3 |ADC1_IN13, ADC2_IN13, ADC3_IN13, ETH_TX_CLK, I2S2_SD, SPI2_MOSI, USB_OTG_HS_ULPI_NXT||
PC4 |ADC1_IN14, ADC2_IN14, ETH_RXD0||
PC5 |ADC1_IN15, ADC2_IN15, ETH_RXD1||
PC6 |DCMI_D0, I2S2_MCK, SDIO_D6, TIM3_CH1, TIM8_CH1, USART6_TX||
PC7 |DCMI_D1, I2S3_MCK, SDIO_D7, TIM3_CH2, TIM8_CH2, USART6_RX||
PC8 |DCMI_D2, SDIO_D0, TIM3_CH3, TIM8_CH3, USART6_CK||
PC9 |DCMI_D3, I2C3_SDA, I2S_CKIN, RCC_MCO_2, SDIO_D1, TIM3_CH4, TIM8_CH4||
PC10 |DCMI_D8, I2S3_CK, SDIO_D2, SPI3_SCK, UART4_TX, USART3_TX||
PC11 |DCMI_D4, I2S3_ext_SD, SDIO_D3, SPI3_MISO, UART4_RX, USART3_RX||
PC12 |DCMI_D9, I2S3_SD, SDIO_CK, SPI3_MOSI, UART5_TX, USART3_CK||
PC13 |RTC_AF1||
PC14 |RCC_OSC32_IN||
PC15 |ADC1_EXTI15, ADC2_EXTI15, ADC3_EXTI15, RCC_OSC32_OUT||
PD0 |CAN1_RX, FSMC_D2, FSMC_DA2||
PD1 |CAN1_TX, FSMC_D3, FSMC_DA3||
PD2 |DCMI_D11, SDIO_CMD, TIM3_ETR, UART5_RX||
PD3 |FSMC_CLK, USART2_CTS|**LED_BUILTIN2**|
PD4 |FSMC_NOE, USART2_RTS||
PD5 |FSMC_NWE, USART2_TX||
PD6 |FSMC_NWAIT, USART2_RX||
PD7 |FSMC_NCE2, FSMC_NE1, USART2_CK||
PD8 |FSMC_D13, FSMC_DA13, USART3_TX||
PD9 |FSMC_D14, FSMC_DA14, USART3_RX||
PD10 |FSMC_D15, FSMC_DA15, USART3_CK||
PD11 |FSMC_A16, FSMC_CLE, USART3_CTS||
PD12 |FSMC_A17, FSMC_ALE, TIM4_CH1, USART3_RTS||
PD13 |FSMC_A18, TIM4_CH2||
PD14 |FSMC_D0, FSMC_DA0, TIM4_CH3||
PD15 |FSMC_D1, FSMC_DA1, TIM4_CH4||
PDR_ON |||
PE0 |DCMI_D2, FSMC_NBL0, TIM4_ETR||
PE1 |DCMI_D3, FSMC_NBL1||
PE2 |ETH_TXD3, FSMC_A23, SYS_TRACECLK||
PE3 |FSMC_A19, SYS_TRACED0||
PE4 |DCMI_D4, FSMC_A20, SYS_TRACED1||
PE5 |DCMI_D6, FSMC_A21, SYS_TRACED2, TIM9_CH1||
PE6 |DCMI_D7, FSMC_A22, SYS_TRACED3, TIM9_CH2||
PE7 |FSMC_D4, FSMC_DA4, TIM1_ETR||
PE8 |FSMC_D5, FSMC_DA5, TIM1_CH1N||
PE9 |FSMC_D6, FSMC_DA6, TIM1_CH1||
PE10 |FSMC_D7, FSMC_DA7, TIM1_CH2N||
PE11 |FSMC_D8, FSMC_DA8, TIM1_CH2||
PE12 |FSMC_D9, FSMC_DA9, TIM1_CH3N||
PE13 |FSMC_D10, FSMC_DA10, TIM1_CH3||
PE14 |FSMC_D11, FSMC_DA11, TIM1_CH4||
PE15 |FSMC_D12, FSMC_DA12, TIM1_BKIN||
PF0 |FSMC_A0, I2C2_SDA||
PF1 |FSMC_A1, I2C2_SCL||
PF2 |FSMC_A2, I2C2_SMBA||
PF3 |ADC3_IN9, FSMC_A3||
PF4 |ADC3_IN14, FSMC_A4||
PF5 |ADC3_IN15, FSMC_A5||
PF6 |ADC3_IN4, FSMC_NIORD, TIM10_CH1||
PF7 |ADC3_IN5, FSMC_NREG, TIM11_CH1||
PF8 |ADC3_IN6, FSMC_NIOWR, TIM13_CH1||
PF9 |ADC3_IN7, DAC_EXTI9, FSMC_CD, TIM14_CH1||
PF10 |ADC3_IN8, FSMC_INTR||
PF11 |ADC1_EXTI11, ADC2_EXTI11, ADC3_EXTI11, DCMI_D12||
PF12 |FSMC_A6||
PF13 |FSMC_A7||
PF14 |FSMC_A8||
PF15 |FSMC_A9||
PG0 |FSMC_A10||
PG1 |FSMC_A11||
PG2 |FSMC_A12||
PG3 |FSMC_A13||
PG4 |FSMC_A14||
PG5 |FSMC_A15||
PG6 |FSMC_INT2||
PG7 |FSMC_INT3, USART6_CK||
PG8 |ETH_PPS_OUT, USART6_RTS||
PG9 |FSMC_NCE3, FSMC_NE2, USART6_RX||
PG10 |FSMC_NCE4_1, FSMC_NE3||
PG11 |ETH_TX_EN, FSMC_NCE4_2||
PG12 |FSMC_NE4, USART6_RTS||
PG13 |ETH_TXD0, FSMC_A24, USART6_CTS||
PG14 |ETH_TXD1, FSMC_A25, USART6_TX||
PG15 |DCMI_D13, USART6_CTS||
PH0 |RCC_OSC_IN||
PH1 |RCC_OSC_OUT||
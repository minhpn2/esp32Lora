esp32Lora
- This project will build on Cpp and compiled by CMake. 
- Using FreeRTOS.
- Function:
+ Ethernet
+ MQTT
+ SPI communication with 3 slaves: - Lora Module SX1278
                                   - 74HC595 for extern output ports: 7 channels
                                   - 74HC165 for extern input ports: 7 channels
+ 4 ADC: - 2 for read 4-20mA
         - 2 for read 0-10V
+ 1 MODBUS RTU via serial: UART

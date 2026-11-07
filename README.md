# Emir Ebubekir Keleş

I write firmware for STM32 and ESP32, mostly bare-metal C.

At GESK Technologies I built packet radio links between STM32 boards with the S2-LP
transceiver, integrated an MFRC522 RFID reader over SPI, wrote UART, SPI and I2C drivers
for Cortex-M parts, and worked on a gateway that moved sensor data over RF and MQTT.
That code stayed with the company.

Things I can share:

- [Motor control on an STM32F051](https://github.com/emirkls44/industrial_motor_control_stm32):
  soft start/stop, e-stop, watchdog and a small framed UART protocol, with tests running in CI.
- [The ESP32 side of it](https://github.com/emirkls44/industrial-motor-control-esp32-gateway):
  bridges the motor controller to MQTT and stops the motor if the link goes quiet.
- [SHT3x driver](https://github.com/emirkls44/STM32_I2C_TEMP_SHT3X_Modular):
  interrupt-driven I2C written against the registers, no HAL.
- [STM32F0 exercises](https://github.com/emirkls44/stm32f0-learning) from when I was learning the part.

Contact: emirkls44@gmail.com · LinkedIn: linkedin.com/in/emir-ebubekir-keleş

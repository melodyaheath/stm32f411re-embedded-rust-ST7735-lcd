# stm32f411re-embedded-rust-ST7735-lcd

Quick Pinout Guide
------

| Nucleo-F411RE Pin | ST7735 Pin  |
|-------------------|-------------|
| 5V                | Vin/5V      |
| GND               | GND         |
| GND               | GND         |
|                   | NC          |
|                   | NC          |
| 5V or 3V          | LED         |
| PA5               | SCL/SCK     |
| PA7               | SDA/MOSI    |
| PB0               | RS/DC       |
| PC9               | RST/RES     |
| GND               | CS          |

What is this project?
------

This is based on the [cortex-m-quickstart](https://github.com/rust-embedded/cortex-m-quickstart) project.

The code is for the stm32-f411re processor, and is meant for the nucleo-f411re board. This is for the ST7735 LCD. This will display a red background on the LCD and serves as a simple way to verify your ST7735 works. 

I've included some resources that have helped me along the way.

![Nucleo F411RE Mappings](/alternate-function-mappings-p1.png)

![Arduino Connectors Part 1](/arduino-connectors-p1.png)

![Arduino Connectors Part 2](/arduino-connectors-p2.png)

![Nucleo F411RE Mappings](/nucleo-f411re-mappings.png)

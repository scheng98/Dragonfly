# Dragonfly

This is Dragonfly, a small (0.7 in. x 1.4 in.) breakout board for ST's latest high-performance, ultra-low-power line of 32-bit microcontrollers: the STM32L4X6 family. Dragonfly uses the STM32L476RE 64-pin LQFP chip package with 512 kB of high-speed flash memory, 128 kB SRAM, running at up to 80 MHz with a single-precision floating point unit. Dragonfly is for sale at [Tindie](https://www.tindie.com/products/onehorse/dragonfly-stm32l4-breakout-board/) for $29.95.

![](https://cloud.githubusercontent.com/assets/6698410/15269579/faa7fbbc-19b7-11e6-888c-075d5f83ac31.jpg)

This is a repository of simple sketches that demonstrate how to use the Arduino IDE to program Dragonfly to read sensors, send serial output, control radios and displays, etc. If you can run a blink sketch in Arduino you can program a 32-bit Cortex M4F microcontroller!

Here's Dragonfly running three RGB leds through the color spectrum using 9 PWM outputs via the Blink_pwm_Dragonfly.ino sketch!

![](https://cloud.githubusercontent.com/assets/6698410/14970256/538ca164-107c-11e6-9ae7-14e755f4c592.jpg)

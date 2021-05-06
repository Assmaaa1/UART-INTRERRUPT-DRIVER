# UART-INTRERRUPT-DRIVER

This program implement a usart driver and usart interrupt driver  for STM32f411 based board

It allows not only to send and receive data through uart interface but also 

to generate an interrupt each time a received data is detected.

A initial sketch is to control the rate of toggling the user led through the communicated 

toggling frequency, further applications might be explored.

The program is developed under keil uvision ,version 5 and it is tested on STM32F411E-DISCO board 

The baud rate = 9600  bps

Clock frequency = 16 Mhz

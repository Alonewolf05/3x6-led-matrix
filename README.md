# 3x6-led-matrix
High Power Led Matrix Schematic and PCB Design

Using transistors, shift registers can be used for high power LED applications.

There are 8 pins and micro usb type-b inputs for this board. USB is just for powering the board. No data tranferrings.
ICs are SN74HC595 modules with SOIC127 package.

Pin | Pin Description
------------ | -------------
1 | SRCLK for IC2
2 | SRCLK for IC1
3 | RCLK for IC2
4 | RCLK for IC1
5 | SER for IC2
6 | SER for IC1
7 | GND
8 | +5V


With IC1, rows of led matrix and with IC2 columns of led matrix will be controlled

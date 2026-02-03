# Colourizer Core
RTL architecture for the image colourizer core. Includes the Top module, a module for interpreting user commands over UART, and a module for reading data from BRAM, computing RGB colour weights, colouring pixels, and passing coloured pixels to UART transmitter. 

## Command Encorder
Waits to receive "strobe" signal and begins sampling datafrom UART receiver at next clock cycle. 


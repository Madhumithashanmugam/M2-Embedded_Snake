# REQUIREMENTS

## INTRODUCTION

    Simple Snake game developed with ATMega328p and LED Matrix.
  
## ATMega328P

    ATMEGA328P is high performance, low power controller from Microchip. ATMEGA328P is an 8-bit microcontroller based on AVR RISC architecture. It is the most popular of all AVR controllers as it is used in ARDUINO boards. It has a modified Harvard architecture 8-bit RISC processor core.ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed. 
    
## GETTING STARTED

    Basic components required are
    
    1. Microcontroller (ATmega 328P)
    2. LED Matrix
    
## SOFTWARE USED

    1. VS code
    2. SimulIDE
    3. Avr gcc
    
 ## PREREQUISITE
 
    In this case I was using the terminal from linux
    Install avr gcc by running the following command  
    
    sudo apt-get install gcc-avr binutils-avr avr-libc
    
    Install avrdude by running
    
    sudo apt-get install avrdude
    
## INSTALLING

    To upload the code to the chip, one can run these commands:
    
    The following compiles the code to a.obj file
    
    avr-gcc -g -Os -Wall -mcall-prolog
    
    The following code compiles the code to a .hex file
    
    avr-objcopy -R .eeprom -O ihex main.obj.main.
    
 ## 4W'S AND 1H
 
 ### WHO
 
    Any one can play the game.
    
 ### WHAT
 
    The project main aim is to develop a simple snake using ATmega 328p and LED matrix.
    
 ### WHEN
 
    User can enjoy playing their game.
    
 ### WHY
 
    The project is to enjoy to play the game.
    
 ### HOW
 
    Anyone can play the game.
    
 

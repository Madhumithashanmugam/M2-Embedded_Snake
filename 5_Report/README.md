
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
    
 ## DESIGN
 
 ### ACTIVITY DIAGRAM
 
 ![Activity diagram](https://user-images.githubusercontent.com/94168215/144235242-10710fae-bfee-43bf-8ee3-0818a25de747.png)
 
 
 


### SCHEMATIC DIAGRAM

 ![schematicdiagram](https://user-images.githubusercontent.com/94168215/144235351-883e00cf-08d1-4999-acbb-24dbf88ff054.png)





![Snake game](https://user-images.githubusercontent.com/94168215/144235381-70ade77b-1eef-44e6-8c7a-35ea8779cf90.png)



## IMPLEMENTATION
### INTRODUCTION

     This folder conatins all the coding files as well as the resources and testing files neede for proper execution of program.
     
## INSTRUCTIONS TO EXECUTE

      1.Clone my repository
      2.Go to 3_Implementation folder
      3.Make sure your system meets all software and hardware requirements
      4.Run "make run" command in terminal for main code execution
      5.Run "make run_test" command in terminal for test code execution.

## Folder Structure
|Column 1 Header |Column 2 Header |
|--- |--- 


## OUTPUT

![Snake game](https://user-images.githubusercontent.com/94168215/144235677-2d6f341a-5134-474f-8d6c-2178d4309083.gif)



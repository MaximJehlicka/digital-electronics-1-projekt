# digital-electronics-1-projekt
### Team members

* Bořvoj Kramný (responsible for coding)
* Maxim Jehlička (responsible for coding)
* Peter Čeleš (responsible for coding, github)

## Theoretical description and explanation

The project is about implementing morse code encoder and decoder. First we are creating morse code encoder. Our approach to this is that we choose one letter that we want to encode by toggling the switches. So input will be 5-bit switch that will represent each letter by its serial number in the alphabet. Outputs will be 7 segment display that will display a letter that will be encoded into morse code and LED diode that will represent morse code by turning on and off depending on which letter will be set by the switch. 
Durations of each characters will be: Dot: 250 milliseconds, Dash: 750ms, Space between characters: 250ms.

### Alphabet represented in 5-bit binary

| **Character** | **5-bit value** | **Character** | **5-bit value** |
   | :-: | :-: | :-: | :-: |
   | A | 00001 | M | 01101 |
   | B | 00010 | N | 01110 |
   | C | 00011 | O | 01111 |
   | D | 00100 | P | 10000 |
   | E | 00101 | Q | 10001 |
   | F | 00110 | R | 10010 |
   | G | 00111 | S | 10011 |
   | H | 01000 | T | 10100 |
   | I | 01001 | U | 10101 |
   | J | 01010 | V | 10110 |
   | K | 01011 | Y | 10111 |
   | L | 01100 | Z | 11000 |
   
   ### Morse alphabet
   
   <img src="images/morse_alphabet.png" alt="morse" style="width:450px;"/>

## Hardware description of demo application

<img src="images/n4r.png" alt="hardware" style="width:450px;"/>

<img src="images/7seg_rgb.png" alt="hardware" />


## Software description

### Schematic of implementation:

<img src="images/schematic.png" alt="schematic" />

## Component(s) simulation

### Simulation of encoding a word "AHOJ":

<img src="images/simulation1.png" alt="simulation_encoder" />

## Refenrences

- [digital-electronics-1 course](https://github.com/tomas-fryza/digital-electronics-1/tree/master/labs)
- https://en.wikipedia.org/wiki/Morse_code

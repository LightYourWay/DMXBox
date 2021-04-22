# DMXBox
A DMX/RDM Library for bidirectional RS485 communication.

## Vison
This library should obey the following principles
- easy to implement for anyone working with microcontrollers (e.g. ATMega 2560)
- DMX and RDM implemented up to `E1.11 – 2008, USITT DMX512-A` specification
- Support for Serial read and write as well as Ethernet, ArtNet and sACN
- Implements Observer Pattern and thus can be easily tailored to any usecase
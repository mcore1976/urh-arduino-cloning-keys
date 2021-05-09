Example of cloning my garage keys with Arduino Digispark and FS1000A transmitter. 
The keys sequences were recorded first using Universal Radio Hacker tool and relevant information about pulses  and puses copied to Arduino sketch. 


Components :
- 1 x Digispark device
- 1 x FS1000A module ( frequency 433,92MHz for EU/Asia or 315MHz for US/Canada)
- 1 x RTL-SDR dongle for PC to use with URH (Universal Radio Hacker) tool
- 1 x powerbank 5V to power clonned keyfob
- 1 x PC ( Linux / Windows / Mac)

Connections :
Connect Digispark to FS1000A module
- 5V Digispark <-> VCC FS1000A
- P2 (PB2) Digispark <-) DATA FS1000A
- GND Digispark <-> GND FS1000A
- Connect some antenna 15cm to FS1000A antenna pin !

See videos how to clone your key : https://www.youtube.com/watch?v=jziWQA8Wvp4


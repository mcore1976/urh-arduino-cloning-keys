Example of cloning my garage keys with Arduino Digispark and FS1000A transmitter. 
The key sequences were recorded first using Universal Radio Hacker tool and relevant information about pulses  and pauses within the radio signal copied to Arduino sketch. 


Components :
- 1 x Digispark device
- 1 x FS1000A module ( frequency 433,92MHz for EU/Asia or 315MHz for US/Canada)
- 1 x RTL-SDR dongle for PC to use with URH (Universal Radio Hacker) tool
- 1 x powerbank 5V to power clonned keyfob
- 1 x PC ( Linux / Windows / Mac) for recording key transmission with URH ( https://github.com/jopohl/urh ) and RTL-SDR USB dongle 

Connections :
Connect Digispark to FS1000A module
- 5V Digispark <-> VCC FS1000A
- P2 (PB2) Digispark <-> DATA FS1000A
- GND Digispark <-> GND FS1000A
- Connect some antenna 15cm to FS1000A antenna pin !

You need to install Arduino environment and Digispark packages/libraries : In ARDUINO IDE go to File/Preferences/Additional board manager URL and put this URL : https://raw.githubusercontent.com/ArminJo/DigistumpArduino/master/package_digistump_index.json , then go to Menu Tools/Board and select Digistump AVR Boards / Digispark default 16.5 MHZ

See videos how to clone your key : https://www.youtube.com/watch?v=jziWQA8Wvp4


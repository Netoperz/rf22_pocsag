POCSAG via si4432-based ISM modules
-----------------------------------


This application is designed to send 512 bps POCSAG-messages
using si4432-based ISM transceivers.


There are currently two versions of this application:
- arduino+linux:
This uses a linux-based application to create the pocsag-message
and an arduino to interface with the si4432 tranceiver module

Version: 0.1.0 (2014/03/30)


- arduino 
This uses an arduino to both create POCSAG-message and to interface
with the si4432 based ISM-tranceiver for broadcasting the message.

As the "create pocsag message" code has now been moved to a dedicated
arduino class, the code has been moved to a new location:
https://github.com/on1arf/pocsag


Have fun!

73
Kristoff - ON1ARF

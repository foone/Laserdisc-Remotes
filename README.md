# Laserdisc-Remotes
 Remote codes for the LD-V4300D/LD-V4400 players

# Format
Each file contains a list of buttons and what 32-bit number they transmit. 

# Protocol
All buttons on the remotes are sent using [the NEC encoding](https://github.com/z3t0/Arduino-IRremote/blob/master/ir_NEC.cpp), other than the volume up/down keys. See also: [documentation of how it's encoded](https://www.sbprojects.net/knowledge/ir/nec.php)

Those keys are encoded using some other protocol that I haven't identified, so they are not filled out. 

# Hardware used
The setup from [this article](https://www.circuitbasics.com/arduino-ir-remote-receiver-tutorial/) was used, with an Arduino Uno and a generic IRC receiver.
This uses the [Arduino-IRremote library](https://github.com/z3t0/Arduino-IRremote) to decode the values received. 

# License
This information is placed in the public domain, where possible. 
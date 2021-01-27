# CDP Bin Creator Utility
This is a open source utility tool for the [ClusterDuck Protocol](https://github.com/Call-for-Code/ClusterDuck-Protocol). The reason of building this tool is to create binary files with unique device id's from a master arduino ino file. In turn this helps speed up the process of flashing (CDP Duck ) devices. 

**Warning: This script was written in Bash on linux- So not sure what other platforms this will be compatible with**
If you do happen to find it works with your own system please let me know and if you feel like porting it to other systems please feel free to submit pull-request for that. 

# Pre-Req Install: Arduino-CLI
1. [Install](https://arduino.github.io/arduino-cli/latest/installation/) the Arduino CLI
2. Follow the [Getting Started guide](https://arduino.github.io/arduino-cli/latest/getting-started/) to check out what the CLI can do
3. Browse the [Commands reference](https://arduino.github.io/arduino-cli/latest/commands/arduino-cli/) to see all the available commands
4. Should you have an issue, read the [FAQ](https://arduino.github.io/arduino-cli/latest/FAQ/) page

# How to Run the Utility:
1. Make sure the script is exucatable by running `chmod u+x <script name>`
2. to run: `./<scriptname> -c <Amount of Ducks to Flash> -f <Your Master .INO>`
3. Enjoy flashing your ducks in a FLASH !

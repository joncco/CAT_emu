# CAT_emu
Emulator cartridge for the Dick Smith CAT computer

This is the "Apple II" emulator cartridge for the Dick Smith CAT computer.  Plugging this cartridge in gave 90% Apple II compatibility.  

The cartridge is composed of 2 PCBs connected together with pin headers.  Because I am unsure how else to do it, I have created 2 KiCAD projects, one for each PCB, with a copy of the same schematic in each (more on this later as they aren't quite exactly the same).
 
The first board "A" contains the PCB edge connector, RAM and some logic.  The schematics of this one is as it is from the emulator manual. https://archive.org/details/dsecatec
The second board "B" contains more "bank switching" logic.  When I tried to route this board, it looked like they (Dick Smith?) revised the board and didn't bother updating the manual.  The schematic under the board B directory has more parts.  I will eventually merge the changes together so the schematic for both will be the same.

Credits:
I would like to thank Craig for allowing me to take his emulator cartridge apart for reverse engineering.  
Jongleur for making a very high quality "CAT scan" of the emulator cartridge manual.
Sean for extensive use of the "man cave".

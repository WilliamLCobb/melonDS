# melonDS
DS emulator, sorta


the goal is to do things right and fast, akin to blargSNES (but hopefully better)

but also to have fun coding this shit


LOVE MELONS


NO ASKING ROMZ!! ILLEGAL


license is GPL. don't steal the code.


how to use:

melonDS requires BIOS/firmware copies from a DS. Files required:
 * bios7.bin, 16KB: ARM7 BIOS
 * bios9.bin, 4KB: ARM9 BIOS
 * firmware.bin, 256KB: firmware
 
note: the DS-mode firmware in the 3DS isn't bootable, it only contains the bare minimum to run games.

ROM filename is currently hardcoded, check NDS.cpp for the required filename. this will eventually be addressed.



TODO LIST

 * sorta-UI (ie not hardcode ROM name)
 * 3D engine
 * sound
 * wifi
 * other non-core shit (debugger, graphics viewers, cheat crapo, etc)
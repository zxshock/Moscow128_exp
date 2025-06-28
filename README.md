# Moscow128_exp
Expansion for Moscow-128 ZX clone  
based on "Betadisk Interface 2" found here: https://vtrd.in/book/BDI.ZIP  
Codename: BJAY - B(etadisk)J(oystick)AY  

Update 2025-06-23: My Moscow-128 has been restored to full operation by now - beta testing soon.  
Update 2025-06-28: postponed for now, as I don't understand some parts namely the purpose of A4 on D27 and how CSROM/!CSROM would work on a Moscow128, nor if they're required.
I did do a "mini expansion" with AY + keyboard + power LED on perfboard in the meantime. Maybe I'll do Betadisk/kempston only add-ons before fully commiting to a multi expansion.

Changes:  
Removed: Centronics port as one already exists on port #FB  
Fixed: 4MHz clock for the AY is wrong, will be 1.75MHz (to be taken from D3-3)  
Added: footprint for 40pin AY-3-8910  
Added: Kempston Joystick on port #31  
Added: labels for western 74LSxx logic chips  
Changed: Expansion connector will be DIN 41216 as SNP59-96 are virtually unobtainable outside .ru for me  
Added: optional mixing of beeper output with AY (to be taken from D10-5)  
Added: optional Floppy style 4 pin Molex connector for additional power  
Added: optional 12V generation onboard for VG93 (as in Scorpion) - not required with MB8877  
Added: optional LEDs for 5/12 volts  
Added: optional connector for keyboard address lines + diodes as the  implementation on the board is a mess  

Notes:  
Added "shock_own.lbr"  
Includes symbols/footprints for KR1818VG93, AY-3-8910, AY-3-8912, 74LS193, KT315B, SNP59-96 and DIN41216-96

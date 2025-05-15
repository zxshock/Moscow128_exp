# Moscow128_exp
Expansion for Moscow-128 ZX clone  
based on "Betadisk Interface 2" found here: https://vtrd.in/book/BDI.ZIP  
Currently being recreated in Eagle  

Changes:  
Removed the Centronics port due to the computer already having one on the standard port #FB  
4MHz clock for the AY is wrong, will be 1.75MHz  
--> to be taken from D3-3 on the moscow-128 board and added to the expansion bus connector (pin undecided)  
Add labels for western 74LSxx logic chips  
Add footprint for 40pin AY-3-8910  
Add "VG93 saver" circuit + generate 12V onboard  

Ideas:  
Maybe add mixing for beeper or regenerate on PCB and mix? Likely to be taken from D10-5  
~Jumpers for ABC and ACB Stereo modes?~  
Kempston Joystick interface on port #31 maybe?  
Make the PCB have 5 corners ... since the Moscow-128 is the first computer that implemented the Pentagon 128 timing.  

Notes:  
Added "shock_own.lbr"  
Includes symbols/footprints for KR1818VG93, AY-3-8910, AY-3-8912, 74LS193, KT315B and SNP59-96

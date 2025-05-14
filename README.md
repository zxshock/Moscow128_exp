# Moscow128_exp
Expansion for Moscow-128 ZX clone  
based on "Betadisk Interface 2" found here: https://vtrd.in/book/BDI.ZIP  
Currently being recreated in Eagle  

Changes:  
Removed the Centronics port due to the computer already having one on the standard port #FB  
4MHz clock for the AY is wrong, will be 1.75MHz (unsure whether to take it from the mainboard or generate locally)  
Add labels for western 74LSxx logic chips  

Ideas:  
Add footprint for 40pin AY-3-8910  
Implement "VG93 saver" circuit so the chip doesn't blow up when 12V supply is missing  
-> currently unsure whether I want to generate 12V locally from the 5V supply (like Scorpion or Compact) or have it fed externally.  
Maybe add mixing for beeper or regenerate on PCB and mix?  
Jumpers for ABC and ACB Stereo modes?  
Kempston Joystick interface on port #31 maybe?  
Make the PCB have 5 corners ... since the Moscow-128 is the first computer that implemented the Pentagon 128 timing.  

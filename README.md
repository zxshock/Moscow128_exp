# Moscow128_exp
Expansion for Moscow-128 ZX clone  
based on "Betadisk Interface 2" found here: https://vtrd.in/book/BDI.ZIP  
Currently being recreated in Eagle  
Codename: BJAY - B(etadisk)J(oystick)AY
Still in the process of fixing my vintage Moscow 128, but getting there.

Changes:  
Removed: Centronics port as one already exists on port #FB  
Fixed: 4MHz clock for the AY is wrong, will be 1.75MHz (to be taken from D3-3)  
Added: footprint for 40pin AY-3-8910  
Added: Mix beeper output with AY (to be taken from D10-5)  
Added: ~"VG93 saver" circuit +~ generate 12V onboard (as in Scorpion)  
Added: Kempston Joystick on port #31  
Added: labels for western 74LSxx logic chips  
Added: Connector for keyboard address lines + diodes as the original implementation is rather messy  
Changed: Expansion connector will be DIN 41216 as SNP59-96 are virtually unobtainable outside .ru  

Notes:  
Added "shock_own.lbr"  
Includes symbols/footprints for KR1818VG93, AY-3-8910, AY-3-8912, 74LS193, KT315B, SNP59-96 and DIN41216-96

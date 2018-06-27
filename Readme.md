DOOGEE X5
===========
Device Tree N
------------------

Device Tree for DOOGEE X5.

- MT6580 Chipset
- marshmallow 6.0 (3.18.19 Kernel)
- 5,0" 1280x720 display
- 2200MAh battery capacity
- 1GB RAM

Bug	tracker
---------------
-solved
- [x] Can not connect to hidden WIFI / WPS
- [x] Some apps fast crash (source code needs to be edit)
- [x] Blackscreen after unlock
- [x] FM Radio (with patch)
- [x] GPS with device only (with patch and ramdisk changes) not fully
- [x] battery drain on daily use (changes power profile and some source code need to be edit)
- [x] Video recording inverted color
- [x] Contact import
- [x] Brightness
-open
- [ ] Video recording camera max 5MPx
- [ ] ril is not stable
- [ ] Blackscreen after unlock with nav bar
-
How to git
---------------
- cd ~/android/LOS141
- repo init -u https://github.com/LineageOS/android.git -b cm-14.1
- repo sync -c

Result
---------------

Credits:
pedropereira22@git
seluce@git
ibrahim1973@git
bekriebel@git

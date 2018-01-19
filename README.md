# temp-control
Arduino-based temperature display and controller -- Created by Ling Leng

Revision History:
12/27/2017
- Added first version "Bare Bones Arduino.zip"
- Replaced "Bare Bones Arduino.zip" with new "TempControl V1.0" files which only includes .brd and .sch files
- Added Mini USB power supply part
- Added external oscillator
- Removed ISP-6 header
- Added reset button
- Added voltage regulator circuit

1/1/2018
- Added OLED
- Added .lbr file

1/2/2018
- Created new TempControl.lbr
- Created parts list
- Went through every parts and replaced them with TempControl.lbr
- Replaced ams1117 with L7805C
- Replaced the reset button
- Removed two LEDs
- Changed packages fot some capacitors
- Added frame

1/3/2018
- For U2, Added 0.33uF on Pin1 and 0.1uF on Pin3
- For U1, Added 0.1uF on Pin7 and 1.0uF on Pin20
- Added Diode on Pin1 for J3, Power Pin for J1, and VCC Pin for J4
- Added Green LED as power indicator
- Added a 4-PIN connector for OLED
- Rearranged and Rerouted the whole board

1/8/2018
- Removed power jack
- Removed 5V regulator
- Added 3v regulator
- Added level shifter

1/19/2018
- Added temp sensor
# AMS operation & trouble-shooting, etc
Author: Jun Zhang, Yufang Hao
## 1.	Turning on/off:
### 1.1 Turn on
1.	Verify the inlet is closed.
2.	Press the button of “Pump Box” and “Accessory” for the power supply.
3.	Turn on the diaphragm pump (MD1) using the knob at the front panel. 
4.	After the pressure is below 1 torr, turn on the turbo pumps by selecting “Start All” at the operating box, and let pump 1 to pump 5 reach 100% speed (this percentage should be seen on the screen). This will normally take about 5-20 min due to the different ToF. It is better to check the speed and power of turbo pumps and compare with the previous values.
5.	Turn on the vaporizer heater. Adjust the vaporizer power to keep the temperature at ~ 550 C. This will normally take 10-20 min.
6.	Open DAQ software from PC. Load TPS settings (e.g., menu1.txt) from PC internet browser (“localhost” in the address bar), then click “send all” to apply the pre-set voltages. Verify the filament is on by looking through the window on the right side. Check the temperature after a while, which should reach ~600 C.
7.	Turn on the chopper spinning from the controller (the blue box on TOF, the operational spinning speed is 100~140 Hz due to different setting) and turn on the inlet valve for sampling.
a.	When the chopper position is changed on the software, the chopper should move and the air beam signal should appear.
b.	If the air beam cannot be seen when the servo is moved, it means the servo should be replaced.
8.	Run mass calibration from DAQ.
9.	Click “acquire” from DAQ, then click “acquire” to start data collection. Check the MS AB from the left side, which should be higher than 2.0E+5.

### 1.2 Turn off
1.	Stop acquiring data in DAQ and zero all voltages in TPS.
2.	Close inlet valve.
3.	Turn off chopper spinning.
(above is what we should do for daily standby; below is the steps for totally shut down)
4.	Turn off the heater of vaporizer power by entering 001 or using the knob at the front panel. 
5.	Turn off the turbo pumps by choosing “Stop All”.
6.	After the turbo pumps have fully stopped, close the valve between the MD1 and a turbo pump if one just need AMS shut down for a short period (for example less than 1 day).
7.	Turn off the MD1.
8.	 When the pumps are fully stopped, loose the two screws on the turbo pumps if AMS will have a long distance transport.
9.	Switch off the power supply to “Pump Box” and “Accessory”.



Here is an example of more details of IE calibration []()


























ToFAMS Tuning Instructions

A series of videos can be seen [here](https://support.aerodyne.com/knowledgebase/articles/KA-01306/en-us), account needed.


<iframe src="https://youtu.be/6_qRKD1mRRM" allowfullscreen></iframe>

<iframe  title="YouTube video player" width="480" height="390" src="http://www.youtube.com/watch?v=TheVideoID?autoplay=1" frameborder="0" allowfullscreen></iframe>

with a **youtube** video embedded


## Reference 

[Aerodyne Knowledge Base](https://support.aerodyne.com/)
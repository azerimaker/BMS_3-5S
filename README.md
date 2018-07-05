# BMS 3-5S
3-5S Battery Management System based on TI bq76920 IC and MSP430 uC. The design is largely influenced by the TI's [TIDA-00449](http://www.ti.com/tool/TIDA-00449) reference and LibreSolar's excellent [BMS-5s](https://github.com/LibreSolar/BMS-5s) designs.

## Specs:
- 3-5 Li-ion/Po Cells
- MSP430 Microcontroller for gas gauging, balancing and serial communication
- Load current: 50A (cont.), 100A (peak) (estimated!)

## Demo
- After the modified firmware balancing and status report work fine [(see here)](https://twitter.com/OrkhanAmirAslan/status/1014643359699406849)

## To Do
- Fix issues with battery voltage switching and Pre-Discharge mosfets. 
- Remove soldermask for high current tracks. 

![BMS_v1 PCB Render](/BMS_Docs/bms_v1.png)

![BMS_v1 PCB](/BMS_Docs/bms_v1_PCBs.jpg)

<div align="center">
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

</div>


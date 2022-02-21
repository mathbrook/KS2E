# KS2E
Collection of my projects for Kennesaw Motorsports FSAE's second electric car, the KS2E.
## [BSPD](KS2E-BSPD)
<img src="/KS2E-BSPD/BSPDRender2-15-22.png" width="600">
Safety circuit designed to interrupt the tractive system in case of torque control or braking faults

## Shutdown Circuit
Circuit which carries current to the AIRs(Accumulator Isolation Relays) which must be closed for the tractive system to operate

<img src="/SHUTDOWNCIRCUITKS2E.drawio (3).png" width="600">

## [IMD AMS Latch](KS2E-IMD-AMS-Latch)

<img src="/KS2E-IMD-AMS-Latch/Imd-Ams-Latch.png" width="600">
Independent latching circuits for the IMD and AMS on one PCB

## [Fan Controller](Val's-Fan-Controller)
Teensy-powered PWM fan speed controller for the Ks2e's accumulator.

<img src="/Val's Fan Controller/ValFC.png" width="600">

## [Precharge](KS2E-Precharge)

Smart precharge circuit utilizing voltage to frequency converters and a teensy to monitor precharge voltage curve

<img src="/KS2E-Precharge/Precharge.png" width = 600>

## [Temperature Monitoring Board](KS2E-Accumulator-Temp-Board)

Work in progress, teensy interfacing with several LTC2499 ADCs over i2c and transmitting that data to an Orion BMS 2 over canbus in order to emulate the Orion Thermistor module.

<img src="/KS2E-Accumulator Temp Board/LTC2499TestBoard.png" width = 600>

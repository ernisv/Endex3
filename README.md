# Project "Endex3"
Ender 3 Idex conversion

Prototype:

<p align="center">
<img src="media/ender-full.png" alt="Conversion in reality" width="500" border="2" align="center">
</p>

Idex in action:
[Idex in action](media/idex-in-action.mp4)

## Goals

* fully functional Idex
  * multimaterial printing without excessive filament/print time waste
  * copy mode
  * mirror mode
* no loss of printable area for at least one of the heads
* ooze prevention for idle nozzle
* controlled by Klipper firmware
* footprint width not to exceed 50cm
* reuse of commodity 3d printing parts of Ender3 era

## Additional hardware 

* NEMA17 stepper motor for new toolhead
* GT2 6mm belt - about 90cm
* GT2 pulley for the motor
* GT2 idler
* microswitch for second X endstop
* new toolhead - extruder with stepper, heating block, thermistor, hotend and part cooling fan
* Klipper compatible control board to control:
  * 2 stepper motors - additional X motor, additional extruder
  * control new toolhead's heater
  * control new toolhead's part cooling fans
  * monitor new toolhead's temperature
* additional 24V PSU 200W+ or 550W+ replacement for original PSU to cover additional power needs 
  
## Conversion story
So before all that there was a Creality Ender3 V2, which was a first printer and during many years it morphed little by little to gain more speed, more flowrate, bed levelling, magnetic bed, Klipper.. and still was printing reliably enough to avoid being replaced by anothing more modern :)

But there was still a feature that it missed - multimaterial printing. And in 2025 - year when multimaterial became the norm with all multiplexing filament changers and even proper toolchangers coming, this became a matter of survival for the Ender3..

And the solution for that was one - Idex conversion. Idex is better than filament changers as produces less waste and switches materials much faster and even offers some interesting unique features that even proper toolchangers do not have - copy and mirror modes when single printer essentially is doing work for two :) 

## Details

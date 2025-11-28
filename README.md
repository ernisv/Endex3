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
TBD

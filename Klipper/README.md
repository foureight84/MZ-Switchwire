## Mega Zero Switchwire Klipper config

This configuration utilizes the follwing:
- SKR Mini MZ 1.0 Controller board with TMC2209 drivers
- 220mm BigTreeTech 12v heatbed
- BL Touch
- Custom print head assembly which is a modified and mirrored version of Voron's design. Default Mega Zero X-Axis and Y-Axis homing direction.
- Input shaper enabled. Make sure to run input shaper and pressure advance calibration.
- Stepper motor rotation configuration and current are for 0.9 degree XYZ steppers. (LDO-42STH38-1684MAC)
- Sherpa Mini Direct extruder with Moons (CSE14HRA1L410A-01) 1amp motor.
- Microswiss Hotend

**Make proper adjustments for your steppers**
Stepper current configuration guide: https://docs.vorondesign.com/community/howto/120decibell/calculating_driver_current.html

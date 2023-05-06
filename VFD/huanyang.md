https://wiki.printnc.info/en/electronics/vfd/config

| Param | Val  | Description |
| ----- | ---- | ----------- |
| PD000 | 0    | Parameter lock, 0=unlock |
| PD001 | 0    | Use the front panel for easier debugging   (Set to 2 for RS485 control) |
| PD002 | 1    | Use the front potentiometer (Set to 2 for RS485 control) |
| PD003 | 400  | Main frequency (Note that this is PD003, and is out of order, this is intentional) |
| PD004 | 400  | Base frequency (Note that this is PD004, and is out of order, this is intentional) |
| PD005 | 400  | Max operating frequency (Note that this is PD005 - it is out of numerical order, this appears to matter, follow the ordering here) |
| PD007 | 20   | Min frequency, for the VF curve |
| PD008 | 220  | Max output volt, for a 220V spindle |
| PD009 | 15   | Intermediate voltage on the VF curve |
| PD010 | 8    | Minimum voltage |
| PD011 | 100  | Minimum frequency, the spindle could overheat at lower speed and the spindle does not have torque at low speed |
| PD014 | 8    | Acceleration time, can be lower for faster acceleration |
| PD015 | 8    | Deceleration time, can be lower for faster braking |
| PD141 | 220  | Motor rated voltage. This is for the 220V spindle |
| PD142 | 9    | Motor maximum Amp, its 9A for the 220V spindle |
| PD143 | 2    | Number of poles, 2 for the standard 2.2kW spindle |
| PD144 | 3000 | A value of 3000 = 24k RPM, this is to have the correct RPM on the display of the VFD |


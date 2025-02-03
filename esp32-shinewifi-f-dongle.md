# Registers

| Name | Address Offset (from 0x1000) | Type | Multiplier | Unit |
|------|------------------------|------|------------|------|
| System Status | 0 | uint16_t | 1 | 0: Standby; 1; (No Use); 2: Discharge; 3: Fault; 4: Flash; 5: PV charge; 6: AC charge; 7: Combine charge; 8: Combine charge and bypass; 9: PV charge and bypass; 10: AC charge and bypass; 11: Bypass; 12: PV charge and discharge; |
| PV Voltage | 1 | uint16_t | 0.1 | Volts |
| PV Power | 3 | uint32_t | 0.1 | Watts |
| Buck Converter Current | 7 | uint16_t | 0.1 | Amps |
| Output Watts | 9 | uint32_t | 0.1 | Watts |
| Output VA | 11 | uint32_t | 0.1 | VA |
| AC Charger Watts | 13 | uint32_t | 0.1 | Watts |
| AC Charger VA | 15 | uint32_t | 0.1 | VA |
| Battery Voltage | 17 | uint16_t | 0.01 | Volts |
| Battery SOC | 18 | uint16_t | 1 | Percent |
| Bus Voltage | 19 | uint16_t | 0.1 | Amps |
| AC Input Voltage | 20 | uint16_t | 0.1 | Volts |
| AV Input Frequency | 21 | uint16_t | 0.01 | Hertz |
| AC Output Voltage | 22 | uint16_t | 0.1 | Volts |
| AC Output Frequency | 23 | uint16_t | 0.01 | Hertz |
| Inverter Temperature | 25 | uint16_t | 0.1 | Degrees C |
| DC to DC Converter Temperature | 26 | uint16_t | 0.1 | Degrees C |
| Load Percentage | 27 | uint16_t | 0.1 | Percent |
| Buck Converter Temperature | 32 | uint16_t | 0.1 | Degrees C |
| Output Current | 34 | uint16_t | 0.1 | Amps |
| Inverter Current | 35 | uint16_t | 0.1 | Amps |
| AC Input Watts | 36 | uint32_t | 0.1 | Watts |
| AC Input VA | 38 | uint32_t | 0.1 | VA |
| PV Energy Today | 48 | uint32_t | 0.1 | kWh |
| PV Energy Total | 50 | uint32_t | 0.1 | kWh |
| AC Charger Today | 56 | uint32_t | 0.1 | kWh |
| AC Charger Total | 58 | uint32_t | 0.1 | kWh |
| Battery Discharge Today | 60 | uint32_t | 0.1 | kWh |
| Battery Discharge Total | 62 | uint32_t | 0.1 | kWh |
| AC Charger Battery Current | 68 | uint16_t | 0.1 | Amps |
| AC Discharge Watts | 69 | uint32_t | 0.1 | Watts |
| AC Discharge VA | 71 | uint32_t | 0.1 | VA |
| Battery Discharge Watts | 73 | uint32_t | 0.1 | Watts |
| Battery Discharge VA | 75 | uint32_t | 0.1 | VA |
| Battery Watts | 77 | int32_t | 0.1 | Watts |
| Fan1 | 82 | uint16_t | 1 | Percent |
| Fan2 | 83 | uint16_t | 1 | Percent |

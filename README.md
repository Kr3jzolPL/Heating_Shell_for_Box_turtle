# Heating-Shell-for-Box-turtle
Controllable heater for box turtle enclosure using your printer with macros for automatic maintain humidity or to keep dry your filament 
***
Cool Functions
***
- Gives status of chamber temp and time remaining in console
- Custom Temp, Duration (In hours), At which temperature timer starts in order to shut down heating (Like a dryer) using "Heat SOAK" Macro
- One click drying using templates
- Can maintain humidity in chamber (Turns on then off heater if humidity is below X%) using "Humidity Soak Auto"
- Don't interfere with active printing
- Easily wired if BTIO is installed using Microfit 4 pin for power and Can
- Compatible with "Voron skirt inserts" for multiple Power / CAN combination
- All macro temperature and humidity settings can be easily edited in macro
- Can be canceled in any time
***

***
***
Warnings!!!
- NOT SUITABLE FOR 230V TOO DANGEROUS IF WIRED BADLY !!!!!!!!!
- If using ABS don't go over 90C at heater beacause you can melt hot side of the system!!
- At 80C heater and 50% power i am getting 45C in chamber, better insulation = better performance
- You might need to change PSU 150Watt Heater at 50% power consume about 100 Watts  , i have MeanWell RSP 500-24V from old Ender 5 Plus, works good
***
***

***
***
Disclaimer :
- I used bigger wires for future proof, you might get away only with Microfit 4 pin for power and canbus but i highly recommend to use 18 AWG cable for this setup,
- i don't recommend to use multiple heating units with that config
***
***

Bom
| Name                    | Quantity | Remarks                                                                                  |
|-------------------------|:----------:|------------------------------------------------------------------------------------------|
| BTT EBB36 | 1        | Mainboard for the system.                        |
| 400w 15A Mosfet        | 1        | Powering the heater, you will need to drill 3mm holes for fixing it                      |
| M3 Heated insert | 12       | Heated inserts for fixing stuff.                                                                 |
| M3 Screws | 12       | for Fixing stuff in place.                                                                 |
| PTC Heater 150 watt        | 1        | Main heater 24VDC Heater +24VDC fan, don't even try to use 230V !!                  |
| Thermistor for heater   | 1        | Standard thermistor i used DollaTek HT-NTC100K                             |
| BME680 / BME280 | 1       | Sensor for humidity and temp in chamber.                                                                 |
| JST PH 2.0 4 Pin | 1       | For connecting the BME sensor                                                                 |
| Microfit 4 pin | 2       | 18 AWG minimum for that config for power and can, second one can be used to add additional turtle or heating unit    |
| Wago 3 pin | 2       | CanBus Distribution   |
| Wago 5 pin | 2       | Power Distribution   |
| Spacers | 2 per board   | Spacers for EBB and Mosfet they are in stl folder    |

If using inserts for power and canbus
***
| Name                    | Quantity | Remarks                                                                                  |
|-------------------------|:----------:|------------------------------------------------------------------------------------------|
| XT60H cable to 2 pin | 1       | printer main power 12awg                                                                 |
| Microfit 4 pin | 1       | if using Microfit inserts only for canbus                                                                 |
| XT60H with cable | 1       | Power input for heater and EBB 12awg                                                                |
| Wago 3 pin | 4       | Power Distribution and Can   |
***
Printing :
- Print files at least in ABS, hot and cold side can be printed using much more temperature ressistant filament but i didn't tested it
- Your printer need to be properly calibrated there are tight tolerances
***
Disclaimer :
- NO, Pla won't work and will melt
***
Supports :
- Use tree supports for saving the filament in Side Wall, Cold Side and Hot side
***
MMU Support :
- Side Wall and cover can be printed using a MMU system, you need to add colors in your slicer

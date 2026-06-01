# Flight Gear - Airbus A320-family - Simple Guide

This is a simple guide designed to help you set up and get started with the Airbus A320-family in FlightGear. Whether you want to understand cockpit layouts, practice standard procedures, or just enjoy the mechanics of flying this advanced airliner, this reference will walk you through the essential steps.

> ⚠️ **Note:** **Do not** use this guide, its contents, or the simulator for real-world aviation, flight training, or real aircraft operations! This is strictly for entertainment and desktop flight simulation purposes.

## Pre-Requisites

Before diving into the cockpit procedures, ensure you have the following components installed and ready:

1. **FlightGear Flight Simulator:** Download and install the simulator from the official website: [FlightGear Official Website](https://www.flightgear.org).
2. **Airbus A320-family Aircraft Pack:** Install the A320-family aircraft from the game catalog. 

## Simple Guide (Checklist)

This section contains a streamlined checklist designed to guide you through a complete flight, from cold and dark to shutdown. It is meant to be used as a practical, step-by-step reference that you can easily follow along with during a single flight or across multiple flight sessions.

### 1. External Power

1. Access `Aircraft > Ground Services` menu and select `Enable External Power Box`.
2. Verify that `EXT PWR` button displays the `AVAIL` light in green.
3. Press `EXT PWR` switch.
4. Press `BAT 1` and `BAT 2` switches.

### 2. Cockpit Lights

1. Adjust **Overhead** `INTEG LT` and `DOME` swithes as your preference.
2. Adjust **FCU** `INTEG LT` as your preference (knob located under the FCU panel).
3. Adjust **Main Panel** `INTEG LT` as your preference.
4. Adjust **Main Panel** `FLOOD LT` lights (pilot and co-pilot knobs) as your preference.

### 3. ADIRS

1. Turn `IR1`, `IR2` and `IR3` selectors to `NAV`.

### 4. APU

1. Turn on `APU MASTER` switch.
2. Turn on `APU START` switch and wait for `AVAIL` green light.
3. Turn on `APU BLEED` switch.
4. Turn on `PACK 1` and `PACK 2` switches (lights off).
5. Set `PACK FLOW` to your preference.
6. Adjust `COCKPIT`, `FWD CABIN`, and `AFT CABIN` selectors to your preference (12 o'clock = 24°C).
7. Turn off `EXT PWR` switch (light changes back to `AVAIL` green).
8. Access the menu `Aircraft > Ground Services` and deselect `Enable External Power Box`.

### 5. Lights and Signs

1. Turn `STROBE` light switch to `AUTO`.
2. Turn on `WING` light switch.
3. Set `NAV & LOGO` light switch to `2`.
4. Turn `SEATBELTS` and `NOSMOKING` switches to `ON`.

### 6. Boarding Services

1. Access the menu `Aircraft > Ground Services`.
2. Select `Front Left` and `Rear Left` stairways.
3. Select `Enable Baggage Ramp`.
4. Select `Enable Catering Truck` and `Enable Rear Catering Truck`.
5. Click on `Toggle Catering` to raise the catering trucks.

### 7. MCDU Initialization

1. Access the **MCDU**.
2. Press the `MCDU MENU` button.
3. Select `FMGC` system and wait for response.
3. Press the `INIT` button.
4. Enter the departure/arrival airports using the format `{ICAO}/{ICAO}` in scratchpad (ex: `SBGR/SBGL`).
5. Press the `FROM/TO` button.
6. Press `IRS INIT` > `ALIGN ON REF` > `CONFIRM ALIGN` buttons.
7. Set `FLT NBR` with your choice (ex: `AB1234`).
8. Set `COST INDEX` to `50` (balanced).
9. Set `CRZ FL` to: `200` (20.000 ft) for small trips; `300` (30.000 ft) for medium trips; `400` (40.000 ft) for long trips.

### 8. MCDU - Fuel Prediction

1. From the `INIT` page, navigate to the `INIT 2` page by pressing the `->` button.
2. Press `ZFW/ZFWCG` to calculate the zero fuel weight automatically.
3. Press `FUEL PLANNING` and wait for prediction.
4. Press `BLOCK CONFIRM` to confirm.

### 9. MCDU - Take Off Performance

1. Press the `PERF` button.
2. Set `V1`, `VR` and `V2` speeds based on the airplane weight (default: `130`, `135`, `140`).
3. Set `FLAPS/THS` with the take off flaps level and trim (default: `1/UP0.1`).

### 10. Runway & ILS Research

1. Open the simulator map at `_Equipament > Map_`.
2. Use the template `DEP: ___ ARR: ___ CRS: ___ FRQ: ___.__ INV: ___` to annotate the information from the next steps.
3. Navigate to the departure airport and annotate the departure `RUNWAY CODE`.
4. Navigate to the destination airport and annotate the arrival `RUNWAY CODE`, `ILS COURSE` and `ILS FREQUENCY`.
5. Calculate the `INVERSE COURSE` and annotate it with the following formula: if course <= 180, do `{COURSE} + 180`. If course > 180, do `{COURSE} - 180`.
6. Check if everything was annotated (ex: `DEP: 27L ARR: 15 CRS: 149 FRQ: 110.30 INV: 329`).

### 11. MCDU - Flight Plan Departure

1. Press the `F-PLN` button.
2. Select the departure airport (ex: `SBGR`).
3. Press `DEPARTURE`.
4. Select the `RUNWAY CODE` for departure (check annotations).
5. Save by pressing `TMPY F-PLN` > `TMPY INSERT *`.

### 12. MCDU Flight Plan Arrival

1. Select the destination airport (ex: `SBGL`)
2. Press `ARRIVAL`
3. Select the `RUNWAY CODE` for landing (check annotations).
4. Save by pressing `TMPY F-PLN` > `TMPY INSERT *`

### 13. MCDU Flight Plan Alignment Waypoint

1. Select the departure airport (ex: `SBGR`).
2. Type into the scratchpad the following format: `{ICAO}/{INV}/40` (check annotations) (ex: `SBGL/329/40`).
3. Press `NEXT WPT`.
4. Save by pressing `TMPY INSERT *`.

### 14. MCDU - Flight Plan Clearing

1. Press the `CLR` button (make sure the `CLR` text was inserted into the scratchpad).
2. Select the `F-PLN DISCONTINUITY` left button to remove the discontinuity point.
3. Repeat the steps above until all `F-PLN DISCONTINUITY` messages are cleared.

### 15. MCDU - Radio Navigation 

1. Press the `RAD NAV` button.
2. Set the `ILS/FREQ` with the `ILS FREQUENCY` information (check annotations).
3. Set the `CRS` (below `ILS/FREQ`) with the `ILS COURSE` information (check annotations).

### 16. Route Review

1. Open the simulator map at `_Equipament > Map_`.
2. Review your flight plan route to ensure everything is correct and there are no anomalies.

### 17. FCU

1. Set the `ALT` knob with the **MCDU** cruise altitude and **PUSH** it (verify that the white dot appears next to the altitude display).
2. **PUSH** the `SPD` knob to engage Managed Speed mode.
3. **PUSH** the `HDG` knob to engage Managed Lateral Navigation.

### 18. Disable Boarding Services And Gear Chocks

1. Access the menu `Aircraft > Ground Services`.
2. Deselect `Front Left` and `Rear Left` stairways.
3. Deselect `Enable Baggage Ramp`.
4. Deselect `Enable Catering Truck` and `Enable Rear Catering Truck`.
5. Deselect `Enable Gear Chocks`.

### 19. Request Pushback

1. Access the menu `Aircraft > Pushback`.
2. Select `Connect`.
3. Click the `Enter` button and setup a puckback route.
4. Release the `PARK BRK` (shortcut: `SHIFT + B`).
5. Click the `Start` button to start the pushback and wait the maneuver is completed.
6. Deselect `Connect`.
7. Turn on `PARK BRK` (shortcut: `SHIFT + B`).

### 20. Engines Startup

1. Turn on fuel pumps `R TK PUMPS` and `CTR TK` (lights off).
2. Turn on the `BEACON` light switch to signalize that the engines are starting.
3. Set the `ENG MODE` selector to `IGN/START`.
4. Turn on `ENG 2` master switch and wait for engine stabilization (engine 2 first to provide primary hydraulic pressure).
5. Turn on `ENG 1` master switch and wait for engine stabilization.
6. Set the `ENG MODE` selector back to `NORM` when both engines are stable.
7. Turn off `APU MASTER` switch.

### 21. Taxi

1. Access the menu `Aircraft > Announcements` and trigger `Cpt - Welcome`.
2. Turn the `NOSE` light switch to `TAXI`.
3. Set the `AUTO BRK` to `MAX`.
4. Adjust the `PITCH TRIM` wheel to match MCDU target (default: `UP0.1`).
5. Set the `FLAPS` to takeoff position (default: `1`).
6. Arm the `SPEED BRAKE` (verify white band is visible).
7. Press the `T.O CONFIG` button to test takeoff configuration.
8. Check the `ECAM` and confirm it displays `T.O CONFIG NORMAL` in green.
9. Release `PARK BRK` (shortcut: `SHIFT + B`).
10. Smoothly advance thrust levers to taxi speed.
11. Taxi the aircraft to the takeoff runway (use `TAB + HOLD LEFT MOUSE BUTTON` to control, and `B` to break).
11. Access the menu `Aircraft > Announcements` and trigger `Cpt - Doors Check`.

### 22. Before Takeoff

1. At the runway holding point, turn on `PARK BRK` (shortcut: `SHIFT + B`)
2. Turn on the `RWY TURN OFF` light switch.
3. Set the `NOSE` light switch to `T.O`.
4. Turn on the `LAND` lights switches.
5. Set the `TCAS` switch to `TA/RA`.
6. Press the `ALL` button on the `CALLS` panel to advise cabin crew.
7. Access the menu `Aircraft > Announcements` and trigger `Cpt - Prepare for Takeoff`.

### 23. Takeoff

1. Release the `PARK BRK` (shortcut: `Shift + B`).
2. Align the aircraft perfectly with the runway centerline.
3. Advance `THRUST LEVERS` smoothly to **50%**, wait for engines to stabilize, then push to `TOGA` (shortcut: `F`).
4. Maintain runway centerline using rudder pedals (`TAB + HOLD LEFT MOUSE BUTTON`)
5. At `VR` speed (around **135 knots**), gently pull the joystick back to rotate the aircraft.

### 24. Climb

1. Set the `LANDING GEARS` lever to `UP`.
2. Set the `FLAPS` to `0`.
3. Climb the airplane manually until `LVR CLB` is displayed on `PFD`.
4. Stabilize the airplane, then move `THRUST LEVERS` to `CL` (shortcut: `SHIFT + F`).
5. Turn on `AP1` to let the **FMGC** fly the programmed route automatically.
6. Verify `A/THR` is active.
7. Desarm the `SPEED BRAKE`.
8. Turn off the `RWY TURN OFF`, `LAND` and `NOSE` light switches.
9. Press the `BARO` knob on the `FCU` to set `STD`.

### 25. Cruise

1. When `ALT CRZ` is displayed on the `PFD`, turn off the `SEAT BELTS` sign (if the flight is smooth and free of turbulence).
2. Enjoy your flight!
3. At **40 NM** before the **Alignment Waypoint**, set the `ALT` knob on the  **FCU** to **10.000 ft**, and **PULL** it (`SHIFT + LEFT CLICK`).

### 26. Alignment Waypoint

1. Ensure that the **Alignment Waypoint** was reached at **10.000 ft** altitude.
3. Press the `BARO` knob on the **EFIS** to switch from `STD` to the local QNH.
4. Turn on the `LAND` and `RWY TURN OFF` light switches.
5. Set the `NOSE` light switch to `TAXI`.
6. Set the `AUTO BRK` to `LOW` or `MED` (depending on runway length).
7. Arm the `SPEED BRAKE` (verify white band is visible).

### 27. Approaching

1. Turn on the `SEAT BELTS` sign.
2. Access the menu `Aircraft > Announcements` and trigger `Cpt - Prepare for Landing`.
3. Turn on the `ILS` audio reception on the **RMP** to monitor the `ILS` code transmission (morse code).
4. Activate the `LS` button in the **EFIS** panel to display the `ILS` localizer and glideslope scales in `PFD`.
5. Set the approaching altitude (around **3000 ft** relative to the destination airpoirt) in `ALT` knob and **PULL** it.
6. While descending, set `FLAPS` from `1` to `FULL` waiting speed stabilization on each step.
7. Lower the `LANDING GEARS` lever to `DOWN`.
8. When both (horizontal and vertical) purple `LS` diamonds are displayed on the `PFD`, press the `APPR` button on the `FCU`.
9. Wait and ensure  the glide slope `G/S` gets captured (turns green in `PFD`).

### 28. Landing

1. When altitude reaches **100 ft**, set the `THRUST LEVERS` to `IDLE` (shortcut: `E`).
2. Disable the `AP1` (press `SHIFT + D`) and start controlling the airplane manually (shortcut: `TAB`).
3. Smoothly pull back the joystick to execute the flare.
4. Upon touchdown, apply `MAX REVERSE` thrust (press `DELETE`) and use `B` for manual breaking if needed.
5. When landing done, cancel reverse thrust (press `DELETE` again).
6. Transition smoothly to the exit of the runway (use `TAB + HOLD LEFT MOUSE BUTTON` to control, and `B` to break).
7. Drive the airplane to the airport gate.

### 29. Taxi To Gate

1. During the taxi, set the `FLAPS` to `0`.
2. Desarm the `SPEED BRAKE`.
3. Turn on `APU MASTER` switch.
4. Turn on `APU START` switch and wait for `AVAIL` green light.

### 29. Parking At the Gate

1. When reached the gate, set `PARK BRK` to `ON` (shortcut: `Shift + B`).
2. Set `THRUST LEVERS` to `IDLE` (shortcut: `E`).
3. Turn off `RWY TURN OFF`, `LAND` and `NOSE` light switches.
4. Set `TCAS` to `STBY`.
5. Check `APU START` switch displays `AVAIL` green light, then turn on `APU BLEED` switch.
6. Move `ENG 1` and `ENG 2` master switches to `OFF`.
7. Turn off `BEACON` light swtich.
8. Turn off `SEATBELTS` sign swtich.

--------------------------------------------------

### 30. Enable Boarding Services and Gear Chocks

1. Enable gear chocks (Aircraft > Ground Services > Landing Gear)
2. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
3. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
4. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

### 31. Shut Down (If Final Flight)

2. If this is the final flight of the day, proceed with the aircraft decommissioning below:
3. Turn off wing fuel pumps `R TK PUMPS 1` and `R TK PUMPS 2` in `ENG 1` and `ENG 2` (lights OFF)
4. Turn off central fuel pumps `L XFR` and `R XFR` in `CTR TK` (if applicable)
5. Turn off `APU MASTER SW`
6. Done

### 32. Next Steps (If Post Flight)

1. If a turnaround flight is planned, follow the steps below
2. Enable fuel truck (_Aircraft > Ground Services > Fuel_)
3. Add fuel (Avg: 13.000 Lbs)
4. Disable fuel truck (_Aircraft > Ground Services > Fuel_)
5. Jump to: **7. MCDU - Initialization (INIT)** section.

## Glossary

- `A/THR`: Automatic Throttle
- `ADIRS`: Air Data Inertial Reference System
- `AFT`: Rear
- `ALT`: Altitude
- `ALT CRZ`: Cruise Altitude
- `AP1/AP2`: Autopilot 1 / Autopilot 2
- `APU`: Auxiliary Power Unit
- `APU BLEED`: Pneumatic Air
- `AUTO BRK`: Automated Hydraulic Braking System
- `AVAIL`: Available
- `BARO`: Barometric Altitude
- `BAT`: Battery
- `BEACON`: Red Beacon Lights (Anti-Collision and Engines Running Indicator)
- `CL`: Climb
- `CRS`: Course
- `CRZ FL`: Cruise Flight Level
- `CTR TK`: Center Tank Pumps
- `DIST`: Distance
- `ECAM`: Electronic Centralized Aircraft Monitor
- `EFIS`: Electronic Flight Instrument System
- `ENG`: Engine
- `EXT PWR`: External Power
- `F-PLN`: Flight Plan
- `FCU`: Flight Control Unit
- `FLAPS`: Wing Trailing Edge Panels (Used for lift at low speeds)
- `FLOOD LT`: Flood Lights
- `FLT NBR`: Flight Number
- `FMGC`: Flight Management and Guidance Computer
- `FWD`: Front
- `HDG`: Heading
- `ICAO`: International Civil Aviation Organization
- `IGN`: Ignition
- `ILS`: Instrument Landing System
- `INTEG LT`: Integral Lights
- `IR`: Inertial Reference
- `LSK`: Line Select Key
- `LVR CLB`: Lever Climb
- `MCDU`: Multifunction Control and Display Unit
- `N1`: Rotational Speed (Low-Pressure turbine)
- `NAV`: Navigation
- `NM`: Nautical Miles
- `NORM`: Normal
- `OVHD`: Overhead
- `PACK`: Pressurization Air Conditioning Kit
- `PARK BRK`: Park Brake
- `PERF`: Performance
- `PFD`: Primary Flight Display
- `R TK PUMPS`: Right Tank Pumps
- `RAD NAV`: Radio Navigation
- `RMP`: Radio Management Panel
- `RWY TURN OFF`: Runway Turnoff Lights
- `SPEED BRAKE`: Wing Spoilers
- `SPD`: Speed
- `STD`: Standard
- `STROBE`: Strobe Wing Lights
- `T.O`: Takeoff
- `TA/RA`: Traffic Advisory / Resolution Advisory
- `TCAS`: Traffic Alert and Collision Avoidance System (Transponder)
- `THS`: Trimmable Horizontal Stabilizer
- `TMPY`: Temporary
- `TOGA`: Takeoff/Go-Around
- `V1/VR/V2`: Decision Speed / Rotation Speed / Takeoff Safety Speed
- `WING`: Wing Lights (Illuminate the wing leading edge for ice inspection)
- `ZFW/ZFWCG`: Zero Fuel Weight / Zero Fuel Weight Center of Gravity

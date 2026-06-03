# Flight Gear - Airbus A320-family - Simple Guide

This is a simple guide designed to help you set up and get started with the Airbus A320-family in FlightGear. Whether you want to understand cockpit layouts, practice standard procedures, or just enjoy the mechanics of flying this advanced airliner, this reference will walk you through the essential steps. The guide focuses entirely on **IFR (Instrument Flight Rules)** operations, specifically walking you through automated navigation management and precision **ILS (Instrument Landing System)** landings, ensuring you learn how to fully utilize the aircraft's advanced instrumental resources from takeoff to touchdown.

> ⚠️ **Note:** **Do not** use this guide for real-world aviation, flight training, or real aircraft operations! This is strictly for entertainment and desktop flight simulation purposes.

## Pre-Requisites

Before diving into the cockpit procedures, ensure you have the following components installed and ready:

1. **FlightGear Flight Simulator:** Download and install the simulator from the official website: [FlightGear Official Website](https://www.flightgear.org).
2. **Airbus A320-family Aircraft Pack:** Install the A320-family aircraft from the game catalog.

## Preparation

1. Copy the form template below to use as a guide for your annotations.

```
From/To..........: ____/____
Departure Runway.: ___
Arrival Runway...: ___
Inverse Course...: ___
ILS Course.......: ___
ILS Frequency....: ___.__
```

2. Annotate the `From` and `To` airport **ICAOs** (International Civil Aviation Organization) codes (ex: `SBGR/SBGL`).
3. Access _Equipament > Map_.
4. In the `Display:` menu, make sure the `Data` checkbox is enabled.
5. Navigate to **departure airport** and annotate the departure `Departure Runway` (check notes below). 
6. Navigate to **destination airport** and annotate the arrival `Arrival Runway Code` and `Inverse Course` (check notes below).
7. Navigate to the beggining of the arrival runway **ILS Feather** and annotate the `ILS Course` and `ILS Frequency` (check notes below).
8. Ensure the template was full filled and proceed to the **Flight Guide**.

> The `Departure Runway` and `Arrival Runway` are displayed in a information box over the airport runway (ex: `09L/27R`). Select the left or the right runway as your preference (ex: `09L`).

> The `Inverse Course` is displayed in a information box over the airport runway, under the runway information (ex: `096/276`). Get the opposite number of the selected runway (ex: `276`).

> The `ILS Course` and `ILS Frequency` are displayed at the beggining of the "ILS feather", in a information box (ex: `276 - 111.90MHz`). For this example, the course is `276` and the frequency is `111.90` .

## Flight Guide

### 1. External Power

1. Access _Aircraft > Ground Services_ and select `Enable External Power Box`.
2. In **Overhead**, Verify `EXT PWR` switch displays `AVAIL` in green.
3. Press `EXT PWR` switch.
4. Turn on `BAT 1` and `BAT 2` switches (lights off).

### 2. Cockpit Lights

1. Adjust **Overhead** `OVHD INTEG LT` and `DOME` light switches as your preference.
2. Adjust **FCU** `INTEG LT` light switch as your preference (knob located under the FCU panel).
3. Adjust **Main Panel** `INTEG LT` and `FLOOD LT` light switches as your preference.

### 3. ADIRS

1. In **Overhead**, turn `IR1`, `IR2` and `IR3` selectors to `NAV`.

### 4. APU

1. Turn on `APU MASTER` switch.
2. Turn on `APU START` switch and wait for `AVAIL` green light.
3. Turn on `APU BLEED` switch.
4. Turn on `PACK 1` and `PACK 2` switches (lights off).
5. Set `PACK FLOW` selector to your preference.
6. Adjust `COCKPIT`, `FWD CABIN`, and `AFT CABIN` selectors to your preference (**12 o'clock = 24°C**).
7. Turn on `CREW SUPPLY` switch (light off).
8. Turn off `EXT PWR` switch (light changes back to `AVAIL` green).
9. Access _Aircraft > Ground Services_ and deselect `Enable External Power Box`.

### 5. Lights and Signs

1. Set `STROBE` light switch to `AUTO`.
2. Turn on `WING` light switch.
3. Set `NAV & LOGO` light switch to `2`.
4. Turn on `SEATBELTS` and `NOSMOKING` light switches.

### 6. Departure Boarding Services

1. Access _Aircraft > Ground Services_.
2. Select `Front Left` and `Rear Left` stairways.
3. Select `Enable Baggage Ramp`.
4. Select `Enable Catering Truck` and `Enable Rear Catering Truck`.
5. Click on `Toggle Catering` to raise the catering trucks.

### 7. MCDU Initialization

1. Access **MCDU**.
2. Select `FMGC` system and wait for response.
3. Press `INIT` button.
4. Type `From/To` airports and press `FROM/TO` button (check annotations).
5. Press `IRS INIT` > `ALIGN ON REF` > `CONFIRM ALIGN` buttons.
6. Set `COST INDEX` to `50` (balanced).
7. Set `CRZ FL` to: `200` (20000 ft) for small trips; `300` (30000 ft) for medium trips; `400` (40000 ft) for long trips.

### 8. MCDU - Fuel Prediction

1. From `INIT` page, navigate to the `INIT 2` page by pressing the `->` button.
2. Press `ZFW/ZFWCG` to calculate the zero fuel weight automatically.
3. Press `FUEL PLANNING` and wait for prediction.
4. Press `BLOCK CONFIRM` to confirm.

### 9. MCDU - Flight Plan Departure

1. Press `F-PLN` button.
2. Select departure airport (ex: `SBGR`).
3. Press `DEPARTURE`.
4. Select `RUNWAY CODE` for departure (check annotations).
5. Save by pressing `TMPY F-PLN` > `TMPY INSERT *`.

### 10. MCDU - Flight Plan Arrival

1. Select destination airport (ex: `SBGL`).
2. Press `ARRIVAL`.
3. Select `RUNWAY CODE` for landing (check annotations).
4. Save by pressing `TMPY F-PLN` > `TMPY INSERT *`

### 11. MCDU - Flight Plan Alignment Waypoint

1. Select the `F-PLN DISCONTINUITY` left button.
2. Type into the scratchpad the following format: `{To}/{Inverse Course}/50` (check annotations) (ex: `SBGL/329/50`).
3. Press `NEXT WPT`.
4. Save by pressing `TMPY INSERT *`.

### 12. Route Review

1. Access _Equipament > Map_.
2. Review your flight plan route to ensure everything is correct and there are no anomalies.

### 13. MCDU - Flight Plan Clearing

1. Press `CLR` button (make sure the `CLR` text was inserted into the scratchpad).
2. Select `F-PLN DISCONTINUITY` left button to remove the discontinuity point.
3. Repeat the steps above until all `F-PLN DISCONTINUITY` messages are cleared.

### 14. MCDU - Radio Navigation 

1. Press `RAD NAV` button.
2. Set `ILS/FREQ` with the `ILS Frequency` information (check annotations).
3. Set `CRS` (below `ILS/FREQ`) with the `ILS Course` information (check annotations).

### 15. MCDU - Take Off Performance

1. Press `PERF` button.
2. Set `V1`, `VR` and `V2` speeds based on the airplane weight (default: `130`, `135`, `140`).
3. Set `FLAPS/THS` with the take off flaps level and trim (default: `1/UP0.1`).

### 16. FCU

1. View the **FCU (Flight Control Unit)**.
2. Set `ALT` knob with the **MCDU** cruise altitude and **PUSH** it.
3. **PUSH** the `SPD` knob to engage **Managed Speed Mode** (display shows: `---`).
4. **PUSH** the `HDG` knob to engage **Managed Lateral Navigation** (display shows: `---`).

### 17. Disable Boarding Services

1. Access _Aircraft > Ground Services_.
2. Deselect `Enable Gear Chocks`.
3. Deselect `Front Left` and `Rear Left` stairways.
4. Deselect `Enable Baggage Ramp`.
5. Deselect `Enable Catering Truck` and `Enable Rear Catering Truck`.

### 18. Request Pushback

1. Access _Aircraft > Pushback_.
2. Select `Connect`.
3. Click `Enter` button and setup the puckback route.
4. Release `PARK BRK` (shortcut: `SHIFT + B`).
5. Click `Start` button to start the pushback and wait the maneuver is completed.
6. Deselect `Connect`.
7. Turn on `PARK BRK` (shortcut: `SHIFT + B`).

### 19. Engines Startup

1. In **Overhead**, turn on fuel pumps `R TK PUMPS` and `CTR TK` (lights off).
2. Turn on `BEACON` light switch to signalize that the engines are starting.
3. In **Main Panel**, set `ENG MODE` selector to `IGN/START`.
4. Turn on `ENG MASTER 2` switch and wait for engine stabilization (**engine 2 first** to provide primary hydraulic pressure).
5. Turn on `ENG MASTER 1` switch and wait for engine stabilization.
6. Set `ENG MODE` selector back to `NORM` when both engines are stable.
7. Turn off `APU MASTER` switch.

### 20. Taxi

1. Access _Aircraft > Announcements_ and trigger `Cpt - Welcome`.
2. Turn `NOSE` light switch to `TAXI`.
3. Set the `AUTO BRK` switch to `MAX`.
4. Adjust the `PITCH TRIM` wheel to match **MCDU** target (default: `UP0.1`).
5. Set `FLAPS` to takeoff position (default: `1`).
6. Arm `SPEED BRAKE` (verify white band is visible).
7. Press `T.O CONFIG` button to test takeoff configuration.
8. Check **ECAM** and confirm it displays `T.O CONFIG NORMAL` in green.
9. Release `PARK BRK` (shortcut: `SHIFT + B`).
10. Smoothly advance thrust levers to taxi speed (shortcut: `PG UP`).
11. Taxi the aircraft to the takeoff runway (use `TAB + HOLD LEFT MOUSE BUTTON` to control, and `B` to break).
12. During taxi, access _Aircraft > Announcements_ and trigger `Cpt - Doors Check`.

### 21. Before Takeoff

1. At the runway holding point, turn on `PARK BRK` (shortcut: `SHIFT + B`)
2. Turn on `RWY TURN OFF` light switch.
3. Turn on `LAND` lights switches.
4. Set `NOSE` light switch to `T.O`.
6. Set `TCAS` switch to `TA/RA`.
7. Press `ALL` button on the `CALLS` panel to advise cabin crew.
8. Access _Aircraft > Announcements_ and trigger `Cpt - Prepare for Takeoff`.

### 22. Takeoff

1. Release `PARK BRK` (shortcut: `Shift + B`).
2. Align the aircraft perfectly with the runway centerline.
3. Advance `THRUST LEVERS` smoothly to **50%** (shortcut: `PG UP`)
4. Push the `THRUST LEVERS` to `TOGA` (shortcut: `F`).
5. Maintain runway centerline using rudder pedals (shortcut: `TAB + HOLD LEFT MOUSE BUTTON`).
6. At `VR` speed (around **135 knots**), gently pull the joystick back to rotate the aircraft (shortcut: `TAB`).

### 23. Climb

1. Set `LANDING GEARS` lever to `UP`.
2. Set `FLAPS` to `0`.
3. Climb the airplane manually until `LVR CLB` is displayed on **PFD**.
4. Stabilize the airplane, then move `THRUST LEVERS` to `CL` (shortcut: `SHIFT + F`).
5. Turn on `AP1` to let the **FMGC** fly the programmed route automatically.
6. Verify `A/THR` is active.
7. Desarm the `SPEED BRAKE`.
8. Turn off `RWY TURN OFF`, `LAND` and `NOSE` light switches.
9. Press `BARO` knob on the **EFIS** to switch from local QNH to `STD`.

### 24. Cruise

1. When `ALT CRZ` is displayed on the **PFD**, turn off the `SEATBELTS` sign (if the flight is smooth and free of turbulence).
2. Follow the distance for the **Alignment Waypoint** from the **ND** (Navigation Display).
3. Enjoy your flight!

### 25. Top Of Descent

1. Depending on your cruise altitude below, initiate the descent at the specified distance before the **Alignment Waypoint**:
   - **50 NM** for **20000 ft**
   - **100 NM** for **30000 ft**
   - **150 NM** for **40000 ft**.
3. Set the `ALT` knob on the **FCU** to **10000 ft**, and **PULL** it (`SHIFT + LEFT CLICK`).
4. Ensure that the aircraft will hit the **Alignment Waypoint** at **10000 ft** altitude.

### 26. Alignment Waypoint

1. Press `BARO` knob on the **EFIS** to switch from `STD` to local QNH.
2. Turn on `LAND` and `RWY TURN OFF` light switches.
3. Set `NOSE` light switch to `TAXI`.
4. Set `AUTO BRK` to `LOW` or `MED` (depending on runway length).
5. Arm `SPEED BRAKE` (verify white band is visible).
6. Start the **Approaching** section.

### 27. Approaching

1. Access **MCDU** and press `PERF` button, then press `ACTIVATE APPR PHASE` and **confirm**.
2. Turn on `ILS` audio reception on the **RMP** to monitor the `ILS` code transmission (morse code).
3. Turn on `LS` switch in the **EFIS** panel to display the `ILS` localizer and glideslope scales in **PFD**.
4. Set the approaching altitude (around **3000 ft** relative to the destination airpoirt) in **FCU** `ALT` knob and **PULL** it.
5. Turn on `SEATBELTS` sign.
6. Access _Aircraft > Announcements_ and trigger `Cpt - Prepare for Landing`.
7. While descending, set `FLAPS` from `1` to `FULL` waiting speed stabilization on each step.
8. Lower the `LANDING GEARS` lever to `DOWN`.
9. When both (horizontal and vertical) purple diamonds are displayed on the **PFD**, press the `APPR` button on **FCU**.
10. Wait and ensure that the glide slope `G/S` gets captured (turns green in **PFD**).

### 28. Landing

1. When altitude reaches **100 ft**, set the `THRUST LEVERS` to `IDLE` (shortcut: `E`).
2. Disable the `AP1` from joystick (press `SHIFT + D`) and start controlling the airplane manually (shortcut: `TAB`).
3. Smoothly pull back the joystick to execute the flare.
4. Upon touchdown, apply `MAX REVERSE` thrust (press `DELETE`) and use `B` for manual breaking if needed.
5. When landing done, cancel reverse thrust (press `DELETE` again).
6. Smoothly advance thrust levers to taxi speed (shortcut: `PG UP`).
7. Transition to the gate (use `TAB + HOLD LEFT MOUSE BUTTON` to control, and `B` to break).

### 29. Taxi To Gate

1. Turn on `APU MASTER` switch.
2. Turn on `APU START` switch.
3. Turn off `LS` switch in the **EFIS**.
4. During the taxi, set `FLAPS` to `0`.
5. Desarm `SPEED BRAKE`.
6. Turn off `ILS` audio reception on the **RMP**.

### 30. Parking

1. When reached the gate, turn on `PARK BRK` (shortcut: `Shift + B`).
2. Set `THRUST LEVERS` to `IDLE` (shortcut: `E`).
3. Turn off `RWY TURN OFF`, `LAND` and `NOSE` light switches.
4. Set `TCAS` to `STBY`.
5. Check `APU START` switch displays the `AVAIL` green light, then turn on `APU BLEED` switch.
6. Turn off `ENG 1` and `ENG 2` master switches.
7. Turn off `BEACON` light swtich.
8. Turn off `SEATBELTS` sign swtich.

### 31. Arrival Boarding Services

1. Enable gear chocks (Aircraft > Ground Services > Landing Gear)
2. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
3. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
4. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

### 32. Shut Down

1. If this is the final flight of the day, proceed with the aircraft decommissioning below, otherwise jump to _Next Flight_ section.
2. Turn off fuel pumps `R TK PUMPS` and `CTR TK` (lights off).
3. Turn off `APU MASTER` switch.
4. Well Done!

### 33. Next Flight

1. If a turnaround flight is planned, follow the steps below:
2. Access _Aircraft > Ground Services_.
3. Click on `Fuel Truck` button.
4. Select `Enable Fuel Truck`.
5. Set the fuel amount to add in `Requested Fuel Quantity (Lbs)` field (default **TOTAL** quantity is: **13.000 Lbs**).
6. Click on `Refuel` and wait refueling to complete.
7. Deselect `Enable Fuel Truck`.
8. Jump to: _MCDU - Initialization_ section.

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
- `ND`: Navigation Display
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

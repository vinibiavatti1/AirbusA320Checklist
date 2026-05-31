# Flight Gear - Airbus A320-family - Checklist

## 1. External Power

1. Enable external power (_Aircraft > Ground Services > Enable External Power Box_)
2. Check `EXT PWR` light is `AVAIL` (Green)
3. Press `EXT PWR` switch (Light changes to `ON` Blue)
4. Turn on `BAT 1` and `BAT 2` switches (lights OFF)

## 2. Turn Cockpit Lights On

1. Set `DOME` switch to `OFF`, `DIM` or `BRT` as preference
2. Adjust `OVHD INTEG LT` as preference
3. Adjust `FCU` light (knob under `FCU` panel) as preference
4. Adjust `FLOOD LT` (Pilot and Co-Pilot) and `INTEG LT` as preference

## 3. Air Data Inertial Reference System (ADIRS)

1. Turn `IR1`, `IR2` and `IR3` selectors to `NAV`
2. Check `ON BAT` light illuminates briefly and then turns OFF

## 4. Auxiliary Power Unit (APU) & Cabin Comfort

1. Turn on `APU MASTER` switch
2. Press `APU START` switch (Blue `ON` light appears) and wait for `AVAIL` green light
3. Turn on `APU BLEED` switch (Pneumatic air active)
4. Check `PACK 1` and `PACK 2` are ON (lights OFF)
5. Set `PACK FLOW` to (`NORM`: default, `HI`: climate is too warm, `LO`: climate is too cold)
6. Adjust `COCKPIT`, `FWD CABIN`, and `AFT CABIN` selectors to your preference (12 o'clock = 24°C)
7. Press `EXT POWER` switch to turn it OFF (light changes back to `AVAIL` green)
8. Disable External Power (_Aircraft > Ground Services > External Power Box_)

## 5. Setup Airplane Lights

1. Turn `STROBE` light switch to `AUTO`
2. Turn on `WING` light
3. Set `NAV & LOGO` light to `2`
4. Turn `SEATBELTS` and `NOSMOKING` signs to `ON`

## 6. Enable Boarding Services

1. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

## 7. MCDU - Initialization (INIT)

1. Access the `MCDU MENU`
2. Select `FMGC` system and wait for system response
3. Access the `INIT` page
4. Set the departure/arrival airports using the format `{ICAO}/{ICAO}` (ex: `SBGR/SBGL`)
5. Press `IRS INIT` > `ALIGN ON REF` > `CONFIRM ALIGN` LSKs
6. Set `FLT NBR` (ex: `AB1234`)
7. Set `COST INDEX` to `50`
8. Set `CRZ FL` to the cruizer altitude (ex: type `200` for 20.000 ft)

## 8. MCDU - Fuel Prediction (INIT > FUEL PREDICTION)

1. Access the `INIT 2` page
2. Click `ZFW/ZFWCG` LSK to calculate the zero fuel weight automatically
3. Press `FUEL PLANNING` LSK and wait for prediction
4. Press `BLOCK CONFIRM` LSK to confirm

## 9. MCDU - Take Off Performance (PERF > TAKE OFF)

1. Access `PERF` page
2. Set `V1`, `VR` and `V2` speeds based on the airplane weight (default: `130`, `135`, `140`)
3. Set `FLAPS/THS` with the take off flaps level and trim (default: `1/UP0.1`)

## 10. MCDU - Approaching Performance (PERF > APPR)

1. Navigate to `APPR` by clicking on `NEXT PHASE` LSK
2. Set `QNH` (default: `1013`)
3. Set `TEMP` (default: `20`)
4. Set `MAG WIND` (default: `000/0` - no wind)
5. Set `BARO` (default `200`)

## 11. Runway & ILS Research

1. Open map map (_Equipament > Map_)
2. Navigate to the departure airport and annotate the departure `RUNWAY CODE`
3. Navigate to the destination airport and annotate the arrival `RUNWAY CODE`, `ILS COURSE` and `ILS FREQUENCY`
4. Calculate the `INVERSE COURSE` and annotate it (formula: if course < 180, do `{COURSE} + 180`. If course > 180, do `{COURSE} - 180`)
5. Check if everything was annotated (ex: `DEP: 27L ARR: 15 CRS: 149 FRQ: 110.30 INV: 329`)

> Template: `DEP: ___ ARR: ___ CRS: ___ FRQ: ___.__ INV: ___`

## 12. MCDU - Flight Plan Departure (F-PLN)

1. Access `F-PLN` page
2. Select departure airport left LSK (ex: `SBGR`)
3. Select `DEPARTURE`
4. Select the `RUNWAY CODE` for departure (ex: `27L`) (check annotations)
5. Select `TMPY F-PLN` and `TMPY INSERT *`

## 13. MCDU - Flight Plan Arrival (F-PLN)

1. Access `F-PLN` page
2. Select destination airport left LSK (ex: `SBGL`)
3. Select `ARRIVAL`
4. Select the `RUNWAY CODE` for landing (ex: `15`) (check annotations)
5. Select `TMPY F-PLN` and `TMPY INSERT *`

## 14. MCDU - Flight Plan Approaching Waypoint (F-PLN) (10.000 ft)

1. Access `F-PLN` page
2. Select the departure airport left LSK
3. Type into the scratchpad the following format: `{ICAO}/{INV}/{DIST}` (ex: `SBGL/329/40`) (check annotations)
4. Select `NEXT WPT` and `TMPY INSERT *`
5. Remove all `F-PLN DISCONTINUITY` from the plan using the `CLR` command

## 15. MCDU - Radio Navigation (RAD NAV)

1. Open the `RAD NAV` page
2. Set the `ILS/FREQ` with the `ILS FREQUENCY` (ex: `110.30`) (check annotations)
3. Set the `CRS` (below `ILS/FREQ`) with the `ILS COURSE` (ex: `149`) (check annotations)

## 16. Review Map

1. Open the map (_Equipament > Map_)
2. Review the route and check everything is correct

## 17. Setup Flight Control Unit (FCU)

1. Set cruise altitude on the `ALTITUDE` knob (ex: 30.000 ft)
2. Push the `ALTITUDE` knob IN (check for a white dot next to the altitude on the FCU)
3. Push the `SPEED` knob IN (enables managed speed according to MCDU profile)
4. Push the `HEADING` knob IN (enables managed lateral navigation to follow the flight plan route)

## 18. Disable Boarding Services And Gear Chocks

1. Disable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Disable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Lower and disable front and rear catering trucks (_Aircraft > Ground Services > Catering_)
4. Disable gear chocks (_Aircraft > Ground Services > Landing Gear_)

## 19. Request Pushback

1. Setup pushback route (_Aircraft > Pushback > Route > Enter_)
2. Mark `CONNECT` to connect the pushback truck
3. Release `PARK BRK` (turn switch to `OFF`) (shortcut: `Shift + B`)
4. Start auto-push (_Aircraft > Pushback > Autopush > Start_) and wait
5. Unmark `CONNECT` to disconnect the pushback truck
6. Set `PARK BRK` to `ON` (shortcut: `Shift + B`)

## 20. Engines Start Procedure

1. Turn on fuel pumps `R TK PUMPS` and `CTR TK` (lights OFF)
2. Turn on `BEACON` to signalize that the engines are starting
3. Turn `ENG MODE` selector to `IGN/START`
4. Raise `ENG 2` master switch to `ON` and wait for engine stabilization (Engine 2 first to provide primary hydraulic pressure)
5. Raise `ENG 1` master switch to `ON` and wait for engine stabilization
6. Turn `ENG MODE` selector back to `NORM`
7. Turn off `APU MASTER` switch

## 21. Taxi

1. Trigger `Cpt - Welcome` announcement (_Aircraft > Announcements_)
2. Turn `NOSE` light switch to `TAXI`
3. Set `AUTO BRK` to `MAX`
4. Adjust `PITCH TRIM` wheel to match MCDU target (default: `UP 0.1`)
5. Set `FLAPS` to takeoff position (default: `1`)
6. Arm `SPEED BRAKE` (verify white band is visible)
7. Press `TO CONFIG` button to test takeoff configuration
8. Check `ECAM` center screen and confirm it displays `T.O CONFIG NORMAL` in green
9. Release `PARK BRK` (turn switch to `OFF`)
10. Smoothly advance thrust levers to approximately 20%-25% `N1` to begin taxiing
11. Taxi the aircraft to the takeoff runway holding point (use `TAB + Hold Left Click` to control the nose wheel steering and `B` to break)
12. Trigger `Cpt - Doors Check` announcement (_Aircraft > Announcements_)

## 22. Before Takeoff

1. Set `PARK BRK` to `ON` (shortcut: `Shift + B`)
2. Turn `RWY TURN OFF` light switches to `ON`
3. Turn `NOSE` light switch to `T.O`
4. Turn on `LAND` lights
5. Set `TCAS` (Transponder) switch to `TA/RA`
6. Press `ALL` button on the `CALLS` panel to advise cabin crew
7. Trigger `Cpt - Prepare for Takeoff` announcement (_Aircraft > Announcements_)

## 23. Line Up & Takeoff

1. Release `PARK BRK` (turn switch to `OFF`) (shortcut: `Shift + B`)
2. Align the aircraft perfectly with the runway centerline
3. Advance `THRUST LEVERS` smoothly to 50% `N1`, wait for engines to stabilize, then push to `TOGA` (shortcut: `F`)
4. Maintain runway centerline using rudder pedals (`TAB + HOLD LEFT CLICK`)
5. At `VR` speed (around 135 knots), gently pull the joystick back to rotate the aircraft nose up to 15 degrees

## 24. Climb (After Takeoff-Off)

1. Set the `LANDING GEARS` lever to `UP`
2. Move `FLAPS` lever to `0`
3. Wait for climb and stabilize the plane straight ahead
4. Move `THRUST LEVERS` to `CL` (shortcut: `SHIFT + F`)
5. Turn on `AP1` (Autopilot 1) to let the FMGC fly the programmed route
6. Verify `A/THR` is active
7. Push the `SPEED BRAKE` lever down
8. Turn off `RWY TURN OFF`, `LAND` and `NOSE` lights
9. Press the `BARO` knob on the `FCU`  to set `STD` (Standard)

## 25. Cruise

1. Turn off `SEAT BELTS` sign (if the flight is smooth and free of turbulence)

## 26. Descent Preparation (Before Waypoint)

1. Press the `BARO` knob on the FCU to switch from `STD` to the local QNH
2. Turn on `LAND` and `RWY TURN OFF` lights
3. Turn `NOSE` light switch to `TAXI`
4. Set the `AUTO BRK` (Autobrake) to `LOW` or `MED` (depending on runway length)
5. Arm `SPEED BRAKE` (verify white band is visible)
6. Start the descend by pulling the `ALTITUDE` on the `FCU` knob (`SHIFT + LEFT CLICK`)

> It is recommended that the waypoint is reached at 10.000 ft altitude

## 27. Approaching (After Waypoint)

1. Turn on the `ILS` audio reception on `RMP` to monitor the `ILS` code transmission
2. Trigger `Cpt - Prepare for Landing` announcement (_Aircraft > Announcements_)
3. Turn on `SEAT BELTS` sign
4. Start the descend by pulling the `ALTITUDE` on the `FCU` knob (`SHIFT + LEFT CLICK`) to approaching altitude (ex: 3000 ft)
5. Press the `LS` button on the `EFIS` panel to display the ILS localizer and glideslope scales on your `PFD`
6. Raise `FLAPS` from `1` to `FULL` waiting speed stabilization on each step
7. Lower the `LANDING GEARS` lever to `DOWN`
8. Press the `APPR` (Approach) button on the `FCU` to arm the ILS guidance (verify `LOC` and `G/S` appear armed on the `PFD` screen)
9. Ensure the glide slope (G/S) get captured by checking that the purple LS diamonds are aligned on `PFD` screen

## 28. Landing & Touchdown

1. (Optional) Disengage `AP1` (Autopilot) to fly manually, or leave it `ON` for an automatic landing (Autoland)
2. Smoothly pull back on the joystick to raise the nose to perform flare (use `TAB` to control)
3. Set `THRUST LEVERS` to `IDLE` (shortcut: `E`)
4. Upon touchdown, apply `MAX REVERSE` thrust (shortcut: `DELETE`) and use manual breaking if needed (shortcut: `B`)
5. When landing done, cancel reverse thrust (click `DELETE` again)
6. Transition smoothly to the exit of the runway (use `TAB + HOLD LEFT CLICK` to control the nose wheel steering, and `B` for breaks)
7. Drive airplane to the airport gate
8. Retract `FLAPS` to `0`

## 29. Parking At the Gate

1. Set `PARK BRK` to `ON` (shortcut: `Shift + B`)
2. Set `THRUST LEVERS` to `IDLE`
3. Push the `SPEED BRAKE` lever down
4. Turn off `RWY TURN OFF`, `LAND` and `NOSE` lights
5. Set `TCAS` (Transponder) to `STBY`
8. Turn on `APU MASTER` switch
9. Press `APU START` switch (Blue `ON` light appears) and wait for `AVAIL` green light
10. Turn on `APU BLEED` switch (Pneumatic air active)
11. Move `ENG 1` and `ENG 2` master switches to `OFF`
12. Turn off `BEACON` light
13. Turn off `SEAT BELTS` sign

## 30. Enable Boarding Services and Gear Chocks

1. Enable gear chocks (Aircraft > Ground Services > Landing Gear)
2. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
3. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
4. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

## 31. Shut Down (If Final Flight)

2. If this is the final flight of the day, proceed with the aircraft decommissioning below:
3. Turn off wing fuel pumps `R TK PUMPS 1` and `R TK PUMPS 2` in `ENG 1` and `ENG 2` (lights OFF)
4. Turn off central fuel pumps `L XFR` and `R XFR` in `CTR TK` (if applicable)
5. Turn off `APU MASTER SW`
6. Done

## 33. Next Steps (If Post Flight)

1. If a turnaround flight is planned, follow the steps below
2. Enable fuel truck (_Aircraft > Ground Services > Fuel_)
3. Add fuel (Avg: 13.000 Lbs)
4. Disable fuel truck (_Aircraft > Ground Services > Fuel_)
5. Jump to **7. MCDU - Initialization (INIT)** section.

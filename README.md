# Flight Gear - Airbus A320-family - Checklist

## 1. Gear Chocks

1. Enable gear chocks (_Aircraft > Ground Services > Landing Gear_)

## 2. Fueling (If Needed)

1. Enable fuel truck (_Aircraft > Ground Services > Fuel_)
2. Add fuel (Avg: 13.000 Lbs)
3. Disable fuel truck (_Aircraft > Ground Services > Fuel_)

## 3. External Power

1. Enable external power (_Aircraft > Ground Services > Enable External Power Box_)
2. Check `EXT PWR` light is `AVAIL` (Green)
3. Press `EXT PWR` switch (Light changes to `ON` Blue)
4. Turn on `BAT 1` and `BAT 2` switches (lights OFF)

## 4. Turn On Cockpit Lights

1. Set `DOME` switch to `OFF`, `DIM` or `BRT` as preference
2. Adjust `OVHD INTEG LT` as preference
3. Adjust `FCU` light (knob under `FCU` panel) as preference
4. Adjust `FLOOD LT` (Pilot and Co-Pilot) and `INTEG LT` as preference

## 5. Air Data Inertial Reference System (ADIRS)

1. Turn `IR1`, `IR2` and `IR3` selectors to `NAV`
2. Check `ON BAT` light illuminates briefly and then turns OFF

## 6. Auxiliary Power Unit (APU) & Cabin Comfort

1. Turn on `APU MASTER` switch
2. Press `APU START` switch (Blue `ON` light appears) and wait for `AVAIL` green light
3. Turn on `APU BLEED` switch (Pneumatic air active)
4. Check `X-BLEED` is set to `AUTO`
5. Check `PACK 1` and `PACK 2` are ON (lights OFF)
6. Check `HOT AIR` switch is ON (lights OFF)
7. Set `PACK FLOW` to (`NORM`: default, `HI`: climate is too warm, `LO`: climate is too cold)
8. Adjust `COCKPIT`, `FWD CABIN`, and `AFT CABIN` selectors to your preference (12 o'clock = 24°C)
9. Press `EXT POWER` switch to turn it OFF (light changes back to `AVAIL` green)
10. Disable External Power (_Aircraft > Ground Services > External Power Box_)

## 7. Turn Radio and Lights On

1. Turn on the `RMP` (Radio Management Panel)
2. Set `NAV & LOGO` light to `2`
3. Turn on `WING` light
4. Turn `SEATBELTS` and `NOSMOKING` signs to `ON`

## 8. Enable Boarding Services

1. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

## 9. MCDU - Initialization (INIT)

1. Access the `MCDU MENU`
2. Select `FMGC` system and wait for system response
3. Access the `INIT` page
4. Set the departure/arrival airports using the format `{ICAO}/{ICAO}` (ex: `SBGR/SBGL`)
5. Press `IRS INIT` > `ALIGN ON REF` > `CONFIRM ALIGN` LSKs
6. Set `FLT NBR` (ex: `AB1234`)
7. Set `COST INDEX` to `50`
8. Set `CRZ FL` to the cruizer altitude (ex: type `300` for 30.000 ft)

## 10. MCDU - Fuel Prediction (INIT > FUEL PREDICTION)

1. Access the `INIT 2` page
2. Click `ZFW/ZFWCG` LSK to calculate the zero fuel weight automatically
3. Press `FUEL PLANNING` LSK and wait for prediction
4. Press `BLOCK CONFIRM` LSK to confirm

## 11. MCDU - Take Off Performance (PERF > TAKE OFF)

1. Access `PERF` page
2. Set `V1`, `VR` and `V2` speeds based on the airplane weight (default: `130`, `135`, `140`)
3. Set `FLAPS/THS` with the take off flaps level and trim (default: `1/UP0.1`)
4. Adjust the `TRANS ALT` accordingly to the region (default: `18000` ft)

## 12. MCDU - Approaching Performance (PERF > APPR)

1. Access `PERF` page and navigate to `PERF - APPR`
2. Set `QNH` (default: `1013`)
3. Set `TEMP` (default: `20`)
4. Set `MAG WIND` (default: `000/0` - no wind)
5. Set `BARO` (default `200`)

## 13. Runway & ILS Research

1. Open map map (_Equipament > Map_)
2. Navigate to the departure airport and decide a runway for take off. Annotate the code (ex: `SBGR 27L`)
3. Navigate to the destination airport and decide an ILS runway for landing
4. Annotate the **landing runway code**, **ILS course** and **ILS frequency** (example: `SBGL 15 149 - 110.30MHz`)

## 14. MCDU - Flight Plan Departure (F-PLN)

1. Access `F-PLN` page
2. Select departure airport left LSK (ex: `SBGR`)
3. Select `DEPARTURE`
4. Select the ILS runway for departure (ex: `27L`)
5. Select `NO SID`
6. Select `TMPY F-PLN` and `TMPY INSERT *`

## 15. MCDU - Flight Plan Arrival (F-PLN)

1. Access `F-PLN` page
2. Select destination airport left LSK (ex: `SBGL`)
3. Select `ARRIVAL`
4. Select the ILS runway for landing (ex: `15`)
5. Select `NO STAR`
6. Select `TMPY F-PLN` and `TMPY INSERT *`

## 16. MCDU - Flight Plan Approaching Waypoint (F-PLN)

1. Access `F-PLN` page
2. Select `---F-PLN DISCONTINUITY--` left LSK
3. Calculate the reverse of the ILS course: If the course is less than 180, do `{COURSE} + 180`. If it is greater, do `{COURSE} - 180`. (Ex: `149 + 180 = 329`)
4. Type into the scratchpad the following format: `{ICAO}/{INVERSE_COURSE}/{DIST}` (for example: `SBGL/329/50`)
5. Select `NEXT WPT` and `TMPY INSERT *`
6. Click the `CLR` button on the MCDU keyboard, and then click the side button next to all `---F-PLN DISCONTINUITY--` to clear them and join the route.

## 17. MCDU - Radio Navigation (RAD NAV)

1. Open the `RAD NAV` page
2. Set the `ILS/FREQ` with the **ILS frequency** (ex: `110.30`)
3. Set the `CRS` (below `ILS/FREQ`) with the runway **course** (ex: `149`)

## 18. Review Map

1. Open the map (_Equipament > Map_)
2. Review the route and check everything is correct

## 19. Setup Flight Control Unit (FCU)

1. Set cruise altitude on the `ALTITUDE` knob (ex: 30.000 ft)
2. Push the `ALTITUDE` knob IN (check for a white dot next to the altitude on the FCU)
3. Push the `SPEED` knob IN (enables managed speed according to MCDU profile)
4. Push the `HEADING` knob IN (enables managed lateral navigation to follow the flight plan route)

## 20. Disable Boarding Services

1. Disable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Disable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Lower and disable front and rear catering trucks (_Aircraft > Ground Services > Catering_)
4. Disable gear chocks (_Aircraft > Ground Services > Landing Gear_)

## 21. Engines Start Procedure

1. Turn on wing fuel pumps `R TK PUMPS 1` and `R TK PUMPS 2` in `ENG 1` and `ENG 2` (lights OFF)
2. Turn on central fuel pumps `L XFR` and `R XFR` in `CTR TK` (if center tank has fuel)
3. Check `MODE SEL` is set to `AUTO` (lights OFF)
4. Turn on `BEACON` to signalize that the engines are starting
5. Turn `ENG MODE` selector to `IGN/START`
6. Raise `ENG 2` master switch to `ON` and wait for engine stabilization (Engine 2 first to provide primary hydraulic pressure)
7. Raise `ENG 1` master switch to `ON` and wait for engine stabilization
8. Turn `ENG MODE` selector back to `NORM`

## 22. Turn Off Auxiliary Power Unit (APU)

1. Turn off `APU BLEED` switch
2. Turn off `APU MASTER` switch

## 23. Taxi

1. Trigger `Cpt - Welcome` announcement (_Aircraft > Announcements_)
2. Turn `NOSE` light switch to `TAXI`
3. Set `FLAPS` to takeoff position (default: `1`)
4. Adjust `PITCH TRIM` wheel to match MCDU target (default: `UP 0.1`)
5. Arm the ground spoilers by pulling UP the `SPEED BRAKE` lever (verify white band is visible)
6. Set `AUTO BRK` to `MAX`
7. Press `TO CONFIG` button to test takeoff configuration
8. Check `ECAM` center screen and confirm it displays `T.O CONFIG NORMAL` in green
9. Release `PARK BRK` (turn switch to `OFF`)
10. Smoothly advance thrust levers to approximately 20%-25% `N1` to begin taxiing
11. Taxi the aircraft to the takeoff runway holding point (use `TAB + Hold Left Click` to control the nose wheel steering)
12. Trigger `Cpt - Doors Check` announcement (_Aircraft > Announcements_)

## 24. Before Takeoff

1. Turn `STROBE` light switch to `AUTO`
2. Turn `RWY TURN OFF` light switches to `ON`
3. Turn `NOSE` light switch to `T.O` (Takeoff)
4. Turn on `LAND` (Landing) lights (extend and turn on both wings lights)
5. Set `TCAS` (Transponder) switch to `TA/RA`
6. Check `PWS` (Predictive Windshear System) switch is set to `AUTO`
7. Press `ALL` button on the `CALLS` panel to advise cabin crew
8. Trigger `Cpt - Prepare for Takeoff` announcement (_Aircraft > Announcements_)

## 25. Line Up & Takeoff

1. Align the aircraft perfectly with the runway centerline
2. Check `ENG MODE` selector is set to `NORM` (re-verify)
3. Check `FLAPS` and `PITCH TRIM` are set accordingly
4. Advance `THRUST LEVERS` smoothly to 50% `N1`, wait for engines to stabilize, then push to `TOGA` (shortcut: `F`)
5. Maintain runway centerline using rudder pedals (`TAB + Hold Left Click`)
6. At `VR` speed (around 135 knots), gently pull the joystick back to rotate the aircraft nose up to 15 degrees

## 26. Climb (After Lift-Off)

1. When positive climb is confirmed on the `PFD` screen (altitude raising), set the `LANDING GEARS` lever to `UP`
2. At acceleration altitude (around 1500 ft above ground), move `THRUST LEVERS` to `CL` (Climb) detent (shortcut: `SHIFT + F`)
3. Turn on `AP1` (Autopilot 1) to let the FMGC fly the programmed route
4. Verify `A/THR` is active
5. At S speed (around 185 knots), move `FLAPS` lever to `0` (Clean configuration)
6. Disarm ground spoilers (push the `SPEED BRAKE` lever down)
7. Turn off `AUTO BRK` switch
8. Turn off `RWY TURN OFF` and `NOSE` lights
9. Press the `BARO` knob on the `FCU`  to set `STD` (Standard)
10. Leave `LAND` lights on until passing 10.000 ft)

## 27. Cruise (Level Off)

1. Check `ALT *` changes to `ALT` on the `PFD` screen (confirming the aircraft leveled off at cruise altitude)
2. Turn off `SEAT BELTS` sign (if the flight is smooth and free of turbulence)

## 28. Descent Preparation (Top of Descent)

1. Identify the destination airport `ATIS` frequency (_AI > CTA Services_)
2. Click the `COM1` button to tune `VHF1` radio channel into the `ATIS` frequency, and ensure weather broadcast audio reception
3. Select the `VHF1` channel and turn on `VHF1` audio reception in `RMP`
4. On the `MCDU`, access the `PERF` page and navigate to `PERF - APPR`
5. Listen to the `ATIS` broadcast and insert the `QNH`, `TEMP` and `MAG WIND`.
6. Turn off the `VHF1` audio reception
7. At the `T/D` (Top of Descent) point on the `ND` screen, push the `ALTITUDE` knob IN to initiate Managed Descent (DES)

## 29. Approaching

1. Turn on the `ILS` audio reception on `RMP`
1. Press the `BARO` knob on the FCU to switch from `STD` to the local QNH captured from the `ATIS`
2. When passing 10.000 feet, turn on `LAND` (Landing), `RWY TURN OFF`, and `NOSE` (set to `TAXI`) lights
3. Turn on `SEAT BELTS` sign
4. Set the `AUTO BRK` (Autobrake) to `LOW` or `MED` (depending on runway length)
5. Trigger `Cpt - Prepare for Landing` announcement (_Aircraft > Announcements_)
6. Press the `LS` button on the `EFIS` panel to display the ILS localizer and glideslope scales on your `PFD`

## 30. Final Approach & Configuration

1. As the aircraft approaches the `DECELERATION POINT` (magenta `D` circle on the `ND` screen), verify the autothrust automatically starts reducing speed towards `VAPP`
2. When speed drops below the green max flaps speed indicator `VFE`, move `FLAPS` lever to `1`
3. Press the `APPR` (Approach) button on the `FCU` to arm the ILS guidance (verify `LOC` and `G/S` appear armed on the `PFD` screen)
4. When speed permits, move `FLAPS` lever to `2`
5. Lower the `LANDING GEARS` lever to `DOWN`
7. Ensure the glide slope (G/S) get captured by checking that the purple LS diamonds are aligned on `PFD` screen
8. Arm the ground spoilers by pulling UP the `SPEED BRAKE` lever (verify white band is visible)
9. Move `FLAPS` lever to `3` and then `FULL` (Full landing configuration)

## 31. Landing & Touchdown

1. (Optional) Disengage `AP1` (Autopilot) to fly manually, or leave it `ON` for an automatic landing (Autoland)
2. Smoothly pull back on the joystick to raise the nose to perform flare (use `TAB` to control)
3. Set `THRUST LEVERS` to `IDLE` (shortcut: `E`)
5. Upon touchdown, apply `MAX REVERSE` thrust (shortcut: `DELETE`) and use manual breaking if needed (shortcut: `B`)
6. At 60 knots, cancel reverse thrust (click `DELETE` again)
7. Transition smoothly to the exit the runway (use `TAB + Hold Left Click` to control the nose wheel steering)

## 32. Taxi After Landing (Vacating Runway)

1. Retract `FLAPS` to `0` (Clean configuration)
2. Push the `SPEED BRAKE` lever down
3. Turn off `LAND` lights
4. Turn off `RWY TURN OFF` lights
5. Set `TCAS` (Transponder) to `STBY`
6. Drive airplane to the airport gate

## 33. Parking At the Gate

1. Set `PARK BRK` to `ON`
2. Turn on `APU MASTER` switch
3. Press `APU START` switch (Blue `ON` light appears) and wait for `AVAIL` green light
4. Move `ENG 1` and `ENG 2` master switches to `OFF`
5. Turn off `BEACON` light
6. Turn off `SEAT BELTS` sign

## 34. Enable Boarding Services

1. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

## 35. Shut Down & Post-Flight

1. If a turnaround flight is planned, return to Step 1 of this checklist
2. If this is the final flight of the day, proceed with the aircraft decommissioning below:
3. Turn off wing fuel pumps `R TK PUMPS 1` and `R TK PUMPS 2` in `ENG 1` and `ENG 2` (lights OFF)
4. Turn off central fuel pumps `L XFR` and `R XFR` in `CTR TK` (if applicable)
5. Turn off `APU MASTER SW`

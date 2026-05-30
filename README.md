# Flight Gear - Airbus A320-family - Checklist

## 1. Fueling

1. Enable fuel truck (_Aircraft > Ground Services > Fuel_)
2. Add fuel (Avg: 13.000 Lbs)
3. Disable fuel truck (_Aircraft > Ground Services > Fuel_)

## 2. Enable Boarding Services

1. Enable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Enable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Enable and raise front and rear catering trucks (_Aircraft > Ground Services > Catering_)

## 3. External Power

1. Enable external power (_Aircraft > Ground Services > Enable External Power Box_)
2. Check `EXT PWR` light is `AVAIL` (Green)
3. Press `EXT PWR` switch (Light changes to `ON` Blue)
4. Turn on `BAT 1` and `BAT 2` switches (lights OFF)

## 4. Air Data Inertial Reference System (ADIRS)

1. Turn `IR1`, `IR2` and `IR3` selectors to `NAV`
2. Check `ON BAT` light illuminates briefly and then turns OFF

## 5 - Auxiliary Power Unit (APU) & Cabin Comfort

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

## 6. MCDU - Initialization (INIT)

1. Access the `MCDU MENU`
2. Select `FMGC` system and wait for system response
3. Access the `INIT` page
4. Set the departure/arrival airports using the format `{ICAO}/{ICAO}` (ex: `SBGR/SBGL`)
5. Press `IRS INIT` > `ALIGN ON REF` > `CONFIRM ALIGN` LSKs
6. Set `FLT NBR` (ex: `AB1234`)
7. Set `COST INDEX` to `50`
8. Set `CRZ FL` to the cruizer altitude (ex: type `300` for 30.000 ft)

## 7. MCDU - Fuel Prediction (INIT > FUEL PREDICTION)

1. Access the `INIT 2` page
2. Click `ZFW/ZFWCG` LSK to calculate the zero fuel weight automatically
3. Press `FUEL PLANNING` LSK and wait for prediction
4. Press `BLOCK CONFIRM` LSK to confirm

## 8. MCDU - Take Off Performance (PERF > TAKE OFF)

1. Access `PERF` page
2. Set `V1`, `VR` and `V2` speeds based on the airplane weight (default: `130`, `135`, `140`)
3. Set `FLAPS/THS` with the take off flaps level and trim (default: `1/UP0.1`)
4. Adjust the `TRANS ALT` accordingly to the region (default: `18000` ft)

## 9. MCDU - Approaching Performance (PERF > APPR)

1. Access `PERF` page and navigate to `PERF - APPR`
2. Set `QNH` (default: `1013`)
3. Set `TEMP` (default: `20`)
4. Set `MAG WIND` (default: `000/0` - no wind)
5. Set `BARO` (default `200`)

## 10. Getting Departure-Arrival Runways Data

1. Open map map (_Equipament > Map_)
2. Navigate to the departure airport and decide a runway for take off. Annotate the code (ex: `SBGR 27L`)
3. Navigate to the destination airport and decide an ILS runway for landing
4. Annotate the **landing runway code**, **ILS course** and **ILS frequency** (example: `SBGL 15 149 - 110.30MHz`)

## 11. MCDU - Flight Plan Departure (F-PLN)

1. Access `F-PLN` page
2. Select departure airport left LSK (ex: `SBGR`)
3. Select `DEPARTURE`
4. Select the ILS runway for departure (ex: `27L`)
5. Select `NO SID`
6. Select `TMPY F-PLN` and `TMPY INSERT *`

## 12. MCDU - Flight Plan Arrival (F-PLN)

1. Access `F-PLN` page
2. Select destination airport left LSK (ex: `SBGL`)
3. Select `ARRIVAL`
4. Select the ILS runway for landing (ex: `15`)
5. Select `NO STAR`
6. Select `TMPY F-PLN` and `TMPY INSERT *`

## 13. MCDU - Flight Plan Approaching Waypoint (F-PLN)

1. Access `F-PLN` page
2. Select `---F-PLN DISCONTINUITY--` left LSK
3. Calculate the reverse course of the track: If the course is less than 180, do `{COURSE} + 180`. If it is greater, do `{COURSE} - 180`. (Ex: `149 + 180 = 329`)
4. Type into the scratchpad the following format: `{ICAO}/{INVERSE_COURSE}/{DIST}` (for example: `SBGL/329/50`)
5. Select `NEXT WPT` and `TMPY INSERT *`
6. Click the `CLR` button on the MCDU keyboard, and then click the side button next to all `---F-PLN DISCONTINUITY--` to clear them and join the route.

## 14. MCDU - Radio Navigation (RAD NAV)

1. Open the `RAD NAV` page
2. Set the `ILS/FREQ` with the **ILS frequency** (ex: `110.30`)
3. Set the `CRS` (below `ILS/FREQ`) with the runway **course** (ex: `149`)

## 15. Review Map

1. Open the map (_Equipament > Map_)
2. Review the route and check everything is correct

## 16. Disable Boarding Services

1. Disable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Disable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Lower and disable front and rear catering trucks (_Aircraft > Ground Services > Catering_)
4. Disable gear chocks (_Aircraft > Ground Services > Landing Gear_)

## 17. Engines Start Procedure

1. Turn on wing fuel pumps `R TK PUMPS 1` and `R TK PUMPS 2` in `ENG 1` and `ENG 2` (lights OFF)
2. Turn on central fuel pumps `L XFR` and `R XFR` in `CTR TK` (if center tank has fuel)
3. Check `MODE SEL` is set to `AUTO` (lights OFF)
4. Turn on `BEACON` to signalize that the engines are starting
5. Turn `ENG MODE` selector to `IGN/START`
6. Raise `ENG 2` master switch to `ON` and wait for engine stabilization (Engine 2 first to provide primary hydraulic pressure)
7. Raise `ENG 1` master switch to `ON` and wait for engine stabilization
8. Turn `ENG MODE` selector back to `NORM`

## 18. Turn Off Auxiliary Power Unit (APU)

1. Turn off `APU BLEED` switch
2. Turn off `APU MASTER` switch

## 19. Taxi

1. Turn `NOSE` light switch to `TAXI`
2. Set flaps to takeoff position (default: `1`)
3. Arm ground spoilers by pulling the `SPEED BRAKE` lever up (verify it stays in the `RET` position but armed)
4. Set `AUTO BRK` to `MAX`
5. Press `TO CONFIG` button to test takeoff configuration
6. Check `ECAM` center screen and confirm it displays `T.O CONFIG NORMAL` in green
7. Release `PARK BRK` (turn switch to `OFF`)
8. Smoothly advance thrust levers to approximately 20%-25% `N1` to begin taxiing

## X. Before Take Off

## X. Take Off

## X. After Take Off

## X. Cruizer

## X. Before Landing

## X. Approaching

## 15. Landing

## 16. Taxi

## 17. Parking

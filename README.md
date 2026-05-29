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
2. Press `APU START` switch (Blue `ON` light appears)
3. Wait for `AVAIL` green light on `APU START` switch
4. Turn on `APU BLEED` switch (Pneumatic air active)
5. Check `X-BLEED` is set to `AUTO`
6. Check `PACK 1` and `PACK 2` are ON (lights OFF)
7. Check `HOT AIR` switch is ON (lights OFF)
8. Set `PACK FLOW` to (`NORM`: default, `HI`: climate is too warm, `LO`: climate is too cold)
9. Adjust `COCKPIT`, `FWD CABIN`, and `AFT CABIN` selectors to your preference (12 o'clock (default) = 24°C)
10. Press `EXT POWER` switch to turn it OFF (Light changes back to `AVAIL` green)
11. Disable External Power (_Aircraft > Ground Services > External Power_)

## 6. MCDU - Initialization (INIT)

1. Access the `MCDU MENU`
2. Select `FMGC` system and wait for system response
3. Access the `INIT` page
4. Set `FLT NBR` (ex: `AB1234`)
5. Set `COST INDEX` to `50`
6. Set `CRZ FL` to the cruizer altitude (ex: type `300` for 30.000 ft)
7. Set the departure/arrival airports using the format `{ICAO}/{ICAO}` (ex: `SBGR/SBGL`)
8. Press `IRS INIT` > `ALIGN ON REF` > `CONFIRM ALIGN` LCKs

## 7. MCDU - Fuel Prediction (INIT > FUEL PREDICTION)

1. Access the `INIT 2` page
2. Click `ZFW/ZFWCG` LCK to calculate the ??? automatically
3. Press `FUEL PLANNING` LCK and wait for prediction
4. Press `BLOCK CONFIRM` LCK

## 8. MCDU - Take Off Performance (PERF > TAKE OFF)

1. Access `PERF` page
2. Set `V1`, `VR` and `V2` speeds based on the airplane weight (default: `130`, `135`, `140`)
3. Set `FLAPS/THS` with the take off flaps level and trim (default: `1/UP0.1`)

## 9. MCDU - Approaching Performance (PERF > APPR)

1. Access `PERF` page
2. Navigate to `PERF - APPR` page
3. Set `QNH` (default: `1013` QnH)
4. Set `TEMP` (default: `20` celsius)
5. Set `BARO` (default `200` ft)
6. Set `MAG WIND` (default: `000/0` - no wind)

## 10. Getting Departure-Arrival Runways Data

1. Open map (_Equipament > Map_)
2. Navigate to the departure airport
3. Decide a runway for take off
4. Annotate the departure **runway code** (example: `SBGR 27L`)
5. Navigate to the destination airport
6. Decide a ILS runway for landing
7. Annotate the landing **runway code** and ILS **course** and **frequency** information (example: `SBGL 15 149 - 110.30MHz`)

## 11. MCDU - Flight Plan Departure (F-PLN)

1. Access `F-PLN` page
2. Select departure airport left LCK (ex: `SBGR`)
3. Select `DEPARTURE`
4. Select the ILS runway for departure (ex: `27L`)
5. Select `NO SID`
6. Select `TMPY F-PLN`
7. Select `TMPY INSERT *`

## 12. MCDU - Flight Plan Arrival (F-PLN)

1. Access `F-PLN` page
2. Select destination airport left LCK (ex: `SBGL`)
3. Select `ARRIVAL`
4. Select the ILS runway for landing (ex: `15`)
5. Select `NO STAR`
6. Select `TMPY F-PLN`
7. Select `TMPY INSERT *`

## 13. MCDU - Flight Plan Approaching Waypoint (F-PLN)

1. Access `F-PLN` page
2. Select `---F-PLN DISCONTINUITY--` left LCK
3. Calculate the inverse angle of landing runway: `x = 180 + {COURSE}` (Course is available at _Equipament > Map_)
4. Type this to the scrathpad: `{ICAO}/{x}/50` (for example: `SBGL/329/50`)
5. Select `NEXT WPT`
7. Select `TMPY INSERT *`
8. Click the `CLR` button to insert `CLR` text, and select `---F-PLN DISCONTINUITY--` to remove it (do it for all discontinuity points)

## 14. MCDU - Radio Navigation (RAD NAV)

1. Open the `RAD NAV` page
2. Set the `ILS/FREQ` with the ILS runway **frequency** information
3. Set the `CRS` (below `ILS/FREQ`) with the **course** information

## 15. Review Map

1. Open map (_Equipament > Map_)
2. Review if the route is correct

## 16. Disable Boarding Services

1. Disable front and rear stairways (_Aircraft > Ground Services > Stairways_)
2. Disable baggage ramp (_Aircraft > Ground Services > Baggage_)
3. Lower and disable front and rear catering trucks (_Aircraft > Ground Services > Catering_)
4. Disable gear chocks (_Aircraft > Ground Services > Landing Gear_)

## 8. Engines

## X. Taxi

## X. Before Take Off

## X. Take Off

## X. After Take Off

## X. Cruizer

## X. Before Landing

## X. Approaching

## 15. Landing

## 16. Taxi

## 17. Parking

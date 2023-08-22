# **Eureka MANTA+35 Datasonde Sensor Calibration**
Updated: August 21, 2023

## **Preparation for Calibrations**

* Before downloading data and calibrating datasonde, clean biofouling off datasonde and sensors. Be extremely careful around the pH sensor as bulb is extremely fragile.

* Clean sensor guard and anti-fouling copper. Replace copper if necessary.

* Check wiper blade for wear and replace if necessary (every few months).

* Connect datasonde to PC to download the data, it will find correct COM port and initialize. Once connected, download data: Software&rarr;Manta2, there will be many Manta2 files, chose the most recent file and export to C Drive/Manta2. This file must also be copied to the CAP LTER Dropbox folder: Dropbox\research\TempeTownLake\Data. File name should be YYMMDD_TTL_data, with the STARTING date of the log file indicated (i.e., one month earlier).

* Logging must be turned OFF to calibrate. Use storage cup for calibrations, can use reverse side of cap (sealed, but not screwed on) for rinses.

* Calibration standards may be salvaged for reuse as rinse solution ONLY for next month's calibration (We generally do this for turbidity 100 NTU standard). Do not reuse for actual calibration.

* Make sure all waste is in appropriate container and properly labeled.

* Eureka Technical Support: Ric Bertrand, (512) 302-4333, Ext. 1111


## **Following Calibrations**

* Sync the internal date/time on the Manta with that on the laptop.

* Create a new data log named YYMMDD_TTL_data, using today's date. Set logging interval to 20 min.  Be sure to START LOGGING. 

* Before returning to field, install new batteries (Note: the two battery tubes have opposite orientation).

* After disconnecting the cable between Manta and computer, five red flashes on the Mata indicate that the logging is on; following the red flashes, there will be one yellow flash for each battery volt > 5.


## **Calibrations**

1. pH calibration

   1. Replace reference electrode solution each month by using a coin to remove slotted cap. Empty old solution from tube and replace with fresh electrode solution. Take care that no bubbles remain in the tube after replacing cap.

   2. pH calibration is a two-point calibration. We will use pH 7 and pH 10.

   3. Screw storage cap on to datasonde, rinse sensor well two times using DI water.

   4. Add small amount of pH 7 buffer to cup and rinse, repeat rinse (2-3 rinses).

   5. Add enough pH 7 buffer to cup to cover sensors (with datasonde sensor side up).

   6. Software &rarr; Manta2 &rarr; Calibrate &rarr; pH unit &rarr; enter sample 1 &rarr; input 7.00 &rarr; enter.

   7. Wait until graph stabilizes, press enter, accept (OK).

   8. Software will read: Enter sample 2.

   9. Rinse sensor twice with DI water.

   10. Add small amount of pH 10 buffer to cup and rinse, repeat rinse (2 rinses).

   11. Add enough pH 10 buffer to cup to fully cover sensors (with sonde sensor side up).

   12. Input 10.00 into calibration screen &rarr; enter.

   13. Wait until graph stabilizes, press enter, accept (OK).

   14. Sensor response factor should be as close to 100 as possible.

   15. When asked if you want to use a 3rd point, enter NO.


2. Conductivity calibration

   1. Rinse sensor well two times using DI water.

   2. Add small amount of conductivity standard to cup and rinse, repeat rinse (2 rinses).

   3. Add enough conductivity standard to cup to cover sensors (with datasonde sensor side up). Cup will be almost full.

   4. Software &rarr; Manta2 &rarr; Calibrate &rarr; SpCond microS/cm &rarr; enter 1413.

   5. Wait until graph stabilizes, press enter, accept (Yes).

   6. Sensor response factor should be as close to 100 as possible.


3. Turbidity calibration

   1. Turbidity calibration is a two point calibration, 0 and 100 NTU.

   2. Rinse sensor well two times using DI water.

   3. Add small amount of turbidity standard to cup and rinse, repeat rinse (2 rinses).

   4. Add enough turbidity standard to cup to cover sensors (with datasonde sensor side up). Cup will be almost full.

   5. Software &rarr; Manta2 &rarr; Calibrate &rarr; Turbidity NTU.

   6. Slope calibration &rarr; input 100, enter.

   7. Wait until graph stabilizes, press enter, accept (Yes).

   8. Sensor response factor should be as close to 100 as possible.

   9. Rinse sensor well two times using DI water.

   10. Calibrate 0 using air.

   11. Software will say "put sensor in zero solution," enter.

   12. Wait until graph stabilizes, press enter, accept (Yes).

   13. Sensor response factor should be as close to 100 as possible.


4. Depth calibration

   1. Calibrate in air - we want value to equal zero in air.

   2. Rinse sensors with DI water and remove calibration cup, making sure hole is not blocked or clogged.

   3. Software &rarr; Manta2 &rarr; Calibrate &rarr; Depth (m).

   4. Enter and press Y for yes.


5. Dissolved Oxygen calibration

   1. Use DI water or tap water to fill liter or 500 mL bottle halfway full.

   2. Shake bottle vigorously for one minute, now contains 100% air saturated water.

   3. Let water stand one minute.

   4. Software &rarr; Manta2 &rarr; Calibrate &rarr; HDO % Sat.

   5. Must have local barometric pressure for this calibration, which we get from Manta depth sensor. Remove cal cup to expose depth sensor and BP field will automatically fill.

   6. Screw storage cap back on to datasonde and add enough air saturated water to cup to cover sensors (with datasonde sensor side up). Cup will be almost full.

   7. Wait three minutes before calibration, press calibrate.

   8. Enter 100 for one point calibration.

   9. Wait until graph stabilizes, press enter, then Done to complete.

   10. Sensor response factor should be as close to 100 as possible.


6. Chlorophyll *a* uses a C fluor sensor that is factory calibrated and does not require monthly calibration.  (Rhodamine can be used as a quality control check)
 
  
7. Chlorophyll *a* calibration (with calcube)

   1. Make sure chlorophyll sensor is clean and dry.

   2. Attach CalCube to sensor, making sure it fits in secure position (only one way it will fit).

   3. **Use a flathead screwdriver to unscrew the locking nut as far as it will go.**

   4. To change the signal level, use the green screwdriver and insert the blade through the hole in the locking nut.

   5. Turn the screwdriver until it engages with the adjustment screw that is beneath the locking nut; rotate screw to adjust the signal level (clockwise &uarr;, counterclockwise &darr;).

   6. **Once the desired reading is obtained, tighten the locking nut to hold the adjustment screw tightly in place.**

   7. We adjusted the screw clockwise until it recorded 40.1. As long as CalCube is not adjusted, this reading will equal 40 &mu;g/L in the future.


8. CDOM/*f*DOM uses a C fluor sensor that is factory calibrated and does not require monthly calibration.  (PTSA can be used as a quality control check)


9. CDOM/*f*DOM Calibration (with CalCube)

   1. Make sure CDOM sensor is clean and dry.

   2. Attach CalCube to sensor, making sure it fits in secure position (only one way it will fit).

   3. Use a flathead screwdriver to unscrew the locking nut as far as it will go.

   4. To change the signal level, use the green screwdriver and insert the blade through the hole in the locking nut.

   5. Turn the screwdriver until it engages with the adjustment screw that is beneath the locking nut; rotate screw to adjust the signal level (clockwise &uarr;, counterclockwise &darr;).

   6. Make sure reading head is not too close to the sensor as it will overheat; try to find the "sweet spot" where reading increases, but stop before it decreases again (i.e., top of curve).

   7. Once the desired reading is obtained, tighten the locking nut to hold the adjustment screw tightly in place.

   8. Record the reading of the CalCube; as long as CalCube is not adjusted, this reading will equal 300 &mu;g/L (0.3 ppm).


# **Stormwater Flowlink Protocol**

Updated August 2010


1. Open Flowlink 5.1.

2. ~~Click the 'Database' button on the top of the screen and select 'Open'. Note: the 'Connect' window may open automatically upon startup, simply exit this window.~~

3. ~~After the 'Open Database' window appears, select 'Browse'.~~

4. ~~Select 'SNAZ.mbd' and click open. (Full address on the GIOS Laptop: C:\Documents and Settings\All Users\Application Data\Flowlink 5.1\SNAZ.mbd). Then click 'OK' on the 'Open Database' window.~~

5. Plug the communications cable into the ISCO (to the right of the rain gauge plug) and plug the USB end into the laptop. Note: Check to ensure the Unit is on.

6. Find the 'Quick Connect' button or press F11.

7. In the 'Connect' window, select the 'COM port' pulldown menu and select '4'. Leave the 'Baud rate on 'Default'. Make sure 'Type' is set to 'Direct'.

8. ~~If this is the first time an ISCO is being connected to Flowlink, select 'Create new site' at the bottom of the screen.~~

9. Select the large button (top left) with '4100/4200/6700 Instruments' above it.

10. Flowlink will connect to the unit and will use the 'Site Description' entered in the programming as the 'Site Name'. (If the unit is in 'Standard Programming' it will use the name of the program as the 'Site Name'.)

11. A window will appear with the Site Name at the top. Press the 'Retrieve Data' button at the bottom of this window (or press F8).

12. After Flowlink has downloaded the data, disconnect from the unit (using the 'Disconnect' button or F2) and close the Site window.

13. On the main Flowlink screen (in the 'Workspace' [the list on the left of the screen]), expand 'Sites', expand the desired site, and expand the desired ISCO (the site and ISCO should be the same name if the program was run in extended mode).

14. Double click on the data tabs (Rainfall, Level etc.). This will open the data in a graph or table named 'New Graph', 'New Graph (1)' etc. The graphs and tables can be renamed by saving them (File, Save).

15. To export the data in a graph, right click on the graph icon and select 'Export'. Enter 'C:\' in the 'To file' box and click 'Select'. Save the file as a CSV file with summary in the desired location. (A CSV file can be opened with Microsoft Excel).

16. If possible, back up the export data to an external hard drive as soon as possible. There is a Database backup feature in Flowlink.

   1. Select 'Database' from the toolbar and then select 'Backup'. This will save a compressed (.zip) file of the database.
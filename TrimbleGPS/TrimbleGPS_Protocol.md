# **Trimble Ranger Handheld and ProXH Receiver GPS Protocol**

## **Overview:**

The Trimble ProXH receiver and Ranger handheld unit are capable of sub-meter accuracy in the field and 30cm post-processed accuracy using Trimble's proprietary H-Star technology. The Ranger unit is basically a handheld PDA running Windows Mobile encapsulated in a durable case and fitted with a convenient keyboard. The Ranger and ProXH receiver communicate via Bluetooth technology, eliminating the need for cables.


## **Step 1: Charge the batteries**

Begin the charging the batteries the day before you plan to use the unit. The handheld and receiver each have internal batteries. Charging equipment is located in GWC682. There are separate chargers for each unit, each having a unique port. A full-charge should provide a full day of use.


## **Step 2 (in the lab): Creating a Project Folder in Pathfinder Office and transferring files to the handheld**

*This step is not necessary to use the GPS hardward in the field but these operations, especially creating data dictionaries, may allow more efficient use of the instrument.*

*Survey200 technicians: you must have the Survey200 dat dictionary installed on the handheld. This has probably already been done but please confirm befoe going to the field. See data transfers (Step 2b) for instructions.*


1. **Setup a project folder**

Pathfinder Office Software, ActiveSync (synchronization softward), and the connecting cable are on Scottsdale2 and a computer in the tech office. Please see Wayne Porter if you need access to a computer.

Start Pathfinder Office. Select *File > Projects* from the toolbar if the proejct dialog box does not appear automatically. Create a project on one of the servers (in your area or in a project folder). Type a name for your project. After you have created a project folder, select *Coordinate System* from the *Options* toolbar and identify an appropriate CS for your project. Note that Survey200 and all CAP LTER-specific project use the following coordinate system:

System: UTM   
Zone: 12 North   
Datum: NAD 1927 Western US   
Altitude measured from Mean Sea Level (MSL) using the defined Geoid model (EGM96 Global)

*Data Dictionaries:* Refer to the manuals or online help system regarding data dictionaries if you want to employ a menu system for entering data in the field. Creating a project-specific data dictionary can speed up recording and updating multiple features (e.g., a data dictionary would allow a pull-down menu for different plant types). A data dictionary is not necessary if you are recording simple features with minimal attributes.

2. **Transferring files from an office computer to the handheld**

Connect the handheld to the PC using the data cable. Once connected, ActiveSync should begin automatically. ActiveSync is the software that links desktops and PDAs running Windows mobile. Choose to establish a Guest Partnership if asked. Start Pathfinder Office. Select *Utilities > Data transfer* from the toolbar. Select the *Send* tab. Search for the files that you would like to load onto the handheld and *Add* each file. Choose *Transfer All*. Close the dialog box when the transfer is complete. Confirm that the files are loaded onto the handheld before disconnecting.


## **Step 3: Basic GPS operation in the field**

1. **Connect the handheld and receiver via Bluetooth**

   1. Turn on the handheld by pressing the green power button at the lower-left corner of the key pad   
   2. Turn on the receiver by pressing the green power button on the front of the unit   
   3. Open TerraSync from the *Start Menu* on the handheld

If all settings are in order, the handheld will automatically establish a link with the receiver (noted at the top of the screen with a satellite icon). If this connection does not happen automatically, select *Setup* from the top-left menu in TerraSync then press the *GPS* button on the right-hand side of the setup screen. If the link will not establish, the Bluetoth settings that facilitate communication between the handheld and receiver may need to be reset. See the Troubleshooting section at the end of the protocol for instructions.

2. **Settings**

Establish the desired coordinate system by selecting the *Setup* tab then depressing the *Coordinate system* box. Fill in the appropriate parameters. You should not need to change any other settings (for the benefit of other uses, please do not change any settings other than the coordinate system).

Monitor system status by selecting the *Status* tab. From here you can determine satellite information on the *Skyplot* screen or the *Satellite Information* screen. Note that four satellites are required for proper function. On the *Skyplot* screen, black boxes represent satellites that the receiver is using; white boxes represent satellites that the receiver has identified but is not using to compute location. From either the *Skyplot* screen or the *Setup* tab, you can change the sensitivity of the instrument using a sliding scale ranging from productivity to precision. Shifting the slider toward precision will yield more accurate data by using only the best satellite signals. Shifting the slider toward productivity will lower the tolerances regarding satellite signals and yield less precise results. Note that although higher tolerances will provide better results, it may be difficult to acquire good satellite signals from four different satellites. Signal acquisition and data logging will also require more time as the slider is moved toward Precision. Trimble representatives recommend leaving the slider mid-way between Productivity and Precision.

*Note that if the instrument has not been used for some time, it may be necessary to download a new almanac. This occurs automatically but may take 10-15 minutes during which the unit will be sluggish or perform poorly.*

To maximize accuracy: (1) obtain the best view of the sky as possible, (2) remain at the feature location long enough to log several GPS positions that will be averaged, and (3) make sure that you maintain a lock on at least four satellites for a minimum of two minutes for H-Star processing.

3. **Collecting Data**

In the **Data** section, establish a new file or open an existing file. For a new file, select *Rover* for File Type; select *Default* for Location; provide an appropriate file name; select a data dictionary (use the generic dictionary if you have not established and loaded a data dictionary). Confirm antenna height of 2.0 m. Identify the type of feature that you would like to collect (i.e., point, line, or area (more feature types will be available if you are using a custom data dictionary)). Press *Create* to begin logging; the number of logged positions is noted in the status bar at the top of the screen. Fill in the attribute table (if desired) and hit *OK*, the feature is now logged and you are returned to the collect features screen ready to collect another feature.

*The log later option:* the default setting is to begin logging positions as soon as you have created a feature (e.g., point, line, area) to collect. If you prefer to control when positions are logged, select *Log Later* from the *Options* tab (a pause sign will be displayed). When you are ready to log positions, select *Log Now*.

*Line features:* While recording a line feature, positions are logged at a regular interval as you travel along the length of the line feature. The logging interval is set in the data dictionary. If you are creating a new line feature using the generic data dictionary, you can manually set the logging interval (the default is 5 seconds). Alternatively, you can use the log later option to manually record positions along the line.

*Area features:* Area features are collected in a similar manner as line features. The first and last positions of an area feature are joined together to close the area so there is no need to return to the exact starting point.

4. **Navigating to a target**

To navigate toward a feature or predefined location, you must select it as your target. Select a feature from the **Map** or **Data** sections and select *Set Nav Target* from the **Options** Menu. Once the target has been identified, you can use the **Map** or **Navigation** screens to navigate toward the feature. Note that when you are within a few meters of the target, the view switches to the close-up screen. In the close-up screen, your position is indicated by the cross and the target is represented by the bullseye.

To identify a target that is not predefined (i.e., already loaded onto the handheld) you can manually enter coordinates. To enter coordinates, you must first create a new data file. From the **Data** section, select *New*, then *Create a new data file*, fill in appropriate file information (see 'Collecting Data' instructions listed above for details), confirm antenna height (2.0 m), select feature type (these instructions are applicable for point features, please see the manual if you want to manually enter coordinates for a line or area feature), enter an appropriate comment (e.g., feature ID) but **do not** hit OK. Select *Log Later* from the *Options* tab. Select the **Map** section. Select *Digitize* from the pull-down menu that includes the map icons (top-left corner of the screen). Select *Options*, scroll down and select *Enter coordinates*. Enter coordinates and elevation (note that the coordinate fields depend on the current coordinate system). Tap *OK*. Highlight the newly created feature in the **Map** or **Data** sections and select *Set Nav Target*.


## **Step 4: Transfer data from the handheld to an office computer**

Connect the handheld to the PC using the data cable. Once connected, ActiveSync should begin automatically. Choose to establish a Guest Partnership if asked. Start Pathfinder Office. Select *Utilities > Data transfer* from the toolbar. Select the *Receive* tab. Search for the files that you would like to transfer from the handheld and *Add* each file. Choose *Transfer All*. Close the dialog box when the transfer is complete. Disconnect and turn off the handheld.

To view the data, select *Open* from the *File* menu in the top toolbar. Select the *Map* option from the *View* menu in the top toolbar. Be sure to confirm that the data are displayed in the appropriate coordinate system by selecting *Coordinating System* from the *Options* menu.


## **Step 5: Differentially correcting data (optional but recommended)**

1. Overview

Differential correction removes errors in GPS data by comparing satellie signals to established bay-stations, improving the accuracy of GPS positions to approximately sub-meter.

2. Select the *Differential Correction* utility from the *Utilities* menu in the top toolbar. Select the file or files to be corrected. Select *Next*. For processing type, select *H-Star: Automatic H-Star Carrier and Code Processing*. Select *Next*. For most applications, the deafult settings in the Correct Settings dialog box are applicable. Please refer to the online help if you need additional information regarding these settings. Otherwise, select *Next*. Press *Select*... to select base providers. It is likely that an appropriate base provider group relevant to your area of study (i.e., within the CAP LTER boundary) has already been selected. Scroll through the list of base providers and examine the different providers. There should be a list of 3-10 providers distributed throughout central Arizona. If a predefined list of base provides does not exist OR if any of the listed providers have an integrity index < 80, select *New...* Type a group name. Press '+' to view a list of base providers. Select *Update List* to ensure that the list contains the most recent information. Identify 3-10 providers within 900 miles of your study area that have integrity indexes &ge; 80; scroll through the integrity index types (i.e., singe, dual, and code) and confirm that all the select providers have integrity indices &ge; 80 for each index type. Highlight the appropriate base providers and select *OK*. Select *OK*. At the differential correction wizard dialog box, be sure that the appropriate base provider group is identified, that the *use reference position from base providers* radio button is selected, and that the *confirm base data and position before processing* box is checked. Select *Next*. Choose output options and select *Start*. *Confirm*. *Close*. A new file is created with the corrected data.


## **Step 6: Exporting to a GIS**

Pathfinder Office is a powerful mapping program but most users are interested in exporting their GPS positions to a GIS database. In the Pathfinder Office software, select *Utilities > Export*. Select files to export and select output location. Choose an export setup, typically a Sample ESRI Shapefile Setup or Sample Microsoft Access MDB setup. Confirm that the GIS Coordinate System is correct (this can be changed in the properties dialog box). Select Properties... to change export details. Note that the default settings will be applicable for most users but it would be prudent to scroll through the tabs and note the export settings, particularly the *Attributes* that will be exported. Select *OK*. 

Please note that Pathfinder Office does not export the coordinate system information (i.e., does not create a .prj file). You must define the coordinate system of the shapefiles using ArcCatalog or ArcMap: from the ArcToolbox, select *Data Management Tools > Define Projection*.


## **Troubleshooting: handheld will not connect to receiver**

If all settings are in order, the handheld will automatically establish a link with the receiver (noted at the top of the screen with a satellite icon). If this connection does not happen automatically, select *Setup* from the top-left menu in TerraSync then press the *GPS* button on the right-hand side of the setup screen. The Bluetooth settings that facilitate communication between the handheld and receiver may already be established but the settings may need to be resert if the batteries were drained. If the settings are in order, if the handheld and receiver do not establish a link, perform the following steps:

1. On the handheld, turn on the Bluetooth radio:   
   1. Tap *Start/Settings/Connections*.   
   2. Tap the Bluetooth icon. The Bluetooth control appears.   
   3. Select the *Turn on Bluetooth* checkbox.   

2. Scan for other Bluetooth-enabled devices:   
   1. Tap the *Devices* tab.   
   2. Tap *New* to add a new device.   
   3. From the list of available devices, select the device you want to add and then tap **Next**.   
   4. Tap **Next** (a passkey is not necessary).   
   5. Tap **Finish**.   

3. Configure the connection to the GPS receiver and then make the connection:   
   1. Confirm that the GPS receiver is selected in the list of devices then select the *Com Ports* tab.   
   2. Tap *New Outgoing Port*.   
   3. Select the device you want to add and then tap **Next**.   
   4. Select the COM port you want to use for the connection from the dropdown list.   
   5. Clear the *Secure Connection* checkbox.   
   6. Tap the **OK** icon in the Navigation bar at the top of the screen.   
   7. In the COM Ports screen, verify the COM Port assignments are correct and tap **OK**.

4. Configure the field software (i.e., TerraSync) to connect to the selected GPS receiver.   
   1. Start the field software (i.e., TerraSync).   
   2. From the dropdown menu, select the *Setup* section.   
   3. Tap *GPS settings*.   
   4. From the *GPS Receiver Port* dropdown list, select the receiver you want to connect to.   
   5. Tap **OK**. 

The connection symbol appears in the status bar while the connection is made. When the connection is successful, the satellite icon appears in the status bar. Signals from four satellites are required for positioning.
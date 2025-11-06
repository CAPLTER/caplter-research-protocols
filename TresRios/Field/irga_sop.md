**Wetlands Ecosystem Ecology Lab (WEEL)**

**Standard Operating Procedure**

**Project:** Tres Rios Wetlands

**Procedure:** Infrared Gas Analyzer (IRGA) Operation – Transpiration

**Purpose**

This SOP covers the field procedures for servicing and operating the
Li-COR 6400XT IRGA and taking transpiration measurements.

**Prepping for use**

1.  Ensure that CO<sub>2</sub> Soda Lime Scrub and Desiccant chambers
    are filled. If either needs to be changed or refilled, unscrew using
    the lower knob, and unscrew the BOTTOM side only (the end opposite
    the bypass valve end). Do not try to unscrew the other end. Both
    chambers should be filled to within a millimeter or two of the
    threading.

2.  Insert a new CO<sub>2</sub> cartridge into the cylinder. Place a new
    o-ring around the tiny valve that pierces the cartridge. With the
    cartridge in the cylinder, quickly invert the cylinder (to make sure
    the cartridge remains aligned) and gently screw it onto the valve.
    When you begin to feel resistance, quickly finish screwing on the
    cylinder with a few sharp turns to ensure the CO<sub>2</sub>
    cartridge is pierced.

**Turning it on**

1.  Make sure batteries are charged. Insert one battery into each
    compartment on the underside of the machine. Make sure to slip the
    battery UNDER the pin and that it makes a loud click when the
    battery is all the way in. Connect battery power cables to the
    appropriate sockets. Two batteries will last about 5-8 hours.

2.  Power on the IRGA (flick the power switch above the batteries but
    under the big connector cables). Give it time to boot up the
    operating system.

3.  You will be prompted to select a configuration file. I created and
    have used “Tres Rios official.xml” over the summer (it is designed
    to sample the same way we have been sampling all summer). Hit enter
    to select a file. After loading the file, you will be asked if the
    IRGA is connected. Press Y for yes. You will hear the valves
    clicking and the IRGA will come to life!!

4.  You are now at the home screen. The function keys (f1, f2, etc.)
    will allow you to access the various menus options available. To
    return here from any other place in the operating system, simply hit
    escape repeatedly until it appears. Here you will see the time,
    date, and battery voltage.

**Prepping for measurements**

1.  From the home screen, press f4 to access the New Measurements
    screen. You should hear another fan kick into action. This menu is
    where all of the field measurements will be made. There will be four
    rows of items.

    1.  The top three rows are variables that the IRGA is currently
        measuring. What these variables mean can be found on pages 3-21
        and 3-21 in Book 1, Part 1 of the IRGA manual. These rows can be
        set to display any set of variables you like using the arrow
        keys on either side of the screen. Think of each as a long
        ribbon that “extends” offscreen and can be scrolled across with
        the arrow keys. The letters correspond to which set of variables
        you have selected.

    2.  The bottom row contains options that can be accessed with the
        function keys. The number keys (1, 2, 3, etc. I’ll call them
        NUM1, NUM2, etc.) will scroll through the “ribbon” of menus
        (similar to the arrow keys and the variables).

2.  *<u>To be performed each time the IRGA is powered on</u>*

    1.  Unclamp the IRGA chamber and turn the small screw at the front
        of the handle to the left a few times (lefty loosey!). Re-clamp
        the chamber. Tighten the screw (turn to the right) until the
        IRGA chamber walls touch. Now unclamp and turn the screw two to
        three half turns to the right. This ensures a snug fit without
        squeeze the foam too tight. This is more a once a day thing, not
        necessary with EACH power on.

    2.  Click NUM2 to access the access what I call the “regulatory”
        options. Here you can set the IRGA to control a number of
        variables. We are interested in the following:

        1.  Make sure the flow rate (f2) is set to 500 ums. This should
            be the default. If not, press f2 and select option F, and
            enter 500. It controls how fast air moves through the IRGA
            system.

        2.  Make sure the CO<sub>2</sub> mixer is on (it is off by
            default). Press f3, then option R, and then enter 400 (or
            just press enter, the default is 400). This controls the
            reference (ambient) CO<sub>2</sub> values to about normal
            atmospheric condition.

        3.  On the CO<sub>2</sub> scrub and desiccant tubes, ensure the
            top knob on the soda lime is turned all the way to scrub
            (follow the arrow) but not too tight. Turn the desiccant top
            knob towards bypass (again, not too tight). This essentially
            allows the machine to fully regulate (“scrub”) reference
            CO<sub>2</sub> using the mixer, but leave water vapor at the
            normal ambient conditions.

    3.  With the mixer on, we need to backtrack a bit. Hit ESCAPE to
        return to the home menu, then f3 to enter the calibration menu.
        Select the CO<sub>2</sub> mixer dropdown list, and then
        “Calibrate…” Press Y to begin the calibration. It will now
        attempt to max out CO<sub>2</sub> flow. After, it will prompt
        you to continue, hit Y for yes. It will now use varying voltages
        to adjust CO<sub>2</sub> flow at 8 different voltage levels.
        Once it has finished (about 5-10 min), press Y to plot the
        results, ESCAPE to exit the plot, and then Y to implement the
        calibration.

    4.  Defining stability. A cool feature of the IRGA is the to “watch”
        a variable(s) over a set period of time and has notify you when
        it has reached a pre-defined definition of stability (useful for
        being consistent). Press NUM4 and then f4 (Define Stablty) to
        define this. With the Tres Rios Official configuration you
        selected, the default should be “Trmmol” (transpiration) with
        slope\<.5 and standard deviation\<.5. Use the controls here to
        add variables, or edit the current ones. You can adjust how
        “tight” you want the stability definition to be with the edit
        key (f1). When you’re happy, hit f5 to exit.

3.  *<u>To be performed before each transect (or every few hours, or
    when climactic conditions change rapidly)</u>*

    1.  Matching. A full explanation can be found in Book 1, Part 1,
        pgs. 4-33 to 4-38. Essentially, this zeroes the difference in
        gas flux readings between the sample cell and the reference
        value. Kind of like taring a balance.

        1.  Enter the New Measurements menu, press NUM1 to show the
            appropriate set of menu options, and then f5 to enter the
            matching mode. CLOSE THE CHAMBER AND ALLOW H2O FLUX AND CO2
            FLUX (variable group B, deltaCO2 and deltaH2O) TO (more or
            less) STABILIZE BEFORE ENTERING MATCH MODE.

        2.  The IRGA will wait until stabilization or until the
            countdown finishes (usually the former). Press f5 (MATCH
            IRGA) to match, and then f1 to exit once this is done

        3.  You may get some error messages here. It will mention
            something about a leak if CO2 flux changes too much. Just
            exit match mode, wait a few seconds (make sure the chamber
            is closed) and try again. If something else pops up, consult
            Book 1, Part 1, page 4-37.

    2.  At the New Measurements menu, press NUM1 to bring up the default
        option ribbon, then f1 to “OpenLogFile.” Here you have the
        option to type in the name of a new log file, which essentially
        creates a new excel spreadsheet in the IRGA file system, or use
        the arrow keys to select a new one

        1.  NOTE: selecting an existing file will allow you to overwrite
            (O), append (A), or cancel (C). DO NOT OVERWRITE OR YOU WILL
            LOSE THE FILE. You may append if you have closed a file by
            accident. This will just create a new file with the old
            file’s name plus “\_1” at the end. You will have to combine
            these spreadsheets on the computer later.

    3.  After creating your log file or appending an existing one, you
        will be prompted to enter a remark. Unless you’d like to let the
        IRGA know how you’re feeling today, just hit enter to skip this.

    4.  You’ll notice the NUM1 option ribbon has changed. f1 is now the
        LOG key.

    5.  Adjust the variable ribbons to your liking. One good
        configuration for Tres Rios sampling is choosing groups B, C,
        and K (from top to bottom). Group K is very important as the
        “stable” variable will be displayed. This allows you to monitor
        how many of the stabilities variables you defined are stable.

**TAKING MEASUREMENTS (finally!!!)**

6.  Clamp on to your leaf. Measurements are taken at the bottom or top
    of a plant.

    1.  The bottom measurements should be taken as close to the lowest
        leaf node (if there are leaves) or bottom of plant as possible.
        Try to pick a spot that has already been sitting the shade of
        the canopy, and keep the leaf as much in that same shade as
        possible. The top measurements should be taken on a leaf already
        in strong sunlight, within 10-20 cm of the tip of the
        leaf/plant, but not at the tip (ET drops off at the leaf tips,
        and the tip is usually dead).

    2.  Try not to change the orientation of the IRGA once clamped. This
        can affect gas flux and light intensity, especially. LIGHT IS
        KEY HERE. ET “machinery” in the leaf is very sensitive to
        changes in light intensity.

    3.  The in-chamber light sensor (the chip inside the plastic window)
        should be kept in the same light condition as as the leaf. You
        can *try* to do this for the external sensor as well, but we
        haven’t used measurements from that sensor so far (large chance
        that they don’t represent the same conditions that the leaf is
        in due to the distance between the two).

    4.  For all plants with thick stems (even some Typha leaves), use
        the custom foam chamber walls that have been made. The
        “cassette” looking white foam pad is inserted just “behind” the
        chamber, lined up with the three big gas exchange holes that you
        can see. This maintains the flow of gas. Also loosen the
        strength of the clamp so that the leaf is not crushed. It may
        take a few turns of the screw to the left. It also may take some
        tinkering to get all the foam pieces lined up and the leaf
        inserted. Make sure to retighten the seal when finished using
        the “foamies.”

    5.  ***<u>MAKE THIS A HABIT:</u>*** When you clamp onto a leaf,
        estimate the leaf surface area. The entire chamber is (the
        smaller window if viewed from above) is 6 cm<sup>2</sup>, or 2
        cm by 3 cm. Just eyeball it. If the leave fills 2/3 of the
        chamber, your area is 4 cm<sup>2</sup>! Don’t be afraid to go in
        increments of .5 (1.5, 2.5, etc.). Call this out to the IRGA
        scribe (or just enter it yourself if you’re solo).

        1.  ***<u>TO ENTER LEAF AREA:</u>*** Press NUM3, then f1, then
            type in the leaf area and hit enter. This is a crucial as
            the IRGA scales certain variables (including ET) depending
            on leaf area.

    6.  If using the stability setting, watch for all of your variables
        you defined to be stable (1/1, 2/2, etc.). Then press NUM1 and
        then f1 to log you data point!

    7.  The IRGA will now prompt you to enter some info about your data
        point. Type on the keyboard to answer the prompts and hit enter
        to record your data. There should be a triumphant BEEP when you
        finish.

        1.  Once you have hit the log button and are answering prompts,
            you may unclamp from your leaf. The data has already been
            saved.

        2.  If you screw up on typing something, don’t panic. Just
            finish logging the point, and then hit NUM1 and then f4 to
            add a remark. This will add a new line in your spreadsheet.
            You can type something like “Ignore last log” or “I’m a
            bonehead!”

    8.  Repeat this log procedure ad infinitum (or nauseum, whichever
        comes first)

    9.  The IRGA has an awesome function that lets you view your data on
        the fly, in case you need to check if you’ve already taken a
        certain measurement

        1.  Press NUM1, f2, and then choose the option “view data as
            stored”

        2.  Use the arrow keys to scroll through this “excel”
            spreadsheet.

        3.  Press ESCAPE to exit when finished.

**After the field**

1.  *<u>DOWNLOADING IRGA DATA</u>*

    1.  There is a black cable in the “Tres Rios Stuff” drawer in
        Rm. 205. One end has an Ethernet plug, the other has a “Rugged
        CF 10/1000 card” plug. This is what we need to connect to the
        computer

    2.  Power on the IRGA until you get to the home screen.

    3.  There is a small latch on one of the longer sides of the IRGA.
        Unscrew the little screw and open the latch. This is IRGA’s port
        for interfacing with the computer.

    4.  At this point, connect the Ethernet end to a computer, and the
        card end gets slotted into the IRGA’s port (be careful to line
        the card up properly with the slot…there’s some room for error)

    5.  On a Mac (check the manual for how-to on windows), simply right
        click on Finder, click “Connect to server…” and type in
        “smb://PSC-3149.local.” and click connect. You can save this to
        your favorite servers for ease-of-use in the future (I’ve done
        this on “my” computer).

    6.  You will be prompted for a username and password. Enter “lpl”
        for both.

    7.  You are now in the IRGA’s file directory. Click on the User
        folder to access the data files.

    8.  Each log file that you created in the New Measurements menu
        while in the field will be stored here as both an .xls format
        and another format that the IRGA uses. The .xls file is your
        Excel spreadsheet, so drag this onto the desktop or into the
        folder of your choice.

    9.  You can leave the files in the IRGA, but if things get too
        cluttered you can delete whichever files you want and they will
        be removed permanently from the IRGA. Make sure you have
        back-ups!!!!

    10. Open up your .xls file and be BLOWN AWAY by the unbelievable
        tidiness and complexity of the IRGA’s measurements.

2.  *<u>PUTTING IRGA TO REST</u>*

    1.  Power down IRGA after downloading data. Remove any batteries and
        plug them in to charge.

    2.  Unscrew the CO<sub>2</sub> mixer chamber (there may be a hiss
        due to leftover compressed CO<sub>2</sub>). Toss the old O-ring
        and cartridge in the garbage. Lightly screw the chamber back on
        to hold it in place until next time.

    3.  Batteries are charging when the “Charge” light is illuminated.
        When this light is off, any connected batteries are fully
        charged. You may remove them and store them where you’d like. DO
        NOT STORE THE BATTERIES WITH LOW OR NO CHARGE, THIS AFFECTS
        THEIR CAPACITY TO HOLD CHARGE.

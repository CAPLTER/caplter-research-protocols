**Wetlands Ecosystem Ecology Lab (WEEL)**

**Standard Operating Procedure**

**Project:** Tres Rios Wetlands

**Procedure:** Water Budget Data Entry – precipitation, inflow/outflow,
weather station

Updated: 8/19/2022

**Purpose**

This SOP provides information for entering data from City of Phoenix
(CoP) and AZ Meteorological Network datasheets for water budget analysis
from Tres Rios wetlands.

**Potential Hazards**

None

**Materials**

- CoP meteorological datasheet

- AZ Meteorological Network raw hourly and daily datasheet – [Buckeye
  Station](https://cals.arizona.edu/AZMET/26.htm)

- CoP inflow/outflow datasheet

- tr_metstation_data.csv excel sheet

- tr_precip_timeseries.csv excel sheet

- tr_waterflow_data.csv excel sheet

- CoP met station cheat sheet card

- AZ Met raw data file formats cheat sheet

**Procedures**

All data required for these files come from external sources. You will
need to contact the City of Phoenix for the met station and flow data
for the desired dates (WSD HARS Support: <hars.support@phoenix.gov>). It
is a good idea to attach examples of the datasheets so the HARS Team has
a specific idea of what you need. An example email is listed below. Use
the Met Data cheat sheet card to help you navigate which Tag
Descriptions go with which column in the Tres Rios file

Remember to:

- Freeze top rows of each dataset to avoid mistakes when entering data.

- Use the “Filter and Sort” feature to isolate met station outputs

- Make sure all measurement units match up

- Double check the values make sense in case of sensor failure

- “Paste Special” as Values only

**Inflow/outflow data**

- Email the CoP’s HARS Team to request flow data for the desired dates.

- Update the tr_waterflow_data.csv excel sheet to reflect the dates you
  will be adding

- Copy/paste flow values

**Precipitation**

- Access the AZ Meteorological Network raw data <u>daily</u> datasheet –
  [Buckeye Station](https://cals.arizona.edu/AZMET/26.htm). The dataset
  will open in a new window as one large text. “Command + A” to
  highlight the entire text. Copy/paste these data into a NEW excel
  sheet or window.

- Use the “Text to Columns” feature to separate the values from one
  another. Text to Columns delimited Comma Finish.

- The raw data file format cheat sheet will tell you the description for
  each data point and highlights which columns you need to focus on (A,
  B, and L).

<!-- -->

- Calculate the day of the year in which your data entry starts and
  match that with the same day on the AZ met datasheet. Copy/paste
  values in the tr_precip_timeseries.csv excel sheet.

**Meteorological Station:**

- Email the CoP’s HARS Team to request met station data for the desired
  dates.

- Freeze top rows of each dataset to avoid mistakes when entering data.

- Update the tr_metstation_data.csv excel sheet to reflect the daily and
  hourly points that you will be adding

- Use the “Filter and Sort” feature to isolate the met station tag
  descriptions that are listed on the COP Met Station cheat sheet and
  match them with their counterpart on the Tres Rios csv file. One by
  one, copy/Paste special as Values.

  - **NOTE:** The temperature on the COP datasheet is in Fahrenheit and
    will need to be converted to Celsius.

  - Do this by copying the Fahrenheit values into a new sheet in
    Column A. In Column B, type the formula =CONVERT(A1, “F”, “C”) and
    drop down so it applies to all the cells. Column B will now show the
    converted temperatures in Celsius.

  - Use these to Copy/Paste special as Values back into the original
    tr_metstation_data.csv and delete the extra sheet

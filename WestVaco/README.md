# GRAL Validation Data Set West Vaco<br>
This is a dataset with a stack source and complex terrain:  Terrain, Rural, Non-downwash, Independent<br>
The data set contains a GRAMM project. With this project a pool of wind fields was calculated for an artificial wind rose. These wind fields are not stored here for lack of space. <br>
The GRAMM wind field was fitted to the measured wind data with the GUI Match to Observation function. <br>
**The calculation of this data set requires considerable computing power** because the calculation is performed with the GRAL transient function and time series for the emission rate, the exit temperature and the exit velocity.<br><br>
You must follow these steps to (re)calculate the validation model:<br>
1. calculate the GRAMM wind field for the artificial wind rose. This calculation will take 1 to 2 days.
2. set a reference to the GRAMM wind field in the GRAL project
3. perform a match-to-observation function to select the best matched calculated wind fields (to the measured data at the measurement site). For this purpose you can use the already configured match settings file "MatchFile.mmo".
4. start the GRAL calculation, the calculation time depends on your hardware but this data set can take 1 to 3 days to complete<br><br>

On request I can offer the matched GRAMM wind fields on a download server, then you can start directly at step 4. <br>

Download: <a href="WestVaco.zip" download>Click to Download</a>

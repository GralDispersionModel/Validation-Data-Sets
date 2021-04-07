# GRAL Validation Test Case West Vaco<br>
This is a test case with a stack source and complex terrain:  Terrain, Rural, Non-downwash<br>
The GRAL test case was developed based on an AERMOD evaluation test case (EPA-454/R-03-003): 
https://www.epa.gov/scram/air-quality-dispersion-modeling-preferred-and-recommended-models.<br>

The data set contains a GRAMM project. With this project a pool of wind fields was calculated for an artificial wind rose. These wind fields are not stored here due to size constraints. <br>
The GRAMM wind field was fitted to the measured wind data with the GUI "Match to Observation" function. <br>
**The calculation of this test case requires considerable computing power** because the calculation is performed with the GRAL transient function and time series for the emission rate, the exit temperature and the exit velocity.<br><br>
You must follow these steps to (re)calculate the validation model:<br>
1. Use the GRAMM project and calculate the GRAMM wind field for the artificial wind rose. This calculation will take 1 to 2 days.
2. Use the GRAL project and set a reference to the calculated GRAMM wind field files
3. Perform a match-to-observation function to select the best matched calculated wind fields (to the measured data at the measurement site). For this purpose you can use the already configured match settings file "MatchFile.mmo".
4. Start the GRAL calculation. The calculation time depends on your hardware but this test case can take 1 to 3 days to complete<br><br>

**Download the validation test case:** <a href="WestVaco.zip" download>Click to Download</a>

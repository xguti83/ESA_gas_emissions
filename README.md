# ESA_gas_emissions

Description of the column contents in the different excel files of the repository

SantaAna_eval_results.xlsx and SanMiguel_eval_results.xlsx

SCD
COLUMNS:
[date]: date in UTC;
[instrument]: serial number of the instrument;
[station]: name of the NOVAC station;
[Angle]: angular orientation of the center of the plume as seen from the instrument's zenith direction;
[SO2]: SO2 dSCD in molec/cm^2;
[SO2e]: DOAS fit error of the SO2 dSCD in molec/cm^2;
[Chi_SO2]: chi^2 fit quality of the SO2 DOAS fit;
[DELTA_SO2]: peak-to-peak maximum of the residuum of the SO2 DOAS fit;
[Shift_SO2]: Levenberg-Marquardt shift of the linked absorption cross sections, for the SO2 DOAS fit in nm;
[Squee_SO2]: Levenberg-Marquardt squeeze of the linked absorption cross sections, for the SO2 DOAS fit in nm;
[BrO]: BrO dSCD in molec/cm^2;
[BrOe]: DOAS fit error of the BrO dSCD in molec/cm^2;
[Chi_BrO]: chi^2 fit quality of the BrO DOAS fit;
[DELTA_BrO]: peak-to-peak maximum of the residuum of the BrO DOAS fit;
[Shift_BrO]: Levenberg-Marquardt shift of the linked absorption cross sections, for the BrO DOAS fit in nm;
[Squee_BrO]: Levenberg-Marquardt squeeze of the linked absorption cross sections, for the BrO DOAS fit in nm;
[BrS]: BrO to SO2 molar ratio in 10^-5;
[BrSe]: spectroscopic retrieval error of the BrO to SO2 molar ratio in 10^-5.

daily_SO2Emiss
COLUMNS:
[date]: date in UTC;
[instrument]: serial number of the instrument;
[station]: name of the NOVAC station;
[flux]: SO2 emission flux in 1000 tons per day (extrapolated from momentary flux rate);
[ISO2]: integral of the SO2 VCDs in molec/cm^2 x ° (i.e. not yet scaled with the plume height);
[centre]: plume centre according to the Gaussian fit; [offset]: mean SO2 dSCD of the background spectra;
[gauss]: ratio of the discrete integral of the SO2 VCDs and the integral of the SO2 VCDs suggested by the Gaussion fit;
[gauss_offset]: offset of the Gaussian fit in 10^17 molec/cm^2;
[BG]: absolute background SO2 VCD;
[WS]: wind speed in m/s;
[WD]: wind direction in degree with 0 = northerly and 90 = easterly.


SantaAna_MultiGAS_result and SanMiguel_MultiGAS_results.xlsx

RatioCalc_results
COLUMNS
[Date]: date in UTC;
[intrument]: name of MultiGAS used on the field;
[Time inic]: starting time of evaluated timewindow in UTC;
[Time end]: ending time of evaluated time window in UTC;
[sampling place]: name of sampling locations;
[SO2 max]: SO2 maximum concentration in ppmv;
[CO2/SO2], [H2S/SO2], [H2/SO2], [H2O/SO2]: calculated molar gas ratio	for the selected time period;
[r^2]: value of the best fit line obtained with the data used within the selected time period;
[error]: error of the calculated molar gas ratio
[data points]: number of data points within the selected time period

Statistics
COLUMNS
[Date]: date in UTC;
[Instrument]: name of MultiGAS device used on the field;
[Place]: sampling location;
[SO2 max (ppmv)]: SO2 maximum concentration in ppmv;
[CO2/SO2], [H2S/SO2], [H2/SO2], [H2O/SO2]: calculated mean molar gas ratio of the day; 	
[Error]: error of the mean molar gas ratio;
[CO2 (mol%)],	[H2S (mol%)],	[H2 (mol%)],	[H2O (mol%)],	[SO2 (%mol)]: CO2, H2S, H2, H2O and SO2 molar fractions in mol%



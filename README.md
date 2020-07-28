# Data-Analysis-Air-Quality

**Air Quality Analysis**


The data contains the responses of a gas multisensor device deployed on the field in an Italian city. Hourly responses averages are recorded along with gas concentrations references from a certified analyzer.

Retrieved from: UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Air+quality)


*Introduction:*

The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level, within an Italian city.


*Time Frame:*

Data were recorded from March 2004 to February 2005 (one year) representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer.

Evidences of cross-sensitivities as well as both concept and sensor drifts are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors concentration estimation capabilities.

Missing values are tagged with -200 value.


*Attributes of the dataset are:*


Date -Date (DD/MM/YYYY)

Time -Time (HH.MM.SS)

CO(GT) -True hourly averaged concentration CO in mg/m^3 (reference analyzer)

PT08.S1(CO) -PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)

NMHC(GT) -True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)

C6H6(GT) -True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)

PT08.S2(NMHC) -PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)

NOx(GT) -True hourly averaged NOx concentration in ppb (reference analyzer)

PT08.S3(NOx) -PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)

NO2(GT) -True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)

PT08.S4(NO2) -PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)

PT08.S5(O3) -PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)

T -Temperature in °C

RH -Relative Humidity (%)

AH -Absolute Humidity

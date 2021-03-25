# GeologicalSurveyDataReader
A GUI-driven application that takes user input on starting date, end date, and an HUC from the USGS to produce data in a readable way about some watershed.

This is a GUI-driven application that fetches information from the US Geological Survey for a specific watershed through dates specified by the user. The user inputs the start date, end date, and the 8-digit Hydrolic Unit Code (HUC) for the desired area of interest.

The code then outputs data on the average water temperature, average air temperature, average wind speed, and water discharge over the specified days. A graph is then made for each of these as well for al the specified time.

Note: Most US Geological Survey sites do not have this sort of timeseries data aailable for it. You can find more information on HUC on their website:
https://waterdata.usgs.gov/nwis/dv?referred_module=sw&search_criteria=state_cd&search_criteria=site_tp_cd&submitted_form=introduction

https://water.usgs.gov/wsc/map_index.html

https://water.usgs.gov/wsc/findwatershed.html

The code i the Jupyter notebook was run with the sample input: 

3/5/2021 3/15/2021 08048000

Note that all input dates must be in this format, with spaces between each entry.

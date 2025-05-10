# optimizer
This folder contains the following files:
- <em>SWT_3.6_120.yaml</em> is the FLORIS Turbine object configured with the SWT-3.6-120 characteristics.
- <em>WF_coordinates.xlsx</em> contains turbine coordinates of the London Array wind farm.
- <em>cc.yaml</em> is the FLORIS Cumulative Gauss Curl input file.
- <em>da_data_11.xlsx</em> contains hourly data of wind speed (average and standard deviation), wind direction (average and standard deviation), turbulence intensity, and day-ahead spot price for April 11, 2105.
- <em>da_data_12.xlsx</em> contains hourly data of wind speed (average and standard deviation), wind direction (average and standard deviation), turbulence intensity, and day-ahead spot price for April 12, 2105.
- <em>fr_data.xlsx</em> contains the data necessary for the construction of the CDF of FR.
- <em>optimizer.ipynb</em> is the python code used to run the optimal wind farm energy and reserve scheduling model. It uses all the files above, except one of the two <em>da_data.xlsx</em>, from which only one is chosen, depending on the case study day.

# pset3

Data:
The data file for this problem set is at: 

  /bsc4452/share/Class_Files/data/CO-OPS_8727520_wl.csv

The file is also in the Class_Files git repo here.Links to an external site.

Metadata:
The file CO-OPS_8727520_wl.csvLinks to an external site. is the water level observations at Cedar Key, FL, from 9/26/2024 to 9/27/2024 during the landfall of Hurricane Helene.

The data were downloaded on 9/29/204 from: https://tidesandcurrents.noaa.gov/Links to an external site.

The columns are fairly self-explanatory:

Date
Time (GMT)
Predicted (ft): Predicted tide level
Preliminary (ft): Observed tide level, preliminary data
Verified (ft): No verified data when downloaded
 

Problem 1 (5 pts):
Write a script (or Jupyter Notebook code block) that opens the file, uses a for loop to read through the file line by line and, after finishing reading through the file, reports the highest water level and the date and time that was observed.

 

Problem 2 (5 pts):
Either in a new script or modifying the above script, calculate the lowest, highest and average water level observed during the time period. As above, print the date and time for the lowest and highest readings. 

 

Problem 3 (5 pts):
Write a script (or Jupyter Notebook) that calculates the fastest rise in water level per 6-minute period between measurements (for this assignment, assume that each line of the dataset is a 6-minute interval) and reports the date and time that was observed and the change in water level from the previous recording.

 

Problem 4 (5 pts):
Imagine that the file is providing live readings of the water level. Write a script (or Jupyter Notebook) to print a line of text with a warning if any of these events occur:

The water level increases more than 0.25 since the previous recording.
The water level is over 5.0.
No reading is received at a time point.
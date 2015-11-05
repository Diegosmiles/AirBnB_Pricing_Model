In order to get the files for the ipython notebook, I used some spatial analysis tools:


0) separate the NYC maps into boroughs

1) I divided listings data into Manhattan and Brooklyn

bnb_manhattan.shp
bnb_brooklyn.shp

2) Create a buffer around the MTA stops in Manhattan and brooklyn

br_stops_buffer
man_stops_buffer

3) intersect listings in step 1 with buffers in step 2, and get:

man_bnb_near_stops
br_bnb_near_stops


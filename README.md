# Taxi-demand-prediction-in-New-York-City
The objective of this real world case study is to predict number of pickups for each region in New York City for every 10 minute interval.
## Data Information
<br>Ge the data from : http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml (2016 data) <br/>The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC)

### Information on taxis:
Yellow Taxi: Yellow Medallion Taxicabs
These are the famous NYC yellow taxis that provide transportation exclusively through street-hails. The number of taxicabs is limited by a finite number of medallions issued by the TLC. You access this mode of transportation by standing in the street and hailing an available taxi with your hand. The pickups are not pre-arranged.

### For Hire Vehicles (FHVs)
FHV transportation is accessed by a pre-arrangement with a dispatcher or limo company. These FHVs are not permitted to pick up passengers via street hails, as those rides are not considered pre-arranged.

### Green Taxi: Street Hail Livery (SHL)
The SHL program will allow livery vehicle owners to license and outfit their vehicles with green borough taxi branding, meters, credit card machines, and ultimately the right to accept street hails in addition to pre-arranged rides.

Credits: Quora

Footnote:
In the given notebook we are considering only the yellow taxis for the time period between Jan - Mar 2015 & Jan - Mar 2016
## Performance metrics
<br>Mean Absolute percentage error<br/>
<br>Mean Squared error<br/>
## Steps Involved 
<br>Data Cleaning<br/>
<br>Data Clustering/ segmentation<br/>
<br>Modeling<br/>
<br>Error Metric Evaluation<br/>
## Results
<br>Error Metric Matrix (Tree Based Regression Methods) -  MAPE <br/>
<br>--------------------------------------------------------------------------------------------------------<br/>
<br>Baseline Model -                             Train:  0.140052758787       Test:  0.136531257048<br/>
<br>Exponential Averages Forecasting -           Train:  0.13289968436        Test:  0.129361804204<br/>
<br>Linear Regression -                          Train:  0.13331572016        Test:  0.129120299401<br/>
<br>Random Forest Regression -                   Train:  0.0917619544199      Test:  0.127244647137<br/>
<br>XgBoost Regression -                         Train:  0.129387355679       Test:  0.126861699078<br/>

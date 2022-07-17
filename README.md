# Bikesharing Challenge
This project is an exercise for the Columbia University Data Science Bootcamp in using and displaying data with Tableau.

## Links
- Data was obtained from:
  - [https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
- Tableau Storyboard can be found at:
  - [https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/AnalysisofCitibikeData](https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/AnalysisofCitibikeData)

## Deliverable 1 - Datetime Conversion
The `tripduration` column was converted to a datetime as per the code in (NYC_CitiBike_Challenge.ipynb)[NYC_CitiBike_Challenge.ipynb].
- Rather than replacing the column, a new column called `tripduration_conv` was created to hold the conversion.
- As well, I created a second conversion as `tripduration_conv_trim` to hold only the hour, minute, and second of the datetime, but this was not as useful for Tableau, so it remains unused.
- The DataFrame was exported to a modified **.csv** file without an index.

## Deliverable 2 - Visualizations
All visualizations will be present on story panels in one aspect or another.  If you would like to view a specific visualization, they can be found at the following sheets:
### Create the Checkout Times for Users Viz
[`Checkout Times for Users`](https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/CheckoutTimesforUsers)
### Create the Checkout Times by Gender Viz
[`Checkout Times by Gender`](https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/CheckoutTimesbyGender)
### Create the Trips by Weekday for Each Hour Viz
[`Trips by Weekday per Hour`](https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/TripsbyWeekdayperHour)
### Create the Trips by Gender (Weekday per Hour) Viz
[`Trips by Gender (Weekday per Hour)`](https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/TripsbyGenderWeekdayperHour)
### Create the User Trips by Gender by Weekday Viz
[`User Trips by Gender by Weekday`](https://public.tableau.com/app/profile/ross.eldridge/viz/ColumbiaDataBootcampChallenge14/UserTripsbyGenderbyWeekday)

## Deliverable 3 - Analysis

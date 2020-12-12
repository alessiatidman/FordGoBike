# data-visualisation

For part 5 of Udacity's Data Analyst Nanodegree. I analysed Ford GoBike dataset of San Fransisco area from February 2019 to see how factors may impact trip duration.

## Summary

The data was provided by Udacity and unfortunately no longer available through Ford GoBikes as it has now been taken out of service. The data consisted of about 183,400 entries from February 2019 located in the San Fransisco area. After cleaning, I was left with the following Variables
* `duration_sec` - `duration_min` was added after
* `start_time` and `end_time`
* `start_station_id` and `end_station_id`
* `start_station_name` and `end_station_name`
* `bike_id
* `user_type` - “Subscriber” = Member or “Customer” = Casual
* `member_birth_year` - this was later used to create `age`
* `member_gender`
* `bike_share_for_all_trip`

## Libraries Used

To complete this project, I used the following:
* Pandas
* Numpy
* Matplotlib
* Seaborn 

## Files

* `exploratory_analysis.ipynb` - this contains all gathering, assessing, cleaning and exploratory analysis.
* `explanation-slide-deck.ipynb` - the notebook that forms the slide deck.
* `201902-fordgobike-tripdata.csv` - original dataset
* `ford_gobike_master.csv` - cleaned dataset. Please note that `age` and `duration_min` varaibles will need to be created.

## Key Insights

In the presentation, I initially look at the distribution of trip duration, age and gender. Here we can see that the majority of trips were around 10 minutes, Men were seen to use the service more and those in their 30s.

I then look at the relationship between duration and age and then gender. Here, I used a violin plots, scatter plots and bar plots.

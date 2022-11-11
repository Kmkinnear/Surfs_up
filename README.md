# Surfs_up

## Project Overview
The purpose of this project was to further examine information about the temperature trends in Oahu for the months of June and December that would help in determining if the surf shop business would be sustainable year-round. We also decided to look at rainfall amounts for June and December since we thought that would be another valuable piece of information. We remembered that earlier in the module, W. Avy was concerned about the amount of precipiation in Oahu. 

## Results

### Deliverable 1 - June Temperature
The first thing that we wanted to look at was the temperature trends for all of the June data that we had in our dataset. We had to write a query that would filter the data and only return data for the month of June.

![image](https://user-images.githubusercontent.com/110848660/201247919-c354bca8-f01f-48e3-83b2-b0e8fcc91f1f.png)

The next thing that we wanted to do was convert our June temperature query to a list and then create a dataframe from that list that we'd be able to run some summary statistics on. 

![image](https://user-images.githubusercontent.com/110848660/201248679-a0ecf4a7-1f7f-466b-ac6b-bdf737be96c8.png)

![image](https://user-images.githubusercontent.com/110848660/201248732-3385e622-6ef1-4931-ba5c-bae60c99828d.png)

![image](https://user-images.githubusercontent.com/110848660/201248842-30622dcb-f32b-4203-8d94-02f1ac65ee95.png)

### Deliverable 2 - December Temperatures
The goal of this deliverable was to complete the same query but to adjust it to pull all the data for the month of December. We were able to use the same code throughout the deliverable while making some minor tweaks to capture December data instead of June.

![image](https://user-images.githubusercontent.com/110848660/201249176-2841088e-826a-450e-bf31-5d434af03d45.png)

![image](https://user-images.githubusercontent.com/110848660/201249209-2efbec4c-dc42-40ed-8f88-eb3ecdcb4e55.png)

![image](https://user-images.githubusercontent.com/110848660/201249282-5ad8f258-6d00-4093-8262-c19c426ef981.png)

![image](https://user-images.githubusercontent.com/110848660/201249323-d2f4bd7c-d4aa-400c-b425-75f43ffe834d.png)

- The first takeaway that we have from comparing the temperature between June and December is that there isn't much variance in the "mean" temperature between the two months. We can see that the mean June temperature is 74.94 degrees and the mean temperature for December is 71 degrees which is only a difference of 3 degrees.

- We wanted to look at the "min" temperature next for our second takeaway. We assumed it would be valuable to look at the "min" temperature since one of the months (December) in our datasets is traditionally one of the coldest months in most areas of the country. We looked at the two months "min" temperatures and saw more of a variance than we did when we compared the average temperatures. The min temperature in June was 64 degrees while the min temperature in December was 56 degrees for a difference of 8 degrees.

- The last takeaway was with checking to see if we had a sufficient amount of temperature observations between our two months that we observed. We wanted to make sure that it was consistent throughout the year to make sure that our data was not skewed. We're able to see that we had a "count" of 1,700 temperature observations in June and 1,517 temperature observations in December. This is a difference of about 200 total observations between the two months. Despite the temperature count discrepancy, we feel like there is sufficient data to make an honest comparison between the two months as it relates to temperature since this data was over multiple years.

## Summary

As we mentioned above, we believe there is sufficient data to be able to make a confident decision on what kind of weather we can expect to see in Oahu in June and December. The average temperatures are very similar between the two months despite one of the months falling in the summer and one in the winter. The main difference we saw was in the minimum temperature we observed, and this was primarily due to the time of the year. We would've liked to see a more consistent total count of observations throughout the year but being off by 200 observations over the course of multiple years didn't seem to cause too much alarm with the data.

As part of the final part of our analysis between the two months, we decided to look at the precipitation numbers and compare them because we knew that W. Avy had previously voiced concerns about there possibly being too much precipitation. To put him at ease we decided to run the precipiration totals to go along with our temperature data. 

We ended up using some of the same code that we used to pull the temperature data however, we made one small change to pull "prcp" data instead of "tobs". We followed the same process of creating a list with the data, creating a dataframe, and then running summary statistics on them. You can see the queries that we used and the summary statistics below for June and December.

![image](https://user-images.githubusercontent.com/110848660/201251645-da20c43e-f3be-4a70-ab01-07fd3273302b.png)

![image](https://user-images.githubusercontent.com/110848660/201251810-102b22e2-0dfb-451b-87c9-4af632baa145.png)

![image](https://user-images.githubusercontent.com/110848660/201251988-0b85f779-41a7-40e8-a438-84196df17c31.png)

![image](https://user-images.githubusercontent.com/110848660/201252077-70a868fc-cc2b-4aaf-baf1-be3e951de6b0.png)

- We can see from the summary statistics from the two months that December is the wettest of the two months. The "mean" rainfall for June was 0.13 inches compared to .21 inches for June. We also looked at the max rainfall for June which was 4.43 inches while the max for December was 6.42 inches. We also wanted to look at the total observation count to make sure we are getting a fair dataset and see that there was a total of 1,574 observations in June and 1,405 observations in December. This was a difference of about 100 total observations.

Overall, we feel confident in the data we pulled and believe that it will help W. Avly and us make a confident decision on whether to open the surf shop.

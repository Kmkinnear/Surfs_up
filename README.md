# Surfs_up

## Project Overview
The purpose of this project was to further examine information about the temperature trends in Oahu for the months of June and December that would help in determining if the surf shop business would be sustainable year-round. We also decided to take a look at rainfall amounts for June and December since we thought that would be another valuable piece of information. We remembered that in that earlier in the module, W. Avy was concerned about the amount of percipiation in Oahu. 

## Results

### Deliverable 1 - June Temperature
The first thing that we wanted to look at the was temperature trends for all of the June data that we had in our dataset. We had had to right a query that would filter the data and only return data for the month of June.

![image](https://user-images.githubusercontent.com/110848660/201247919-c354bca8-f01f-48e3-83b2-b0e8fcc91f1f.png)

The next thing that we wanted to do was convert our June temperature query to a list and then create a dataframe from that list that we'd be able to run some summary statistics on. 

![image](https://user-images.githubusercontent.com/110848660/201248679-a0ecf4a7-1f7f-466b-ac6b-bdf737be96c8.png)

![image](https://user-images.githubusercontent.com/110848660/201248732-3385e622-6ef1-4931-ba5c-bae60c99828d.png)

![image](https://user-images.githubusercontent.com/110848660/201248842-30622dcb-f32b-4203-8d94-02f1ac65ee95.png)

### Deliverable 2 - December Temperatures
The goal of this deliverable was to complete the same query but to adjust it to pull all of the data for the month of December. We were able to use the same code throughout the deliverable while making some minor tweaks to capture December data instead of June.

![image](https://user-images.githubusercontent.com/110848660/201249176-2841088e-826a-450e-bf31-5d434af03d45.png)

![image](https://user-images.githubusercontent.com/110848660/201249209-2efbec4c-dc42-40ed-8f88-eb3ecdcb4e55.png)

![image](https://user-images.githubusercontent.com/110848660/201249282-5ad8f258-6d00-4093-8262-c19c426ef981.png)

![image](https://user-images.githubusercontent.com/110848660/201249323-d2f4bd7c-d4aa-400c-b425-75f43ffe834d.png)

- The first takeaway that we have from comparing the temprature between June and December is that there isn't a big variance in the "mean" temperature between the two months. We can see that the mean June temperature is 74.94 and the mean temperature for December is 71 which is only a difference of 3 degrees

- We wanted to look at the "min" temperature next as part of our second takeaway. We assumed it would be valuable to look at the "min" temperature since one of the months in our datasets is traditionally one of the coldest months in most areas of the country. We we looked at the two months "min" temperatures, we saw more of a variance than we did when we compared the average temperatures. The min temperature in June was 64 degrees while the min temperature in December was 56 degrees for a difference of 8 degrees.

- The last takeaway was around checking to see if we had a sufficient amount of temperature observations between our two months that we observed. We wanted to make sure that it was consistent throughout the year to make sure that our data was not skewed. We're able to see that we had a "count" of 1700 temperature observations in June and 1517 temperature observations in December. This is a difference of about 200 total observations between the two months. Despite the temperature count discrepeancy, we feel like there is sufficient data to make an honest comparison between the two months as it relates to temperature.
- 
### Summary



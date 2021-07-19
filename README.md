# PyBer_Analysis

(File also available as word document with embeded images and charts at: https://github.com/Roland791/PyBer_Analysis/blob/main/Pyber_Analysis_Challenge.docx)


##Overview

	The purpose of our analysis is to parse ride sharing data by city type(Rural,Urban & Suburban)and identify key factors that can inform company decisions regarding fare structuring and driver distribution. 

	Data will be grouped by city type with totals of drivers, fares, and rides, the average cost per ride and average fare per driver. Then, we'll sample data for a range of 4 months (January - April) and review to see what kind of trends can be derived for the total weekly fares for each city type during that period.

##Results

	 										
Figure 1 - Pyber Fare Summary: https://github.com/Roland791/PyBer_Analysis/blob/main/analysis/Figure_1_Pyber_Fare_Summary.png


	Upon analyzing the data groupings by city type in Figure 1, a few key items stand out:

The more densely populated areas have a higher adoption rate of the ride service, both in ridership and drivers
Based on average fare data, it appears that riders in less populous areas are generally traveling further, resulting in higher average fares per ride, with the reverse being true for urban areas, where the average cost of rides is much lower, indicating shorter average ride times 
There is an oversaturation of drivers in urban areas, with a 3:2 driver to rides ratio, indicating that, on average, a 3rd of drivers aren't active, this deviation brings the average fare per driver down significantly lower as a result.  


				
Figure 2 - Pyber Date Sampling: https://github.com/Roland791/PyBer_Analysis/blob/main/analysis/Figure_2_PyBer_Date_Sampling.png

		In addition, by graphing the data between January and April, several trends become apparent:

The trend for more populous areas being more profitable that was noted in the summary data is even more clearly demonstrated here by the fact that there is no point where Total fares between the three areas come even close to being equal. 
Urban areas tend to be much more volatile from week to week, with sharper ups and downs.

##Summary 

	Upon review of this information, we are making the following recommendations to improve the disparities identified.

	1) Investigate the disparity between drivers to rides in urban areas to determine if the issue is a result of too many inactive drivers in the system or if there are simply too many drivers at certain periods 
	2) Introduce surge pricing in urban areas during periods with low driver availability and high ridership to increase the rates per driver and incentivize inactive drivers to be available during these periods.
	3) Look at marketing opportunities to increase visibility in rural and suburban areas including partnerships with local businesses (bars, grocery stores, etc) to provide more targeted service. 




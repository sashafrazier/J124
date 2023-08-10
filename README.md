# J124 Final: Data Analysis and Visualization of Ojai Drought Causing People to Move out of Town
# By Sasha Frazier
## Story Pitch:
While sunny Ojai, CA is most widely known as a tourist destination, is also a huge agricultural town with ranches, farms, orchards, and residential gardens. These grounds, and people’s abilities to tend to their own, are the driving forces drawing people into Ojai. Many locals live off the lands, raising livestock and crops, and depend on the weather and natural resources to maintain their livelihoods. According to Ventura River Ecosystem, 67% of Ojai’s annual water use is allocated for agriculture. Rain is a big factor for the ranchers in Ojai, and in recent years, its absence has been driving them out of town.

Ojai has been experiencing increased drought conditions the past couple years. In 2021, Ojai received its lowest amount of rainfall on record according to VC Watershed and the 5 driest years recorded have all been within the last 10 years according to NIDIS. As a result of this, water rates have been increasing, making it more difficult for ranchers to afford their utility bills. These increased utility bills, leading to the inability to grow crops and feed livestock, has forced ranchers to move out of Ojai and take their farming elsewhere. According to World Population Review, recent population projections reflect this phenomenon as population growth rates are set to decrease, starting with 2021.
## Contacts:
1. Shane Watkins - Watkins Cattle Company<br>
Phone: (805)896-7995<br>
Email: gotbeef@watkinscattleco.com<br>
Shane Watkins is a local rancher and butcher who moved out of Ojai due to increased water rates and dying crops, making it impossible to afford to feed cattle. He gives a first-hand account of the drought crisis making Ojai inhospitable for ranchers, causing them to relocate. 
2. Rachelle Giuliani - Tonya Peralta Real Estate<br>
Phone: (805)746-5188<br>
Email: rachelle@PeraltaTeam.com<br>
Rachelle Guiliani is a local real estate agent who can testify on her client’s reasons for selling and moving out of the valley. She can lay the groundwork for the draw of Ojai’s land and gardens and explain that if these are inaccessible or unaffordable, people are having to leave and move elsewhere.
3. Scott Holder - VC Watershed, Watershed Resources and Technology Division<br>
Phone: (805)766-9383<br>
Email: pwa.hydrodata@ventura.org<br>
Scott Holder is a hydrologist in the Watershed Resources and Technology Division who can explain the irregularity of the low rainfall counts. He can provide a professional testimony on the effects these records have on plant life and crops in Ojai Valley. This is his area of expertise. 
## Additional Sources:
1. *Public Works “Old-Timer” Rainfall Chart*
[Public Works “Old-Timer” Rainfall Chart](https://vcwatershed.net/hydrodata/chart/?site=030)
		a. I would use this source to highlight that 2021 had the lowest rainfall in Ojai Record. This is significant because in 2021, the population growth rate decreased and is projected to maintain a negative rate from that point on.
2. *Ojai Water Budget Breakdown*
![Ojai Water Budget Breakdown](https://1.bp.blogspot.com/_gPTpZ6ajSsk/S9YrjU7zgGI/AAAAAAAAB9I/3VmRrJXIkmw/s1600/Picture+33.png)
	   a. I would use this source as context at the beginning of my story to show how the majority of water use is agriculture, helping explain the importance of water to local ranchers and farmers.  
## Data Visualization:
1. ![Ojai Population Data Vis](https://github.com/sashafrazier/J124/assets/140098794/6e00e6e9-0e0a-4739-a14c-4c38f5e9ab5c)
	   a. *Ojai Population*<br>
[Ojai Population](https://datawrapper.dwcdn.net/VzHQJ/1/)
2. ![Drought Record Data Vis](https://github.com/sashafrazier/J124/assets/140098794/ec1ad911-33bc-4edf-a767-90b6b351e87d)
 	     a. *Drought Record*<br>
[Drought Record](https://datawrapper.dwcdn.net/MFw5N/2/)
## Data Analysis:
**1. What is the mean drought level for each year?**
		1. I made a new sheet for the mean drought levels each year and typed in the AVERAGE function to pull data from the drought level sheet and calculate the averages for each drought level each year.<br>
**2. What 5 years are the driest?**
		1. 2016, 2015, 2014, 2021, 2017<br>
		2. Based on yearly averages for category D4 drought since D4 is the most severe category for drought. I put D4 yearly averages in alphabetical order from Z-A.<br>
**3. What is the mean growth rate of the driest years?**
		1. 0.13%<br>
		2. I started by writing a VLOOKUP function to find projected population growth for the top 5 driest years. 
I used A2 as my search key because that was the first input in the range. 
My range is ‘Ojai Population’ A2 : D29 because I needed the years and growth rates from the Ojai Population sheet. 
4 is the index because column D is where the growth rate is listed and D is the 4th letter.
Finally, it is false because I need the exact match of years, not approximations. <br>
I then selected the growth rates for the top 5 driest seasons and changed the green icon at the bottom from ‘Sum’ to ‘Avg’ and got 0.13%<br>
**4. What is the growth rate of the year with the least amount of precipitation?**
		1. -0.32%<br>
		2. I found the year with the least amount of precipitation (2021) and found at the population growth rate for 2021: -0.32%<br>
**5. What is the average population growth rate from the day with the lowest precipitation, onward?**
		1. -0.32%<br>
		2. I went to the Ojai Population sheet and selected years 2021-2023 because the precipitation data only goes through 2023, and I selected the little ‘Avg’ icon in the bottom left of the screen and it said: -0.32%<br>
**6. How do these compare to the overall average growth rate?**
		1. These are both significantly smaller than the overall average<br>
		2. To find the overall average growth rate, for years that have precipitation data (up until 2023), I selected the population column data for 2000-2023 in the Ojai Population sheet and pressed the ‘Avg’ icon. It said: 0.90%<br>
**7.  What are the population speculations for the highest utility costs?**
		1. I cleaned the Rate data by putting it in a new sheet with the year as a row and the meter sizes as columns. This way I could compare the rate per year to the population per year. I added Population data to this table<br>
		b. I then made a pivot table so I could compare just the 12-inch water meter rates per year to the population. I selected the 12-inch water meter because it is typically used for large gardens and ranches. <br>
**8.  What is the drought history of the last 5 years?**
		1. I sorted the Mean Drought table from Z-A.


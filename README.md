# Leveraging Social Media to Map Disasters

Examining: 

Camp Fire - Paradise, CA | November 8th - 25th 2018

Carr Fire - Redding, CA | July 23rd - August 30th 2018

Hurricane Harvey, Houston Metro Area | August 23rd - August 31st 2017

#### [Please Read the Summary of Our Analysis Here](https://drive.google.com/file/d/1pfrALyBYQm49f1ucScO3CiN1P7pYer0V/view?usp=sharing)
#### [Please Take a moment to look through Our Presentation Here](https://github.com/pwalesdi/Mapping_Disasters/blob/master/presentation.pdf)


When responding to disasters such as wildfires, hurricanes, floods and earthquakes,  emergency workers have the critical task of being able to identify where survivors are located in order to quickly and accurately send assistance. 

Given the rapid growth in wireless technology and the increasing likelihood that people all across the globe have a cell phone we want to attempt to tap into this technology in such a way that we can use social media posts asking for help and assistance to track survivors.

Social media can provide valuable information about the specifics of a disaster such as downed power lines, flooding streets, spread and location of wildfire, density of smoke etc. Additionally it can help identify isolated communities at risk, locations of survivors and areas where assistance teams should be sent for search and rescue, levels of damage, help map depths of flooding, identify where additional imagery/information needs to be collected and plan when and where resources should be allocated.

Here we attempted to specifically engage with the Twitter API in order to create tools that would allow us to geolocate people in need and/or areas in need of assistance and/or areas that should be avoided. The desired tools would have the ability to help locate problems regardless of the type of disaster.

In summary, this project illuminated to us that there are opportunities to use real-time social media data to access important information during disasters or emergency situations. The key for any major company hoping to do this will be to ensure the quality of the data they are acquiring. Despite many of the challenges when attempting to leverage this information, we found the project to be useful and rewarding and it presents opportunities for further developments in the future.

One final thought for companies like FEMA who might feel like this type of tool or one similar has great potential to be useful would be to partner with Twitter, Instagram and other companies to include an emergency feature on the app. Perhaps something that only can be activated by state and local emergency staff that sends out a warning to people's phones asking if there are in danger. They could have the option of tapping a button to instantly send their geo-location to EMS with a message about their situation. In order for these platforms to be leveraged properly it seems necessary to have coordination and cooperation between the platforms themselves and the respondents. 

# Repo Contents

[Data Gathering Notebook](https://github.com/pwalesdi/Mapping_Disasters/blob/master/1.twitter_API.ipynb)

[Corpus Building Notebook](https://github.com/pwalesdi/Mapping_Disasters/blob/master/2.build_disaster_corpus.ipynb)

[EDA Notebook](https://github.com/pwalesdi/Mapping_Disasters/blob/master/3.EDA_clustering.ipynb)

[Data Modeling Notebook](https://github.com/pwalesdi/Mapping_Disasters/blob/master/4.modeling.ipynb)

[Geo Mapping Notebook](https://github.com/pwalesdi/Mapping_Disasters/blob/master/5.google_maps_plotting.ipynb)

[Data Visualization Notebook](https://github.com/pwalesdi/Mapping_Disasters/blob/master/6.visualization.ipynb)

# Visuals

### Mapping Geo-Location of Disaster Related Tweets - Chico, CA
![alt text](https://github.com/pwalesdi/Mapping_Disasters/blob/master/images/satellite-Chico.png "Chico, CA")
<space>
	
### Mapping Geo-Location of Disaster Related Tweets - Redding & Chico, CA
![alt text](https://github.com/pwalesdi/Mapping_Disasters/blob/master/images/satellite-Overview.png "Carr Fire & Camp Fire")
<space>
<space>

### Camp Fire Location and Spread
<p align="center">
  <img width="750" height="550" src="https://github.com/pwalesdi/Mapping_Disasters/blob/master/images/camp_fire.png">
</p>




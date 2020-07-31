# GIS Portfolio
Welcome to my GIS portfolio. Below you can browse examples of my work compiled over the past two years. 

This portfolio can also be viewed by visiting [https://jaxgoodlabs.github.io/GIS_portfolio/](https://jaxgoodlabs.github.io/GIS_portfolio/). 

## About me 
<img align="left" src="https://user-images.githubusercontent.com/32546509/77238966-de37cd00-6bab-11ea-9b9b-e49783f8300a.jpg">
My name is Patrick Campbell and I’m a recent graduate of Carnegie Mellon University's Public Policy and Management master's program (MSPPM). Prior to enrolling at Carnegie Mellon, I worked for over eight years in a wide variety of positions in the areas of environmental science and conservation. My early career was devoted primarily to addressing water quality issues in South Florida, where I worked as an environmental consultant in support of several projects managed by the South Florida Water Management District. During this time, I gained a lot of valuable experience both in water quality and other field sampling techniques as well as in the broader policy environment surrounding the local management of natural resources.<br />
<br />
I first became interested in the social applications of data science through my engagement with the Effective Altruism and Data Science for Social Good communities, which seek to apply reason and evidence to determine the most effective ways to benefit others. My interactions with these communities opened my eyes to the depth of need that exists within the public sector both for more high-quality data as well as for the knowledge and skills to put that data to effective use.<br />
<br />
This realization is what ultimately led me to Carnegie Mellon, and to Heinz College in particular. As the country’s top-rated program in analytics education with a mission of training students to “turn raw data into solutions for society’s most pressing problems,” the MSPPM program at Carnegie Mellon offered the perfect opportunity to develop the technical competencies I was seeking as well as an ideal environment to practice those skills in a real-world setting—namely, the City of Pittsburgh and its diverse network of organizational partners.<br />
<br />
My most recent projects have focused on public interest technologies that help to increase the range and accessibility of social services worldwide, especially as a means of increasing society's resilience to global threats like climate change.<br />
<br />
View my resume [here](https://jaxgoodlabs.github.io/patrick-campbell-portfolio/Patrick%20Campbell%20Resume.pdf).

#### Jump to Section
- [Google Map Styles](#google-maps-styles) 
- [ArcGIS Map Style](#arcgis-map-style-plant-growing-in-the-desert) 
- [Mecklenburg Hazard Evacuation Exercise](#mecklenburg-hazard-evacuation-exercise)
- [Mapping Damage from Hurricane Katrina](#mapping-damage-from-hurricane-katrina) 
- [Visualizing 412 Food Rescue Data with Kepler](#visualizing-412-food-rescue-data-with-kepler) 
- [Investigating Patterns in my Google Location Data](#investigating-patterns-in-my-google-location-data) 
- [Final Project: Hazus Flood Modeling for Miami, FL](#final-project-hazus-flood-modeling-for-miami-fl)
- [Sustainable Campus Project](#sustainable-campus-project) 
- [Sustainable City Project](#sustainable-city-project) 
- [Norwalk Transportation Project](#norwalk-transportation-project)
- [Pittsburgh EV Site Analysis Project](#pittsburgh-electric-vehicle-site-analysis) 
- [Optimizing Coverage of Hunting Areas for Maximum Removal of Burmese Pythons in South Florida](#optimizing-coverage-of-hunting-areas-for-maximum-removal-of-burmese-pythons-in-south-florida) 
- [Bumblebee Conservation in the Midwest US](#bumblebee-conservation-in-the-midwest-us)
- [Resilience Oriented Planning Map](#resilience-oriented-planning-map)

## Google Maps Styles

### People's Square
In this exercise, I used the [Google Maps Platform Styling Wizard](https://mapstyle.withgoogle.com/) to create my own Google Maps basemap, which I've named People's Square. To create the style, I first searched Google for an image (filtered by "marked for resuse" license) whose color scheme matched that of the map style I wanted to create. 

I ultimately settled on the following image of People's Square in Shanghai (photo by [f11photo](https://stock.adobe.com/contributor/201898682/f11photo?load_type=author&prev_url=detail) via [Adobe Stock](https://stock.adobe.com/), standard license):

<p align="center">
<img width="600" height="400" src="https://user-images.githubusercontent.com/32546509/77230702-6302f680-6b6c-11ea-93ce-bf99898ecf31.jpg">
</p>

I then used [Canva's color palette generator](https://www.canva.com/colors/color-palette-generator/) to create a custom color palette based on the image I had chosen. 

<p align="center">
<img width="500" height="155" src="https://user-images.githubusercontent.com/32546509/77231010-92b2fe00-6b6e-11ea-9bac-d2ba32425c89.jpg">
</p>

Back in the Google Maps Styling Wizard, I selected the "Dark" theme to serve as my base template and then proceeded to change the colors of various features using the hex codes from my custom color palette. A screenshot of the final product is displayed below. To access an interactive version of the map style, just click [here](https://jaxgoodlabs.github.io/GIS_portfolio/peoples-square.html).

<p align="center">
<img width="800" height="450" src="https://user-images.githubusercontent.com/32546509/77235533-cc92fd00-6b8c-11ea-89fa-86e10101dde3.JPG">
</p>

### Night Glacier 2
The Night Glacier 2 style was inspired by this image of ice climbers exploring a glacier at night, which I again used Canva to convert into a custom color palette.

<p align="center">
<img width="810" height="275" src="https://user-images.githubusercontent.com/32546509/77257394-5654d000-6c4a-11ea-92b0-7d8fbb566671.JPG">
</p>

The resulting map style is presented below.

<p align="center">
<img width="800" height="535" src="https://user-images.githubusercontent.com/32546509/77254553-171d8380-6c38-11ea-8b6e-5a2ab281bcba.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/GIS_portfolio/night-glacier-2.html) to access the interactive version.

### Remote Sensing
The Remote Sensing map style attempts to mimic the typical color scheme of an image generated using remote sensing technology. The image that served as my inspiration for this style is presented below along with the color palette generated from it.

<p align="center">
<img width="810" height="275" src="https://user-images.githubusercontent.com/32546509/77257412-7dab9d00-6c4a-11ea-9836-2edfaa506d90.JPG">
</p>

The resulting map style is presented below.

<p align="center">
<img width="800" height="535" src="https://user-images.githubusercontent.com/32546509/77254556-1a187400-6c38-11ea-812d-5e909c2047fd.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/GIS_portfolio/remote-sensing.html) to access the interactive version.

[Return to top](#jump-to-section)

## ArcGIS Map Style: Plant Growing in the Desert
<img align="left" width="17%" height="17%" src="https://user-images.githubusercontent.com/32546509/77484326-9d84c180-6e00-11ea-8bb3-d4757ef2b7d8.JPG">
For this exercise, I wanted to make another attempt at executing my concept from last week - which, again, was to use a contrasting color scheme to highlight the specific elements of a municipality's physical infrastructure (buildings, highways, etc.) used by commons, cooperatives, and other cooperative enterprises. Similar to the previous exercise, I searched for images following a "life and death" theme, where life was represented by living greenery (trees, plants, etc.) and death was represented by burned or desiccated soil or dull, gray concrete. I ended up using  this image of a plant sprouting in the desert (left).<br />
<br />
A lesson I took away from last week's assignment was that the role of the basemap in a project like I've described is pretty minimal. Most of the contrast I want to draw is between elements of the physical infrastructure, most of which (particularly buildings) is absent from the basemap. For that reason, I decided it was best to use a subtle, low-contrast color scheme for the basemap and give priority to the duller hues, i.e., the browns, taupes, and beiges. I used the greens for their traditional purpose of demarcating parks and natural areas, saving the brighter tones for those map layers I would add later.<br />
<br />
To execute my vision, I selected the Modern Antique template. I naturally think of the development of the commons-based infrastructure as a sort of frontiersman/early-explorer sort of enterprise, so I wanted to use a basemap that had an older, antique feel to it. This template also looked like it would work well for the subtle, low-contrast color scheme I had in mind.

A screenshot of my final map style is copied below. (Click [here](https://arcg.is/1qPCSb) to view the fully interactive version.)

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/77484477-0409df80-6e01-11ea-865e-6f1b805e9d65.JPG">
</p>

The big test for how effective my basemap is has to do with how well it supports the message I want to communicate with the layers I add later, specifically, buildings, roads, etc. This is where I'd want to focus my attention when QA-ing the final product. At first glance, I'm satisfied with how everything is rendering. I like the general subdued tone of the map and the old-timey feel it has. 

One change I'd like to make to improve my final map is to dull the color used for certain parks/natural areas. For whatever reason, the template I used automatically dulled the green for most of these areas but left certain polygons with the full color saturation (see, e.g., the top right corner of Schenley Park in the main screenshot above). Because I don't want my basemap to compete with added layers (specifically the physical infrastructure layers that are the map's primary subject), I'd prefer all these areas to be the same shade of green. 

One unanswered question, which may affect my comments above, has to do with which additional map layers end up being relevant to the final map, and how my design choices for those features interact with those of my basemap. For example,  I mentioned that I want to display large portions of the physical infrastructure layers as background/contextual layers also, using a similar color scheme to those I've used for the basemap. (This is necessary, e.g., to highlight those specific portions of that infrastructure that are utilized by cooperative enterprises.) So one thing I'd want to pay special attention to is how well that effect works when it's being duplicated at both the basemap and feature layers, or if, alternatively, I need to make some adjustments to the basemap to preserve the impact at the feature level. 

[Return to top](#jump-to-section)

## Mecklenburg Hazard Evacuation Exercise

**I. Map with Incident and Evacuation Plans**

*Mecklenburg, NC Hazardous Incident Report*
<br />
> At 6:32 this evening, a tanker truck carrying chlorine gas was heading westbound on Interstate 85 in Mecklenburg County when the driver lost control of the vehicle. The tanker was damaged in the process and chlorine gas is leaking slowly from the damaged tank into the surrounding area. The incident occurred between the two northbound and southbound lanes of Interstate 77 creating unsafe conditions for anyone located within a two-mile radius of the incident. 
> 
> Emergency responders are on the scene and have issued an immediate evacuation notice for all households located within the affected area (see the evacuation area on the map below). 
> 
> Initial reports estimate 15,626 households located within the affected area, representing a population of approximately 47,697 individuals. Temporary shelters have been set up in the half-mile area outside the perimeter of the evacuation zone (light red ring) and are marked on the map with mustard-yellow icons. All evacuees are instructed to seek shelter immediately at the nearest shelter location until the situation has been brought under control. While current weather conditions look favorable to preventing the expansion of the hazard area, the situation is being closely monitored for any changes. 
For real time updates on the status of the situation, stay tuned to your local public radio station. A special hotline has also been set up to answer questions and provide any additional guidance that may be required as the situation is being resolved. To speak to an attendant, dial 555-5555. 

<p align="center">
<img width="80%" height="80%" src="https://user-images.githubusercontent.com/32546509/79400523-70858380-7f54-11ea-9269-3f55cd1bd80b.JPG">
</p>


**II.	Map of Redirected Traffic Patterns and Drive Times to Nearest Hospitals**
<br />
Below is a proposed text message that the North Carolina DMV can send out that instructs motorists how to deal with the incident. Below that, I have included a map of evacuation routes and the service areas of the nearest fire stations. 

> An immediate evacuation notice has been issued for all motorists located within two miles of the I-77/I-85 interchange in Mecklenburg County due to the release of toxic chlorine gas in the area. Emergency responders are working to contain the incident and will provide regular updates through your local public radio station. Please call 555-5555 to be notified of the location of the nearest shelter and evacuation routes. If you think you may have been exposed to the hazard, an attendant can provide the location of the nearest hospital and offer guidance on seeking evaluation and treatment.

<p align="center">
<img width="80%" height="80%" src="https://user-images.githubusercontent.com/32546509/79400529-73807400-7f54-11ea-9f26-184d0c30e1c0.JPG">
</p>

[Return to top](#jump-to-section)

## Mapping Damage from Hurricane Katrina

**I.	Map of Mississippi elevation/bathymetry**
<br />
The map below shows the elevation/bathymetry of coastal Mississippi counties with places, types of water, barrier islands, and rivers. A second map is also provided showing a time series of the path of Hurricane Katrina in relation to these features. The time slider has been stopped at the moment the hurricane’s path had just crossed the Mississippi coastline, around 4 pm on Aug. 28, 2005 (see light yellow line at west of map). As you can, the hurricane landed at the southwest corner of Hancock county with a pressure of less than 923 millibars.

<p align="center">
<img width="80%" height="80%" src="https://user-images.githubusercontent.com/32546509/79077075-8da82100-7ccc-11ea-9a09-8f89cded7056.JPG">
</p>
<p align="center">
<img width="80%" height="80%" src="https://user-images.githubusercontent.com/32546509/79076843-0f974a80-7ccb-11ea-89f4-e0de69b6c6dc.png">
</p>

**II.	Map of flooded Mississippi coast after Hurricane Katrina**
<br />
The map below shows the extent of flooding in the wake of Hurricane Katrina across three coastal counties in Mississippi. Flooding is shown broken down by the type of land-cover it affected, with the unaffected areas displayed with no color.
<br />
<p align="center">
<img width="80%" height="80%" src="https://user-images.githubusercontent.com/32546509/79076926-803e6700-7ccb-11ea-98f6-d3aaf2064c38.jpg">
</p>

A total of 1,293,503 acres of land was flooded in the wake of Hurricane Katrina between the three coastal counties. A breakdown of these flooded areas by type of land cover is provided in the table below.<br />

*Table 1. Breakdown of flooded areas by type of land cover*
<p align="left">
<img width="47%" height="47%" src="https://user-images.githubusercontent.com/32546509/79076909-5dac4e00-7ccb-11ea-856c-6f81bf7dd810.JPG">
</p>

**III.	Map of infrastructure at risk from storm surge**
<br />
The map below shows the infrastructure and health facilities at risk from the Hurricane Katrina storm surge, which rose to 15 feet above normal sea level. Vast areas were affected with the largest impacts being concentrated around existing wetlands and river systems. The barrier islands to the south were completely inundated by the storm surge, although these areas fortunately appear to have been absent of major infrastructure or facilities.

<p align="center">
<img width="80%" height="80%" src="https://user-images.githubusercontent.com/32546509/79076928-85031b00-7ccb-11ea-9089-6fe22ab7056a.JPG">
</p>

[Return to top](#jump-to-section)

## Visualizing 412 Food Rescue Data with Kepler
Below is a screenshot of the 412 Food Rescue data I visualized in Kepler. Like many others, I felt the 3-d view would be most effective for displaying the arcs connecting donor and recipient. I chose a purple-yellow color scheme for maximum contrast and visibility on the dark-themed basemap. To reinforce the altruistic nature of the work, I chose the brightest color (yellow) to represent the recipients, implicitly making the map about them rather than the donors, who are visualized in purple. I thought the gradation effect was nice for providing the context of directionality. 

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/79072640-1ebccf00-7cb0-11ea-8d3c-50a9fee402d5.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/GIS_portfolio/kepler412data.json) to access the json file for this map.

[Return to top](#jump-to-section)

## Investigating Patterns in my Google Location Data

While exploring my location data in ArcGIS data - which curiously included data just from 2015, 2019 and 2020 - the first thing that struck me was how spotty the coverage was. I had thoroughly expected to see a complete saturation of points throughout my travel range, but for many trips, found only single points representing a final destination. These were long, drawn out car trips, some of them covering multiple days of travel, and yet Google seems to have only collected a single data point from the whole trip.

The two notable exceptions to this rule are my more regular commutes, e.g., between Miami and West Palm Beach when I was living in West Palm Beach and hunting pythons in Miami on the weekends, and longer trips that I took more than once, e.g., my trip from my permanent residence in Jacksonville, FL up to school in Pittsburgh. A lot of my traveling, particularly in Florida. passes through cell-coverage dead zones, so I assume that of the spottiness in data collection owes to that fact. That might also explain the single erroneous point near Fort Walton Beach in the Florida panhandle. While I passed in that general vicinity on one or two occasions during this period, that particular point is pretty far off from any of the routes I would've taken. 

My dead zone theory is also consistent with the absence of points west of the Tamiami Trail/Krome Ave. intersection in Sweetwater, FL. This area, which passes through Everglades and Big Cypress National Parks, is where I did all my hunting for the python program, but has notoriously poor cell coverage. 

The other interesting thing I noticed about my location data is how sprawling my data is around the areas that I live. The first thing I do when I settle into a new place is starting exploring the nearest natural areas with hiking opportunities. Often, the closest locations are maybe a half-hour drive from my apartment in the city, but after a year or two, I'm up to driving two or three hours away to find new parks to explore. This pattern is most noticeable around Pittsburgh (my current residence) and Jacksonville, FL (my permanent residence). 

<p align="left">
<img width="38.1%" height="38.1%" src="https://user-images.githubusercontent.com/32546509/79076040-e8d61580-7cc4-11ea-8a5f-941fb5e093a2.JPG"> <img width="60.3%" height="60.3%" src="https://user-images.githubusercontent.com/32546509/79076036-e2e03480-7cc4-11ea-9b77-d68aa0b6e1d1.JPG">
</p>

I was surprised at how little order I could discern at a high scale. If I had no special knowledge, I doubt I would be able to discern from the concentration of points alone anything beyond where I lived and where I've been. My work and school locations were not at all obvious even at the narrowest zoom ranges (although perhaps referencing what's located at each of these points in conjunction with the date and time stamps would clue me in).

The location of my home was easier to discern, but still required some fine-combing through the data. Of course, there's a lot more information embedded in this data than is apparent in the distribution of the points alone, and I imagine that it wouldn't be difficult to answer these sorts of questions once my data was aggregated with that of other users, since these patterns probably don't differ too drastically between members of the same general category (e.g., university students). 

To see how easily I could extract this sort of information from these data, I used the hexagon binning option in the aggregate points tool to aggregate the number of points located in each tenth mile squared cell. Sure enough, this method resolved all the ambiguity of the previous display. Using a contrasting blue-yellow color scheme made my home and frequent locations pretty unmistakable, as the image below demonstrates.

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/79072713-7a875800-7cb0-11ea-9c13-60147f423540.JPG">
</p>

[Return to top](#jump-to-section)

## Final Project: Hazus Flood Modeling for Miami, FL

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/80930537-2a1c8b00-8d82-11ea-9803-c63422e9555e.JPG">
</p>

*Overview*

This project aims to model the flood risks for a single census tract in Miami, FL. This census tract  is currently being analyzed as part of a pilot study by researchers at Miami-Dade College. The methodology developed over the course of this study will eventually be adapted for application to the entire city in order to better anticipate and respond to the threats posed by climate change to public buildings and the communities that they service.

(Updates to the proposed workflow and deliverables are provided at the end of this summary.)

**1.	Problem Statement**

The problem this project aims to solve is how to best leverage FEMA’s Hazus tool for risk assessment, policymaking, and coordinated response in Miami, Florida, especially in the face of rapidly changing climate conditions and rising seas.

A secondary challenge related to the problem defined above is how to design / optimize the workflow for city-wide deployment of the developed methodology. This requires, among other things:
-	Determining the optimal resolution of drone footage to balance (a) speed and efficiency of data collection and processing with (b) accuracy and reliability of assessments and recommendations
-	Integrating multiple software platforms (CDMS, ArcGIS Pro + Hazus, etc.) and data types (high-resolution aerial imagery, structural data, GIS map layers, etc.).

**2.	End Users**

The end users of the products generated by this project are researchers at Miami-Dade College and the City of Miami.

**3.	Work Plan and Methodology**

This project aims to model the flood risks for a single census tract in Miami, FL. This census tract  is currently being analyzed as part of a pilot study by researchers at Miami-Dade College for eventual expansion to the entire City of Miami. 

The two central elements of the project are (1) the flood model (Hazus Flood Level 1) for the target study area and (2) a documented workflow detailing how the data collection, processing, and cross-platform integration will be accomplished.

Key steps in this workflow include:
-	Collection of high-resolution aerial imagery of target study area using drones
-	Processing and analysis of drone footage to model key features of site, including buildings and infrastructure for more accurate and precise damage projections
-	Integration of drone data into Hazus state data package using Hazus Comprehensive Data Management System (CDMS) and other software systems as necessary
-	Codification of site analysis within Hazus tool
-	Export of results and findings for response and policymaking

My methodology for this project varies according to the different component activities it comprises. For a thorough description of methods employed organized by activity, refer to the accompanying [Process Log](). 

**4.	Group Members and Roles**

Patrick Campbell - Project Manager, GIS Analyst, Data Systems Manager

**5.	Data Sources**

The full set of source data used for this project is detailed in the accompanying [Data Documentation]() file. 

**6.	Final Deliverables**

The final deliverables for this project include:
-	A one-page summary describing what my final project is, who worked on it, what the problem I’m attempting to solve is, and who benefits from it. 
- A [Process Log]() documenting the steps involved in my analysis, organized by date. 
-	Final assets: 
  - Final project package including 
    - Hazus Flood Modeling for Miami, FL geodatabase file
    - Screenshots
    - Source documents
    - Esri Surface Imperviousness Exercise (including all associated outputs)
    - MiamiStudyArea mxd file for Hazard Analysis
  -	[Example tutorial]() for creating a flood model and impact assessment from a Digital Elevation Model (DEM) file

**7.	Project Updates**

<p align="center">
<img width="85%" height="85%" src="https://user-images.githubusercontent.com/32546509/80931010-4d950500-8d85-11ea-9002-b4b24cb4d7a9.png">
</p>

Due to difficulties running the Hazus software on my personal laptop, I decided instead to focus on analyses I could execute using the standard ArcGIS Pro suite of tools. The central focus of this effort involved attempting to reproduce several official flood models issued by Miami-Dade County and NOAA. For example, in the figure below, I've reproduced [NOAA's model for 9 feet of sea level rise](https://coast.noaa.gov/slr/#/layer/slr/9/-8926859.280505564/2977300.725765961/15/satellite/none/0.8/2050/interHigh/midAccretion) by converting a Digital Elevation Model (DEM) file to a polygon layer representing flooded lands. Details of this and other analyses are thoroughly documented in the accompanying [Process Log]().

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/80931424-c09f7b00-8d87-11ea-8a65-91b0f92a0d36.JPG">
</p>

A secondary goal of this project was to troubleshoot various tutorials and flood modeling exercises for possible incorporation into the new Geographic Information Systems for Environmental Awareness and Community Engagement (GISEC) curriculum at Miami-Dade College. “The goal of GISEC is to create a pathway for students in GIS technology and to enhance technological applications of public interest with an emphasis on environmental hazards awareness and community engagement in Miami-Dade County, a minority-majority urban area significantly impacted by, and at ongoing risk for, natural disasters.”[1](https://www.mdc.edu/entec/grants/gisec.aspx)  To this end, I spent a large portion of my time on this project exploring various applications of the ArcGIS Pro Image Classification tools, completing several guided tutorials in the process. The products of these exercises have been included in the final project package. Relevant notes and insights from these exercises are provided in the Process Log, while the Example Tutorial file provides a model of how these analyses might be converted into guided tutorials for use in the classroom. 

[Return to top](#jump-to-section)

## Sustainable Campus Project

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/80049872-1e0f0e80-84e2-11ea-99b5-3ff09698fc8c.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/GIS_portfolio/sustainable-campus) to view the final report for this project. The interactive final product can be accessed [here](https://jaxgoodlabs.github.io/Sustainable_Campus/).

[Return to top](#jump-to-section)

## Sustainable City Project

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83973007-78590880-a8b1-11ea-8c1f-6ab0df87929f.png">
</p>

Click [here](https://jaxgoodlabs.github.io/SustainableCity/) to view the interactive final product.

[Return to top](#jump-to-section)

## Norwalk Transportation Project

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83985569-c00a7f00-a907-11ea-801d-83699e1ea831.png">
</p>

Click [here](https://github.com/jaxgoodlabs/Norwalk_Transportation/) to view this project on GitHub.

[Return to top](#jump-to-section)

## Pittsburgh Electric Vehicle Site Analysis

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/80050002-79410100-84e2-11ea-9ced-5082f60267e9.JPG">
</p>

Click [here](https://github.com/jaxgoodlabs/Pitt_EV_Bike_Ped_Site_Analysis) to view this project on GitHub.

[Return to top](#jump-to-section)

## Optimizing Coverage of Hunting Areas for Maximum Removal of Burmese Pythons in South Florida

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/80058259-cb8c1d00-84f6-11ea-919a-03ca89bd5605.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/sfwmd-python-program) to view the final report for this project.

[Return to top](#jump-to-section)

## Bumblebee Conservation in the Midwest US

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83971918-9ae82300-a8ab-11ea-82e8-bf18962a0587.JPG">
</p>

[View this map on ArcGIS Online](https://arcg.is/05XH5S0) or click [here](https://carnegiemellon.maps.arcgis.com/apps/MapSeries/index.html?appid=9dc0bb2905164cf4a9c71c6e6a972c63) to view the project Story Map. Access the final report [here](jaxgoodlabs.github.io/bumbleebee-conservation/).

[Return to top](#jump-to-section)

## Resilience Oriented Planning Map

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/83976614-14dad500-a8c9-11ea-829d-abff9be35343.png">
</p>

Click [here](https://jaxgoodlabs.github.io/pittsburgh-hazards-map) to view this project.

[Return to top](#jump-to-section)

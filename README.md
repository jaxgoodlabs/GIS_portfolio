# GIS_portfolio
Welcome to my portfolio for 90753: Advanced GIS. This portfolio can also be viewed by visiting [https://jaxgoodlabs.github.io/GIS_portfolio/](https://jaxgoodlabs.github.io/GIS_portfolio/).

## About me 
<img align="left" src="https://user-images.githubusercontent.com/32546509/77238966-de37cd00-6bab-11ea-9b9b-e49783f8300a.jpg">
My name is Patrick Campbell and I’m a 2nd year student in the Public Policy and Management Master's Program at Carnegie Mellon University. Before coming to CMU, I worked in a variety of positions in the areas of environmental science and conservation. Some of the more notable examples of the work I've done include 3 years managing a volunteer program at a biological research station in the Peruvian Amazon and a year and a half hunting and removing invasive Burmese pythons from the areas surrounding Everglades National Park in South Florida. <br />
<br />
I also have many interests and pet projects outside of conservation and environmental science. As a student, I tried on majors ranging from digital media and biology (B.S.) to philosophy (M.A.) and, currently, public policy (M.S.), while dabbling in cognitive science, ecology, and social entrepreneurship. Similarly, as a professional, I've worked variously as an environmental consultant, ecotourism guide, HVAC installation technician, volunteer program manager, special education teacher, and python hunter. My most recent projects have focused on public interest technologies that help to increase the range and accessibility of social services worldwide, especially as a means of increasing society's resilience to global threats like climate change.

## What I hope to learn 
In this course, I hope to shore up the foundational knowledge and skills I acquired in my introductory GIS course and begin digging deeper into the advanced capabilities of ArcGIS Pro, especially those that are most highly valued among my prospective employers in the fields of civic tech and environmental policy and sustainability. I also look forward to gaining exposure to additional tools and software used by GIS professionals and integrating my knowledge of these tools with the broader base of knowledge I've acquired during my nearly two years in Heinz College, especially database management, programming, and [data visualization](https://jaxgoodlabs.github.io/campbell-portfolio/).

## Portfolio
Below are some examples of my work.

### Simple iframe insert
This is a simple iframe created on Google Sheets and embedded here. This is only a placeholder to demonstrate that my portfolio is set up properly to publish iframes and will be removed in subsequent weeks of the course.

<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ2Onf8XIOj3ZYJSLff_D9Xh947V9mCuw9lcPUKHoTq7nA7oal4jFPZ0GGU8szrc791OzZUZW7HbI7T/pubchart?oid=2081714158&amp;format=interactive"></iframe>

### Google Map Style: People's Square
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

### Google Map Style: Night Glacier 2
The Night Glacier 2 style was inspired by this image of ice climbers exploring a glacier at night, which I again used Canva to convert into a custom color palette.

<p align="center">
<img width="810" height="275" src="https://user-images.githubusercontent.com/32546509/77257394-5654d000-6c4a-11ea-92b0-7d8fbb566671.JPG">
</p>

The resulting map style is presented below.

<p align="center">
<img width="800" height="535" src="https://user-images.githubusercontent.com/32546509/77254553-171d8380-6c38-11ea-8b6e-5a2ab281bcba.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/GIS_portfolio/night-glacier-2.html) to access the interactive version.

### Google Map Style: Remote Sensing
The Remote Sensing map style attempts to mimic the typical color scheme of an image generated using remote sensing technology. The image that served as my inspiration for this style is presented below along with the color palette generated from it.

<p align="center">
<img width="810" height="275" src="https://user-images.githubusercontent.com/32546509/77257412-7dab9d00-6c4a-11ea-9836-2edfaa506d90.JPG">
</p>

The resulting map style is presented below.

<p align="center">
<img width="800" height="535" src="https://user-images.githubusercontent.com/32546509/77254556-1a187400-6c38-11ea-812d-5e909c2047fd.JPG">
</p>

Click [here](https://jaxgoodlabs.github.io/GIS_portfolio/remote-sensing.html) to access the interactive version.

### ArcGIS Map Style: Plant Growing in the Desert
<img align="left" width="20%" height="20%" src="https://user-images.githubusercontent.com/32546509/77484326-9d84c180-6e00-11ea-8bb3-d4757ef2b7d8.JPG">
For this exercise, I wanted to make another attempt at executing my concept from last week - which, again, was to use a contrasting color scheme to highlight the specific elements of a municipality's physical infrastructure (buildings, highways, etc.) used by commons, cooperatives, and other cooperative enterprises. Similar to the previous exercise, I searched for images following a "life and death" theme, where life was represented by living greenery (trees, plants, etc.) and death was represented by burned or desiccated soil or dull, gray concrete. I ended up using  this image of a plant sprouting in the desert (left).<br />
<br />
A lesson I took away from last week's assignment was that the role of the basemap in a project like I've described is pretty minimal. Most of the contrast I want to draw is between elements of the physical infrastructure, most of which (particularly buildings) is absent from the basemap. For that reason, I decided it was best to use a subtle, low-contrast color scheme for the basemap and give priority to the duller hues, i.e., the browns, taupes, and beiges. I used the greens for their traditional purpose of demarcating parks and natural areas, saving the brighter tones for those map layers I would add later.<br />
<br />
To execute my vision, I selected the Modern Antique template, pictured below. I naturally think of the development of the commons-based infrastructure as a sort of frontiersman/early-explorer sort of enterprise, so I wanted to use a basemap that had an older, antique feel to it. This template also looked like it would work well for the subtle, low-contrast color scheme I had in mind.

<p align="center">
<img width="50%" height="50%" src="https://user-images.githubusercontent.com/32546509/77484415-e3418a00-6e00-11ea-8ea0-5abba8d7dae7.JPG">
</p>

A screenshot of my final map style is copied below. (Click [here](https://arcg.is/1qPCSb) to view the fully interactive version.)

<p align="center">
<img width="100%" height="100%" src="https://user-images.githubusercontent.com/32546509/77484477-0409df80-6e01-11ea-865e-6f1b805e9d65.JPG">
</p>

The big test for how effective my basemap is has to do with how well it supports the message I want to communicate with the layers I add later, specifically, buildings, roads, etc. This is where I'd want to focus my attention when QA-ing the final product. At first glance, I'm satisfied with how everything is rendering. I like the general subdued tone of the map and the old-timey feel it has. 

One change I'd like to make to improve my final map is to dull the color used for certain parks/natural areas. For whatever reason, the template I used automatically dulled the green for most of these areas but left certain polygons with the full color saturation (see, e.g., the top right corner of Schenley Park in the main screenshot above). Because I don't want my basemap to compete with added layers (specifically the physical infrastructure layers that are the map's primary subject), I'd prefer all these areas to be the same shade of green. 

One unanswered question, which may affect my comments above, has to do with which additional map layers end up being relevant to the final map, and how my design choices for those features interact with those of my basemap. For example,  I mentioned that I want to display large portions of the physical infrastructure layers as background/contextual layers also, using a similar color scheme to those I've used for the basemap. (This is necessary, e.g., to highlight those specific portions of that infrastructure that are utilized by cooperative enterprises.) So one thing I'd want to pay special attention to is how well that effect works when it's being duplicated at both the basemap and feature layers, or if, alternatively, I need to make some adjustments to the basemap to preserve the impact at the feature level. 

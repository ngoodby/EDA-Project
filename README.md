# Identifying the Busiest Days and Times at the Busiest NYC Subway Stations

**Abstract**

The goal of this project was to understand which New York City subway stations are busiest and when to inform signature collection efforts by a non-profit called [Transportation Alternatives](https://www.transalt.org/). I worked with NYC Metropolitan Transportation Authority data to identify the ten busiest stations, as well as target days of the week and times that Transportation Authority can use for planning their outreach efforts.

**Design**

The mission of Transportation Alternatives is to *reclaim New York City's streets from the automobile and advocate for better walking, biking, and public transit for all New Yorkers.* Transportation Alternatives plans to collect signatures in support of their NYC 25x25 plan, which will be delivered to NYC’s city council at the end of 2022. They want to identify priority locations, dates, and times for collecting signatures, and subway stations are one of their identified targets. They are interested in identifying the busiest stations and understanding what days and times traffic at those stations tends to be highest.

**Data**

NYC Metropolitan Transportation Authority Turnstile Data: http://web.mta.info/developers/turnstile.html

This analysis began with acquiring all available MTA turnstile data from 2021. This data includes entry and exit counts for the turnstiles across all NYC subway stations. The initial dataset contained 10,717,660 observations. After cleaning the data, 8,646,820 observations remained and were used for analysis and visualization. 

**Materials**

* The code used to bring data from the MTA website into a SQL database can be found [here](https://github.com/ngoodby/EDA-Project/blob/7f20386fa7945d2e92c8811855e6b08bd9c8bc32/get_mta.py). Thank you to to folks at [Metis](https://www.thisismetis.com/) for providing this code. 
* The code used to clean and visualize the data for this analysis can be found [here](https://github.com/ngoodby/EDA-Project/blob/7f20386fa7945d2e92c8811855e6b08bd9c8bc32/EDA_Project.ipynb).
* Slides used to present findings can be found [here](https://github.com/ngoodby/EDA-Project/blob/7f20386fa7945d2e92c8811855e6b08bd9c8bc32/EDA_Presentation_Slides.pdf).
* A brief summary of the project can be found [here](https://github.com/ngoodby/EDA-Project/blob/7f20386fa7945d2e92c8811855e6b08bd9c8bc32/EDA_Project_Summary.pdf).

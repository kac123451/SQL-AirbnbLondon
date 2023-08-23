# Airbnb London Exploration data analysis(EDA)

SQL [here](https://github.com/kac123451/SQL-Projects/blob/main/AirBNB%20London)

As an entry level junior data analysis I want to present to you my Airbnb London hostings analysis in SQL and Tableau.

**Goal is to find general informations, insights and correlations in London bouroughs and 
use data to guide business strategy**

# Ask

* What can we learn about different hosts and areas?
* What can we learn from predictions? (ex: locations, prices, reviews, etc)
* Which hosts are the busiest and why?
* Is there any noticeable difference of traffic among different areas and what could be the reason for it?

# Prepare

Data collected from - https://www.kaggle.com/datasets/whenamancodes/london-uk-airbnb-open-data

Additional source - http://insideairbnb.com/


Tools:
Prepare&Analysis   -> SQL(BigQuery)
Share              -> Vizualizations(Tableau)
# Process & Analysis
**[here](https://github.com/kac123451/SQL-Projects/blob/main/AirBNB%20London)**

# Share&Act

For Tableau vizualizations click [here](https://public.tableau.com/app/profile/kacper.sarwuta/viz/AirbnbLondonreport/Dashboard3)

**Key Insights:**

* **69319** total properties with **45229** unique owners and **£177** Average price per night


* Entire/apartment is the most popular room type **(41,120 hosts)** with an average price of **£227.**
* Private rooms **(27,465)** cheapest option **(£103 average price)** but also the **lowest availability** for rent.
* Only **403** shared rooms with the **lowest average price**
* **231** hotels with the **highest average price £260**


* **Westminster** has the most total hosts **(7758) and rooms (5269)** available in London with an average price of **£345** for available places.
* **Hackney and Tower Hamlets** has the most booked hosts with an average price of under **£100.**


* A total of **39931 (57.6%)** hosts are **available**


* Available hosts are **£94 (56.6%)** more expensive than Unavaiable.**


* **Greenwich and Tower Hamlets** has highest Average **(8.7)** of minimum nights spent


* **Westminster** has highest amount of reviews **(156k)** but City of London is reviewed more often on average with **29%.**


* **36236 hosts with <5 reviews** have the **highest price and highest average minimum nights spent.**


* **Hosts with >20 reviews have the highest availability**
* **Tower Hamlets, Hackney, Islington, Lambeth and Haringey are outliers as from 33 bouroughs only them has more Unavailable than Available hosts**

**Conclusions**
 > * **Consider the number of hosts available, private rooms are the best choice for the lowest prices but there are many people who prefer to pay more for a whole house/apartment and spend more nights on average**
 > 
 > * **As we get closer to centre of London Total hosts are expanding**
 > 
 > * **Of the top 10 locations with highest number of total hosts, Westminster and Kensington and Chelsea have the highest ratio of available hosts at 68% development or investments should consider locations with the lowest ratios such as Hackney(41%), or Tower Hamlets(49%).** We should also take to consideration other aspects like price or availability of land/houses in different areas etc.
 > 
 > * **The total number of available hosts and the price difference between available and unavaiable hosts appear to be correlated**
 > * **Lowering the price of available hosts closer to the price of unavailable hosts may benefit demand - (more analysis required).**
 > 
 > 
> * **Data on reviews does not provide much context for the analysis, as we cannot assess its content against e.g positive and negative reviews.**

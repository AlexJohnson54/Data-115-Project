# Data-115-Project

Repository for Data 115 Personal Project

Motivation

There are two things in the world that I love to do more than anything and those are skiing and traveling. When I can find a way to mix the two together that just creates a perfect scenario for me. This process allows me to take certain parameters and find a way using data to maybe see where I should start when picking where I want to go on my next trip. There are many factors to take into account like would I prefer a trip where I can go to a lot of different ski resorts or a trip where I would stay on one mountain. At the very least I would like to narrow down my options of what area in the world I would like to go to.

Data Source

The data I got was from www.skiresort.info.

Processing Steps

I had to deal with a decent number of missing values as the data set had collected data from the resort’s sites which all have differing details on what the resort would want to include. So what I did from there is found the columns with the largest missing percentages of data and removed a lot of them because when I did a check on what percentage of data was missing it was all the way at 35%. A lot of the missing columns were things like slope preparation, snow reliability, yearly snowfall, as well as the columns about apres skiing. If you don’t know what apres ski is the columns that would fall under that section would be things like hotels, bars, and other commodities that are nearby for vacationers. This removal left us with still a good amount of columns for locations that seem like good viable options for this project. I ended up with finding the columns of continent, country, resort size, and resort difficulty as the most useful columns in the data set after I had done the full cleansing process.

Visualization

![Country's Resorts (2)](https://user-images.githubusercontent.com/78052697/115977716-6b77ee80-a52f-11eb-845d-66279f02af6c.png)

I chose to count the resorts by country to see what country had the highest density of resorts and would allow me to travel amongst different resorts and get a feel of what a country really has to offer. This gave me Germany as the highest cound with Japan and the U.S in second and third.

![ContinentResorts (2)](https://user-images.githubusercontent.com/78052697/115977938-2d7bca00-a531-11eb-8f7a-50c52bf83be1.png)

With countries I saw that Germany, USA, and Japan were the top 3 but then I thought about maybe I should do by continent mainly for Europe as I can easily travel between countries that are in Europe like Germany, Switzerland, and Austria which were all in the top 5 of resorts within countries.

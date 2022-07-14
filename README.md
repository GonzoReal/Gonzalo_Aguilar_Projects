# My Projects By Gonzalo Aguilar




## Descriptive Analysis - Top 10 console players 

#### Project overview 
Analyzing a life-long passion of mine which is gaming! and no better
way to do that by interpreting a dataset I extracted from the web

![This is an image](4e8db1cb9e03af414122bea4c92fee99.jpg)



#### Objectve: Summarize the data and interpret all conclusions 




### Data Collection 

Many tabs later I found the dataset I wanted to work with from a website all about esports and data [HERE](https://www.esportsearnings.com/players/console-players)

I used Google Sheets IMPORTHTML() fuction to import the data into a spreadsheet the field name's are not so pretty to work with in SQL

<img width="1085" alt="Screen Shot 2022-07-12 at 8 51 25 AM" src="https://user-images.githubusercontent.com/104581752/178510597-f0d5f667-b09d-4ff9-961b-8601e6951654.png">


### Data Altering in BigQuery

in order to visualize we need the data be visual ready, next we import the data into BigQuery and transfrom it to our needs below:

* aliasing column names to visulize and summarize the data easier 
* filtering the data to list only the highest earning(last 30 days) console players 
* Limiting the results to focus only on the top 10 players

![This is an image](Screen Shot 2022-07-12 at 11.02.04 AM.png)
ALL SQL QUIERIES [HERE](https://github.com/GonzoReal/Gonzalo_Aguilar_Projects/blob/main/SQL%20QUERIES)

C6, Arcitys, Clayster, Abezy, Simp, and Scump have all earned more than a milion dollars playing videgames specifcally in Call of Duty,
So the next time you tell your kid to stop playing video games remeber that he/she can have a comfortable living.

Ian porter known as C6 in game is the 1# console player by earnings in the last 30 days
![this is an image](https://github.com/GonzoReal/Gonzalo_Aguilar_Projects/blob/main/Dashboard%202-13.pdf)
should C6 worry about the runner up Alec Sanderson know as Arcitys taking his crown? Looking at the highest paid game and 
percent of total says otherwise. 














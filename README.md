# nosql-challenge
### Background
The Food Standards Agency in the UK assesses a range of establishments throughout the country and assigns them food hygiene ratings. You have been engaged by the editorial team of a food magazine named "Eat Safe, Love" to analyze a portion of the ratings data. This analysis will assist their journalists and food critics in determining which establishments to prioritize for future articles.

This challenge includes two part:
### Part 1: Database and Jupyter Notebook Set Up
* Used <i NoSQL_setup_starter.ipynb /i> then imported provided data called <b establishments.json /b> from the terminal.
* The database has been named "uk_food" and the collection is called "establishments". 
* The two libraries, PyMongo and Pretty Print, have been imported.
* An instance of the Mongo Client has been initialized. 
* The successful creation of the database and loading of data has been verified. The collection has been assigned to a variable in order to make it ready for utilization.

### Part 2: Update the Database
* Used <i NoSQL_setup_starter.ipynb /i> for thi section. 
* Added new information to the database, Find the BusinessTypeID for "Restaurant/Cafe/Canteen" then returned only BusinessTypeID and BusinessType fields.
* Updated the new restrant added to the database with its BusinessTypeId.
* Found establishedments in Dover Local Authority and removed it from the database. 
* Converted latitude and longitude data type to decimal numbers using update_many.
* Converted RatingValue data type to integer numbers using update_many.

### Exploratory Analysis
In this section questions from Eat Safe, Love has been answered which will help them find the locations they wish to visit and avoid. 
* Used <i NoSQL_analysis_starter.ipynb /i> To address the questions provided:
    1. Which establishments have a hygiene score equal to 20?
    2. Which establishments in London have a RatingValue greater than or equal to 4?
    3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    4. How many establishments in each Local Authority area have a hygiene score of 0?

<img src="/images/q4.png" width="400" >

### References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. <a href="https://ratings.food.gov.uk/open-data/en-GBLinks" target="_blank">  to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).


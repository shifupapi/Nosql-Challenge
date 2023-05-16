# Nosql-Challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

These were the instructions for this challenge:

Part 1 Database & Jupyter Notebook Setup
•    Imported the data from establishments.json and setup the database and collection from the data that was imported.

Part 2 Updating the database
•    Used Mongo, PyMongo, Python, & Pandas to update the database
•    Updated Business ID field
•    Converted the latitude, longitude, and rating values types to decimal and integer respectively

Part 3: Exploratory Analysis
For part three, this was the code needed to run in the terminal first:
mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json

•    Used queries to find which establishments Hygiene scores were equal to 20.
•    Used queries to find which establishments rating values scores were greater than or equal to 4.
•    Used a query to find the top 5 establishments with a RatingValue of 5, & sorted it by lowest.
•    Used a query to find how many establishments in each Local Authority area have a hygiene score of 0.
•    Sort the results from highest to lowest & printed the top ten local authority areas.




 
 

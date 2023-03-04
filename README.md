# EatSafeLove-nosql

**About this project:**

This 3 part project utilizes MongoDB, NoSQL, and PyMongo to analyze various food establishments for a food magazine called *Eat, Safe, Love*. Results were then converted into pandas DataFrames for exploratory analysis.

**Part 1-2, Setup:**

- Imports the json file, and names the database 'uk_food' and the collection 'establishments'
- Connects to MongoDB and adds a new resturant to the 'establishments' collection
- Drops establishments in Dover
- Updates longtitude and latitude to decimal numbers

**Part 3, Analysis**
- Contains specific queries about resturants and converts results into Pandas DataFrames

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

*please refer to the NoSQL_part1_2_setup.ipynb and NoSQL_part3_analysis.ipynb files for further documentation and answers to queries*

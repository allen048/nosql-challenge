# nosql-challenge

This UK Food Standard Agency involves evaluating various establishments across the United Kingdom, and gives them a food hygiene rating. I was contacted by the editors of a magazine called Eat Safe, Love to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles. In this assignment, I was able to create two Juypyter Notebooks for setup and analysis.

The first Juypyter Notebook is called NoSQL_setup_starter_solution.ipynb. In this notebook, I created a database called uk_food and a collection called establishments through the mac terminal in order to import the required data. The data is stored in the establishments.json file. This notebook required two libraries called PyMongo and Pretty Print. I created a instance of the Mongo Client and confirmed that the database loaded the data properly into MongoDB. I assigned the establishments collection to a variable for use. Also, the database needed some necessary updates to complete this assignment.

The second Jupyter Notebook is called NoSQL_analysis_starter_solution.ipynb. It's an exploratory analysis to find detailed information. There are a total of 4 questions that are needed to be answered. The questions involve data about the establishments' hygiene scores, rating values, nearest locations, and the top ten local authority areas. This information will be used to dive deeper into analyzing the data. I was able to print the results for each of the analyses using the Pretty Print library and create Panda DataFrames that captured each of the results.

• Module 12 Challenge Citations:
'Title:<NoSQL_analysis_starter_solution.ipynb> 'Author:Brandon Knox 'Date:<2023> 'Code Version:<1.0> 'Availability:https://github.com/allen048/nosql-challenge/blob/main/NoSQL_analysis_starter_solution.ipynb
'Code Cited: 
query = { 'geocode.latitude': {'$gte': latitude - degree_search, '$lte': latitude + degree_search},
          'geocode.longitude': {'$gte': longitude - degree_search, '$lte': longitude + degree_search},
          'RatingValue': 5
        }

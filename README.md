# Food Hygiene Analysis

## Project Summary

This project has successfully analyzed food hygiene ratings data from the UK Food Standards Agency to assist the editors of Eat Safe, Love, a food magazine, in selecting establishments for future articles. The analysis was performed in three main parts:

### Part 1: Database and Jupyter Notebook Setup

In this section, the project set up a MongoDB database named `uk_food` and a collection named `establishments` to work with the provided data. The process included importing data from the `establishments.json` file and confirming the proper setup of the database. The required libraries, PyMongo, and Pretty Print (`pprint`), were imported, and the establishments collection was prepared for analysis.

### Part 2: Update the Database

This section involved making specific modifications to the database as requested by the magazine editors. These modifications included adding a new halal restaurant, "Penang Flavours," in Greenwich, updating its `BusinessTypeID`, removing establishments within the Dover Local Authority, and converting certain number values stored as strings to numbers.

### Part 3: Exploratory Analysis

The exploratory analysis section addressed various questions posed by Eat Safe, Love to help them make informed decisions about which establishments to feature in their articles. This involved identifying establishments with specific hygiene scores, finding highly-rated establishments in London, determining the top-rated establishments nearest to "Penang Flavours," and counting establishments with a hygiene score of 0 in each Local Authority area.

## References

- UK Food Standards Agency. (2022). UK food hygiene rating data API. [https://ratings.food.gov.uk/open-data/en-GB](https://ratings.food.gov.uk/open-data/en-GB). Contains public sector information licensed under the Open Government Licence v3.0.

The analysis was conducted with reference to the UK Food Standards Agency's data, accessed on September 9, 2022, and September 12, 2022, with the following establishment settings: `longitude=51.5072`, `latitude=-0.1276`, `maxdistancelimit=4567`, `pagesize=10000`, `sortoptionkey=distance`, `pagenumber=(1,2,3,4,5,6,7,8)`.

This project successfully provided valuable insights into food hygiene ratings, enabling Eat Safe, Love to make informed decisions about the establishments they wish to feature in their magazine articles.

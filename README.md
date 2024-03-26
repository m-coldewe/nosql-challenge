# nosql-challenge
evaluation of data ratings

# Eat Safe, Love - Database Evaluation

## Overview

This project seeks to evaluate some of the ratings data for food magazine, *Eat Safe, Love*, in order to help their journalists and food critics decide where to focus future articles. Utilizes pymongo.

## Purpose

The first part of this project sets up and updates the database: creating the connection, assigning the database and collection to a variable, and adding the the location of the new establishement, then updating the data types associated with longtitude, latitutude and RatingValue to numbers (decimals and intergers, respectively).

The second part analyzes the information within the collection using the following questions:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Results sorted from highest to lowest, with the top 10 Local Authority areas printed. 

## Results

1. Which establishments have a hygiene score equal to 20?
The collection returned 41 locations with a hygiene score equal to 20 for a number of different retail types, including Caring Premises, Hotel/bed & breakfast/guest house, Restaurant/Cafe/Canteen, and Takeaway/sandwhich shops.

2. Which establishments in London have a RatingValue greater than or equal to 4?
The collection returned 33 locations in London that have a RatingValue greater than or equal to 4.

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
The top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant, "Penang Flavours", are: Volunteer, Plumstead Manor Nursery, Atlantic Fish Bar, Iceland, and Howe and Co Fish and Chips.

4. How many establishments in each Local Authority area have a hygiene score of 0? Results sorted from highest to lowest, with the top 10 Local Authority areas printed.
![count_by_area](https://github.com/m-coldewe/nosql-challenge/assets/152045367/833a5248-3973-41f6-8d3c-8a10899f44e3)



## Summary
From this data, we can see that Thanet has the highest number of locations with an excellent hygiene score, with Greenwich coming second. Forty-one locations have a lot of room for improvement in hygiene. Also, Penang Flavours has a number of top-rated options located in close proximity, meaning they will likely have to score well in hygiene and other factors to be competitive in the market.

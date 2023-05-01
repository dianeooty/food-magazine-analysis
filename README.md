# food-magazine-analysis
> Utilizing MongoDB to extract data for the editors of a food magazine adn evaluate the ratings data to determine where to focus future articles.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
Part 1 of this project is to setup the database. Importing the establishments.json file and using Pymongo and Pretty Print libraries to create the database.  Confirm the database and collection were correctly added by checking the list of databases and collections. Then retrieving one document to confirm data was successfully imported.  Then I updated the collection by inserting a new document with the correct Business ID and Business Type. Next, I validated the datatypes and converted the incorrect string datatypes to decimal numbers.

For Part 2 of this project is to complete an analysis of the data. Using Pymongo, I retrieved the establishments with the specified hygiene score of 20, establishments with London as the local authority and rating value of 4 or greater and the top 5 establishments with a rating value of 5 sorted by lowest hygiene score.  The results were then converted to dataframes.


## Technologies Used
- MongoDB
- Pandas
- Python
- Pymongo
- Pretty Print
- JSON


## Screenshots
![1](https://user-images.githubusercontent.com/117790100/223496679-4cf43397-12eb-4aa8-af03-1010ff74826a.png)
![2](https://user-images.githubusercontent.com/117790100/223496682-5b85464f-c676-4a3a-9d3d-1248e4e81527.png)
![3](https://user-images.githubusercontent.com/117790100/223496684-7a2cf7fb-6ef6-4870-a1ed-1648e0b28a30.png)


## Setup
The JSON file used for this challenge can be found in the Resources folder.


## Project Status
Project is complete and no longer being worked on.


## Acknowledgements
- Many thanks to my instructional team and David Chao.


## Contact
Created by Diane Guzman


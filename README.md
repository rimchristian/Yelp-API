# Yelp API Data Project of Korean Cuisines in Los Angeles.


## Project Description:
I am obsessed with all korean food and love sharing people around the world about how great Korean food is. In fact, I love to expand my korean culture through the lens of food. I am aiming for a world, where people can be connected, culturally, through shared dining experiences. 

This data project showcases feature engineering and geospatial visualization of Yelp search results for Korean cuisines in Los Angeles. The project aims to provide insights into the distribution and characteristics of Korean restaurants in the Los Angeles area. 

## Project Structure:
For this project, I wanted to extract data from the Yelp API and explore the LA food scene.  I mainly performed API Extraction in a JSON file, then converted into a pandas dataframe. Once I got my API key from Yelp API, I loaded the data into a JSON file. I defined the terms by creating the Location and Term keyword. 

## Table of Contents
- Data
- Features
- Results
- Acknowledgements
- License

### Data
To use this project, follow these steps:
The data used in this project is sourced from Yelp and includes information about Korean restaurants in Los Angeles. The dataset, yelp_data.csv, contains the following columns:

name: The name of the restaurant.
address: The address of the restaurant.
latitude: The latitude coordinate of the restaurant's location.
longitude: The longitude coordinate of the restaurant's location.
rating: The average rating of the restaurant.
price: The price range of the restaurant.

### Features
In this project, I performed the following feature engineering steps:

Data cleaning and preprocessing.
Exploratory data analysis to understand the characteristics of the dataset.
Geospatial visualization using Plotly to plot the restaurant locations on a map of Los Angeles.

### Results
The project's main result is a geospatial visualization that shows the distribution of Korean restaurants in Los Angeles. The map highlights the locations of the restaurants and provides additional information such as restaurant names, ratings, and price ranges. By analyzing the map, users can gain insights into the concentration of Korean restaurants in different areas of Los Angeles.

### Acknowledgements
The Yelp dataset used in this project is sourced from the Yelp Fusion API (https://www.yelp.com/fusion).
The project was inspired by the need to explore and visualize the presence of Korean cuisines in Los Angeles.

### License
This project is licensed under the MIT License.

Feel free to customize the sections and content according to your specific project. Make sure to include any relevant images or files (such as the map image) and update the file and directory names as necessary.

## Data Analysis Implementation:
I have learned a lot of concepts from coding efficient API Data to EDA. I am still working on developing this project. Stay Tuned. 
Here are the steps I took to identify the restaurants in Los Angeles. 
1. Get the API Key from the Yelp Developer Site. Save it to a safe place in your computer - hidden folder. 
2. Open and access the API JSON File in Jupyter Notebook. 
  - Create a function to create a JSON file
4. Convert the JSON files to pandas dataframes. 
  - All the data cleaning and EDA analysis.
5. Data Visualiation 

## Technologies used in this project
- Python
- Pandas, matplotlib
- Plotly

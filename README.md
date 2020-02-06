#  IBM Data Science Capstone Project 
## Planning Travel and Tours in New York City's Broadway Theatre District
### Comparison of Hotels, Restaurants, and Theaters in Manhattan, NY for a Broadway Theater Trip
### Brian Vineyard 

## INTRODUCTION

This is my final Capstone Project for the IBM Data Science Professional Certification through Coursera.

Students were tasked with using data science tools and methods to do a detailed study of a city using the Foursquare API.

This project involved the use of Python 3 and Jupyter Notebooks. Tools used include pandas, numpy, JSON, pickle, GeoPy, BeautifulSoup, matplotlib, and sklearn.

### Business Problem


**Business Problem**: A travel service is planning to offer Broadway trips with the best options in New York City, NY to include on their package. They want to build a package with a list of Broadway shows, a recommended hotel, and a list of nearby restaurants. 

Their clients are mostly interested in Broadway musicals and plays, so this project will focus on finding the best hotel and restaurants near the Broadway theater district.

![Broadway](77.jpg)

**Key Questions to Answer**

- What are the best theaters to catch the top Broadway shows?
- What hotels close to the Theater District have the best ratings and room rates?
- What are the best nearby restaurants?


**Foursquare API study of following city**:

- Broadway Theatre District, New York City, NY

Example search criteria: Hotels, Restaurants, Museums, Live Shows

**Project Details**: 

This project uses the following tools and technology:

- [Foursquare Places API](https://https://enterprise.foursquare.com/products/places)
- [2014 New York City Neighborhood Names](https://geo.nyu.edu/catalog/nyu_2451_34572)
- [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/)


The goal is to find the best area of the city to hold tours, based on our findings.

## DATA SOURCES

This project will use the following data:

- **Latitude and longitude of neighborhoods from the five boroughs of New York, NY**
  Source: 2014 New York City Neighborhood Names: https://geo.nyu.edu/catalog/nyu-2451-34572
- **Broadway Theatre Wiki with Current Shows in Production**
  Source: https://en.wikipedia.org/wiki/Broadway_theatre
- **Hotels and Restaurants near the Richard Rodgers Theatre - (where *Hamilton* is playing)
  Source: API Queries of Foursquare 
 - **Reviews of Hotels and Restaurants in the Foursquare Dataset
  Source: Google Reviews, Hotels.com data

##METHODOLOGY

The coordinates will be passed to the Foursquare Places API, for querying New York City neighborhoods for venues such as:

- **Restaurants**
    - Liebman's Deli, La Morada, Royal 35 Steakhouse, Le Benardin
- **Hotels**
    - Gramercy Park, Life Hotel Nomad, Mansfield Hotel
- **Fun**
    - Museums: Metropoliton Museum of Art, 9/11 Memorial, American Museum of Natural History
    - Top Tourist Destinations: Empire State Building, Madison Square Garden, Statue of Liberty, Times Square
    - Broadway Productions: Hamilton, The Lion King, Wicked, Moulin Rouge, Phantom of the Opera
    - Sightseeing Cruises: Circle Line Full Island, Classic Harbor Lines, Zephyr Yacht, Liberty Cruises
    - Parks: Central Park, Washington Square Park, Fort Tryon Park, Bronx Zoo, 
    
 ### Table of Contents
 1. [Import Libraries, Foursquare Credentials](#import-1)
 2. [New York's Manhattan Borough Neighborhood Data](#borough-2)
   - [Map of Neighborhoods in New York City's Five Boroughs](#borough-map)
   - [Map of Neighborhoods in NYC's Manhattan Borough](#neighor-map)
 3. [Broadway Theatres and Current Productions](#broadway-3)
   - [Map of Broadway Theatre Locations](#broadway-map)
 4. [Hotels Near the Broadway Theatre District](#hotels-4)
   - [Map of Hotels Near Broadway Theatres](#hotels-map)
 5. [Restaurants Near the Broadway Theatre District](#restaurants-5)
   - [Map of Restaurants Near Broadway Theatres](#rest_map)
 6. [Conclusions and Findings](#conclusions)
 
## 1. Import Libraries, Foursquare Credentials, and Neighborhood Data <a name="import-1"></a>



## 2. New York's Manhattan Borough Neighborhood Data <a name="borough-2"></a>
###  Map of Neighborhoods in the New York City' Five Boroughs <a name="borough-map"></a>
### Map of Neighborhoods in NYC's Manhattan Borough <a name="neighbor-map"></a>
## 3. Broadway Theatres and Current Productions <a name="broadway-3"></a>
## 4. Hotels Near the Broadway Theatre District <a name="hotels-4"></a>
### Map of Hotels Near Broadway Theatres <a name="hotels-map"></a>
## 5. Restaurants Near the Broadway Theatre District and citizenM Hotel <a name="restaurants-5"></a>
### Map of Restaurants Near the Broadway Theatre District <a name="rest-map"></a>
## 6. Conclusions and Findings <a name="conclusions"></a>

## RESULTS

## CONCLUSION


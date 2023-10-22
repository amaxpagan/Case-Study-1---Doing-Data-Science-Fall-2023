# Case Study 1 - Doing Data Science Fall 2023
## Christian Castro and max Pagan
### 10/21/2023

### Introduction and Purpose:
The purpose of this study, conducted by Max Pagan and Christian Castro, is to analyze data on beers and breweries in order to provide insight to Budweiser’s CEO and CFO that could help the company within the marketplace. The team used various statistical methods to investigate and collect evidence of relationships between variables that might prove helpful with further data and research. Looking at the data, the variables of Alcohol by Volume (ABV), International Bitterness Units (IBU), the names of the beers, the styles of the beers, and the names of the breweries were vital to understanding market trends and preferences. 

### Codebook: 

#### Transformations and merging:
First, any row missing both ABV and IBU were removed since there was not enough data to infer the values. Afterwards, the mean IBU values were used to fill in missing values. 
The data was merged by combining data sets and relating them through the Brewery_ID and Brew_ID variables. 

#### Environment:
The R session used various libraries dplyr, tidyverse, naniar, class, caret, and ggplot2.

#### Data Dictionary:
Beers data set
	
	Name - the name of the beer
 
	Beer_ID - the individual identifier of the beer
 
	ABV - the alcohol by volume of the beer
 
	IBU - the International Bitterness Unit rating of the beer
 
	Brewery_ID - the individual identifier of the beer brewer
 
	Style - the style and type of the beer
 
	Ounces - the size/content of the beer distributed
 
Brewery Data set

	Brew_ID - the individual identifier of the beer brewer (same as Brewery_ID in Beers data set)
 
	Name - the name of the brewery
 
	City - the city where the brewery is located
 
	State - the state where the brewery is located 
 


#### System info:
Processor    12th Gen Intel(R) Core(TM) i7-12700H   2.30 GHz

Installed RAM    16.0 GB (15.7 GB usable)

Device ID    611AC12A-7DE3-4F9B-9CB8-5800CEBEBA14

Product ID    00342-20843-04747-AAOEM

System type    64-bit operating system, x64-based processor

Pen and touch    Touch support with 10 touch points

Edition    Windows 11 Home

Version    22H2

Installed on    ‎12/‎12/‎2022

OS build    22621.2428

Experience    Windows Feature Experience Pack 1000.22674.1000.0

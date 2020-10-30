# IBM Professional Data Science Capstone Project

## Project title: 
'The battle of the Neighborhoods: How does population density influence business decisions?'

## Background and Problem

An important business strategy is to understand the factor that could be important for maximizing
profit. One factor is location of business enterprise. The location of a business can influence the
availability of demand and traffic of people seeking goods and services. Higher traffic can drive up
the chance of increasing and maintaining profits. High demand of people correlates with location
with higher population density. An example of a city with this high population density is New York
city. New York city is one of the top ten cities in the world with the highest population density per
square mile. New York city is considered the capital of the world, because of its unique
multicultural population, and diverse business and entertainment enterprises. In this study, analysis
of a good and service, the bakery industry, and the relationship of the population density in
different neighborhoods, in the big Apple, are determined. The understanding of the relationship
between these population density and the density of bakeries by neighborhood would enlighten
business decision for potential stakeholders to determine what neighborhoods need to a particular
good or service.

## Methodology 

* Python
* FourSquare API
* IBM Watson Studio
* Jupyter Notebook
* Pandas Library
* Request Library
* Numpy Library 
* Seaborn Library
* ScikitLearn Library
* Folium Library
* GeoPy Library

## Data

The data for this project were obtained from different sources and via different techniques. The
population data, the regular and polygon geoJSON of New York city containing the Manhattan
Borough by Neighbourhood were downloaded from the internet. Specifically, the data of the top places to
go in Manhattan were scraped from the FourSquare site using the developer API access with a radius of 500 and limit of 1000 places.

## Visualization 

1. New York City Population Density

![Population_density_Manhattan](https://user-images.githubusercontent.com/59964869/97740688-08455c00-1ab8-11eb-83c4-308176564831.JPG)
2. Modeling
* Linear Regression

![SeabornLinearRegressionPlot](https://user-images.githubusercontent.com/59964869/97741284-d4b70180-1ab8-11eb-8488-3f4a2d98d4c6.JPG)

* Polynomial Regression, Power of 2

![power2](https://user-images.githubusercontent.com/59964869/97741294-d8e31f00-1ab8-11eb-8693-0b26945930bf.JPG)
![power2_RSquareScore](https://user-images.githubusercontent.com/59964869/97741305-dd0f3c80-1ab8-11eb-8a27-6b5f48f86d65.JPG)

* Polynomial Regression, Power of 6

![power6](https://user-images.githubusercontent.com/59964869/97741319-e6000e00-1ab8-11eb-9001-36ccc6366d4a.JPG)
![power6_RSquareScore](https://user-images.githubusercontent.com/59964869/97741326-ea2c2b80-1ab8-11eb-8299-2f9d9455b11f.JPG)

## Conclusion
There isn't a significant relationship between number of bakeries and population density for
a linear fit and polynomial fit at a power of 2 and 6. Business associates are advised to look at other variables such as access to public
transportation, distribution of schools, parks and so on in different neighbourhoods in a city to
determine where to open a bakery for the highest profit possible.

### Certificate awarded April 15th, 2020
![CertificateIBMDataScience](https://user-images.githubusercontent.com/59964869/97740948-5ce8d700-1ab8-11eb-9c65-ef46805c5597.JPG)

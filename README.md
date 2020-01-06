# King County House Price Project
King County house price project - first project done in a datascience bootcamp

In this python project I will be analysing a provided dataset of house prices and features of King County.
The data consists of entries from the years 2014 and 2015.

The following features are present in the dataset. Of these the target variable was the price of a house.
* **id** - unique identified for a house
* **date** - date house was sold
* **price** -  is prediction target / house price
* **bedroomsNumber** - Number of Bedrooms
* **bathroomsNumber** - Number of bathrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront / has a waterfront
* **view** - Has been viewed ?? - An index from 0 to 4 of how good the view of the property was 
* **condition** - How good the condition is ( Overall ) dependent on year built and grade
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors

The model used for predicting the house price was Linear Regression.
In the end it had a realistic accuracy of 78%.

In conclusion there surely have to be other features not present in this dataset, which influence the price of a house.
Some of which could be explored further, like:
* crime statistics
* quality of the land
* economic distribution
* public transportation
* or the distribution of schools and their quality

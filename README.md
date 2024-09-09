Module 6 - python-api-challenge
Commleted WeatherPy.ipynb and VacationPy.ipynb scripts are saved in the WeatherPy directory within this repo. The requisite csv and plot (png) files are included in the output_data repository. 
To complete this homework, the zoom class recordings were used to review the material and activities covered in class. These along with the following internet sources were used as reference: stack overflow, pandas.pydata.org, https://openweathermap.org/current#parameter (to understand parameter structure)
and https://apidocs.geoapify.com/docs/places/#categories (to understand geoapify categories). 

A .gitignore file was added to the repo to protect the api_keys used for this assignment. 

The the citipy Python library and the OpenWeatherMap API with previously ascertained api key were used to complete WeatherPy.ipynb. Random geographic coordinates were generated with nearby cities. Various parameters (humidity, cloudiness, maximum temperature, etc) were extracted for each city. The data
was divided into northern hemisphere cities and southern hemisphere cities. Several variables were plotted against latitude to determine if latitude contributed to the variance in any of these variables in a linear way. Linear regression and measurment of the coefficient of determination
were used to demonstrate how well the data fit a linear model. General conclusions were drawn about the relationships of the variables to latitude in the northern and southern hemispheres.

To complete the VacationPy.ipynb script, Geoapify API and hvplot.pandas were used to plot the cities in the cities.csv file from part 1 of the homework. The data were filtered to desirable parameters for a vacation (e.g. certain temperature range, wind and cloud coverage). 
Geoapify was used to find hotels within 10,000 miles of the "desirable" cities from hotel_df and plotted on a second map. Hover over attributes as well as coloring by latitude were used to show cities were being pulled from all over the world (not just one region). 

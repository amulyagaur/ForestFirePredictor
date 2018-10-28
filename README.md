# ForestFirePredictor
Predicting the magnitude of area affected by Forest Fire

In this task, the aim is to predict the burned area of forest fires, in the northeast region of Portugal, by using meteorological and other data.

# Evaluation metric
RMSE 

# File Description
train.csv - training data<br>
test.csv - testing data

# Data Field Description
Id - id of the datapoint within a given data file<br>
X - x-axis spatial coordinate within the Montesinho park map: 1 to 9<br>
Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9<br>
month - month of the year: 'jan' to 'dec'<br>
day - day of the week: 'mon' to 'sun'<br>
FFMC - FFMC index from the FWI system: 18.7 to 96.20<br>
DMC - DMC index from the FWI system: 1.1 to 291.3<br>
DC - DC index from the FWI system: 7.9 to 860.6<br>
ISI - ISI index from the FWI system: 0.0 to 56.10<br>
temp - temperature in Celsius degrees: 2.2 to 33.30<br>
RH - relative humidity in %: 15.0 to 100<br>
wind - wind speed in km/h: 0.40 to 9.40<br>
rain - outside rain in mm/m2 : 0.0 to 6.4<br>
area - the burned area of the forest (in ha): 0.00 to 1090.84 (this output variable is very skewed towards 0.0, thus it may make sense to model with the logarithm transform)

# [Contest Link](https://www.kaggle.com/c/logicalrhythm18-fire/)

# Result 
Rank : 16<br>
Score : 153.85798

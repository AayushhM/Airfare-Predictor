
# [Airfare Predictor](https://airfare-predictor-production.up.railway.app/)

This code is a Flask web application that predicts airfare prices based on user inputs. The prediction is made using a pre-trained machine learning model, which is loaded using the pickle library when the application starts. The model was trained on features such as departure time, arrival time, duration, total number of stops, and airline.

The user inputs are taken from an HTML form and then processed and used as the features for making the prediction. The processed inputs include the departure and arrival times, duration, and the selected airline. The processed inputs are then passed to the pre-trained machine learning model to make the prediction, which is then returned to the user.

The model used in this code is Random Forest Regressor, which is an ensemble learning method for regression. It builds a set of decision trees and outputs the average prediction of all the trees.


## Demo

The app has been deployed on Railway:
https://airfare-predictor-production.up.railway.app/



## Screenshots

![App Screenshot](https://user-images.githubusercontent.com/13918412/218329384-0ccfda8f-2277-47d3-9f98-8969f6c3f62a.jpeg)

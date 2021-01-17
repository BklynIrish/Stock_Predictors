# Stock Predictor
Final Project Deployed using heroku at https://stock-predictor1.herokuapp.com

In this project, we used machine learning models to explore the behavior of two different stocks. The stocks we chose were Cisco Systems, Inc. (CSCO) and New Oriential Education (EDU). Cisco Systems (CSCO) supplies hardware and software for networking solutions and other communication needs like mobility and sercuirty. It provides provides software and security for telemedicine platforms, 5G mobile connections, and  platforms for companies to analyze data through AI and machine learning. New Oriental Education & Technology Group (EDU) provides remote educational services to people in China. Both these companies are positioned in industries that are set to grow, but we wanted to see if we could predict their future stock prices using past prices. We used a two different types of machine learning Long Short-Term Model to predict future stock prices based. We used a Multi-variate linear regression to anaylze the impact that certain fundementals had on a stock's price. Below are some screenshots of interactive plots predicting future behavior of both of the two stocks analyzed.

EDU Future Prediction (.png file)
https://github.com/BklynIrish/Stock_Predictors/blob/main/Models/EDU_Future_Prediction.png?raw=true

CSCO Future Prediction (.png file)
https://github.com/BklynIrish/Stock_Predictors/blob/main/Pictures/CSCO_Future_Prediction%20copy.png?raw=true

## Deployed Version (as seen above)
https://stock-predictor1.herokuapp.com/

## Tools and Resources
* Python
* Machine Learning
* HTML / JavaScript/ CSS/ Bootstrap
* Flask
* Mongo DB
* Plotly
* Libraries:
  * tensorflow.keras.layers import LSTM 
  * tensorflow.keras.models import Sequential
  * tensorflow.keras.layers import Dense
  * tensorflow.keras.layers import Activation
  * tensorflow.keras.layers import Dropout
  * numpy import array
  * pandas as pd
  * numpy as np
  * sklearn.model_selection import train_test_split
  * matplotlib.pyplot as plt
* Heroku
 * gunicorn
 * Procfile
 * requirements.txt
 

# IPL Score Prediction Model

This project uses a machine learning model to predict the total score in an IPL match based on various input features. The model is implemented using Python, Keras, and TensorFlow, and it is deployed with Django.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/GJ-sanjay/ipl-score-prediction.git
   cd ipl-score-prediction
2. Usage guide:
   ~ just pip install the requirements if you're using google colab this will make it much easier. 
   ~ I've also given the dataset (.csv) file to use.
   ~ why use huber loss? It's less affected by outliers or anomalies present in the data set. A simple extremely less outlier can affect the entire prediction here. That's why 
   using huber loss would be the most effective approach here. As it allows a balanced prediction
   ~ Label encoding allows us to transform the categorical values to numerical formats
   ~ using Minmaxscaler() allows the values to be rounded from 0 to 1 
   ~ Then we train the model and use pywidgets to display the results

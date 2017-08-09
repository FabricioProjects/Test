### Price Prediction Challenge
**Load and preprocessing data:**  
Strings like 'residential' from 'property_type' feature was transformed to numbers. All the values are normalize to [0,1] range (this helps when using Sigmoid as an output activation function). The 1st feature 'apn' has many unique numbers (almost all of them) so I decided to drop it to avoid decorrelation. 

**Models:**  
The first model is the k-nearest neighbors non linear approach. I'm using Deep Neural Networks as the 2nd prediction model. I didn't had time to appropriately fine tunning the DNN model so is expected better results than showed in here  

**Run both models:**  
The 'main' cell will run and show the results of both models. Just pay attention on the output prints to see the results provided by 'Mean Absolute Error'. I'm avoiding 'Mean Absolute Percentage Error' here because this method have high chances to produce division by zeros.  

**Dependencies:**
pandas  
numpy  
sklearn  
matplotlib  
keras (tensorflow as backend)



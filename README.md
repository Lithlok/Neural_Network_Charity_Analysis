# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is to use Neural Networking to create models that will predict an outcome based on training and testing input. 
This is achieved through feeding the input data into the model, modifying the amount of layers and the nodes in each layer, and choosing the 
activation method which produces the most favorable output.


## Results

The target variable is the "Is_Successful" column, while the features are the rest of the columns which are not indiidual identifiers. 
Those were dropped, EIN and Name, because they didn't contribute usable data in the model.

I used 2 hidden layers in my network, the first had 8 neurons while the second had 3 so as to not overfit the data. I chose the RELU 
activation as that seemed the most applicable given the dataset.

I was Not able to achieve the target model performance. I had a training loss of 74 and an accuracy of 64% prior to optimization.. I attempted 
various numbers for my network layers, but I found that the one suppled here worked the best and i couldn't shave 4 more percentage points out of it. 
The final optimized result was a loss of 66 and an accuracy of 71%.


## Summary 

After the deep learning model was performed the accuracy can only be seen as dissapointing at the accuracy of 71%. i believe that the Logistics Regression Model 
would have worked just as well if not better than the weighted model.
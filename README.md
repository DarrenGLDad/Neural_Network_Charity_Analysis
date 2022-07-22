# Neural_Network_Charity_Analysis

## Overview of the analysis: 
- The purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 

#### Data Preprocessing

- What variable(s) are considered the target(s) for your model?

  - The variable/feature that is considered the target in the model is the "IS_SUCCESSFUL" column.

- What variable(s) are considered to be the features for your model?
		
  - All of the variables except for the target would be considered features.

- What variable(s) are neither targets nor features, and should be removed from the input data?

  - EIN & Name columns were removed and would not be considered for the training of the model; these would be arbitrary.
  
### Compiling, Training, and Evaluating the Model
        
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

  - I intuitively selected random numbers in hopes to reach my 75% accuracy.  I added an additional layer, resulting in a total of three, and I elected to have 114 in layer-1, 64 in layer-2, and 14 in layer-3. In the 2nd & 3rd attempts I changed the activation function to "tanh". There is no rule of thumb, the only to ascertain optimal performance is through trial & error, with the barometer being noticeable improvements...

	<img width="909" alt="Screen Shot 2022-07-17 at 5 35 04 PM" src="https://user-images.githubusercontent.com/100239100/179425588-f402598d-d7a5-40ba-a50a-192d316e3448.png">


- Were you able to achieve the target model performance?
		
  - No, but I was able to increase the accuracy by a percentage point.

- What steps did you take to try and increase model performance?

  - I added an additional layer, as well as adding additional neurons in the first & second layers. I also decreased the number of epochs; furthermore, I changed the activation function with the intent of increasing accuracy and performance.

### Summary: 

The overall result or the accuracy of this specific machine learning model seems to only attain a mid-70% at best; this could be satisfactory for some industries.  I would recommend a Support Vector Machine since these are used for binary classifiying, but not a Linear Regression model, although they're utilized for binary-like decisions, these are more suited for two-group-continuous-categorical variables.

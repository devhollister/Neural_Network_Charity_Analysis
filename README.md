# Neural Network Charity Analysis

## Overview of the analysis: 

The purpose of this analysis is to create a binary classifier that is capable of predicting whether charity applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing
* The “IS_SUCCESSFUL” variable is the target for the model.
* The are the features of the model.
* The columns are not useful and should be dropped. 

### Compiling, Training, and Evaluating the Model

*  The model was initialized with 80 neurons in the input layer, as the are 40 features. 
*  Target model achievement was not reached.
* The following steps were taken to increase model performance: 
  - dropping the “STATUS”, “SPECIAL_CONSIDERATIONS_Y”, and “SPECIAL_CONSIDERATIONS_N” columns
  - adding another hidden layer 
  - increasing neurons
  - changing input activation from “relu” to “sigmoid”

## Summary: 

The accuracy remained near 72% for all versions of the model attempted. Accuracy could potentially be further increased by adding bins to the “ASK_AMT column. It may also be possible that a Random Forest Model may be better suited for this problem.  

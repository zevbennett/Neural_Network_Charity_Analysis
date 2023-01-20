# Neural Network Charity Analysis

The purpose of this analysis is to predict if applicants for the Alphabet soup funding will have successful ventures. 

## Results

- The target variable was IS_SUCCESSFUL. Which describes whether or not the venture was sucessful 
- The Features were: Application type, Affiliation, Classification, Use case, Organization, Status, Income amount, Ask amount, and special considerations.
- There were identification numbers as well as the name of the organization which were dropped from the machine learning inputs, as they were not features or targets.


- I used two hidden layers the first with 8 nerons, and the second with 5 neurons
    - this seemed to be a good balance of complexity of the model
- I was not able to achieve target performance
- I tried using a different activation function (tanh instead of relu) to improve the performance.
    I also tried increasing the number of epochs, and adding more neurons.

## Summary
The results were not so impressive. The best model I came up with only produced an accuracy of around 70%. This is not quite enough. If I were to do this again, I would use a hypertuner to find the ideal machine learning parameters, because on my own I didn't find a satisfactory setup. 
This is poentially suitable for another supervised machine learning program, perhaps a random Forest model. That may have more success. 
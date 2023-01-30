# Neural_Network_Charity_Analysis

## OVERVIEW

The purpose of this analysis was to utilize neural networking using Tensorflow, and to be able to try and figure out how to adjust certain parameters to either increase or decrease accuracy. Within the scope of the activity, we were seeing how accurately we could determine if a company which received funding would be succesful or unsuccesful.

## RESULTS

1. Wether a company was succesful or unsuccesful was the target variable for the model.
2. The company being IS_SUCCESFUL is the feature for this model.
3. EIN and NAME were unrelated variables, which we were able to take out to remove excess information.
4. We had 3 layers in this model, with the first having 80 neurons, the second having 20, and the last having 1 neuron. As for the activation functions, we used sigmoid, relu, then linear, in that respective order.
5. I was unable to reach the target performance of 75%, with the highest I was able to achieve being 72.5% accuracy. 
6. In an attempt to increase model performance, I took out a column I believe was extraneous, I cut off at higher increments, being 1000 and 2000 for the classification count, and I increased the number of neurons. However, this ended up actually slightly lowering the accuracy.

## SUMMARY

After some testing, it seems to not be able to achieve an accuracy of 75% or higher, so perhaps another method should be tested to see if it returns better results.

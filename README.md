# Neural_Network

## Overview

### On this challenge the purpose was to run a nerual network that will say where to put the money for the charity in. 

## Results

### The targets for the model are Classification and Application Type. The features for the model to me are Affiliation, Organization, Income Amount, Special Considerations. Last the variables that are neither to me would be EIN, Name, and Use Case. For the first run I used 80 neurons on the first hidden layer and 30 on the second. On the activation I used relu. I did this because the relu solves the vanishing graident issues and I thought that would be the best chance to get over 75. However this did not achieve the target, it only gave me a result of .719. So on the second one I added another hidden layer and did 100 neurons on the first layer, 50 on the second and 20 on the third. This actually made the preformance lower at .718. on the third one I used a different activation function and doubled the amnount of epochs. However the rsult was only .717. 

## Summary

### Unfortunately out of the 3 attempts I was not able to reach the target. I think a better step would be to drop more of the columns so the data is more focused and adding more neurons. I think the relu activation is still the best one to use given the results that I was given. 

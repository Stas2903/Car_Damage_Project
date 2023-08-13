## Introduction

    The growth of commercial car sharing and delivery to the venue results in a growing number of drivers per vehicle. 
    With this trend, the complexity and liability for insurance companies and car owners increases drastically. Therefore, a thorough inspection at each handover is preferred. 

    The common manual inspection method presents problems of low efficiency and time consumption, as well as inadequate and failed detection. 
    To avoid delays in the process, in terms of cost and ease of usage, a more automated and efficient inspection is required. 

## Objective

    One of many ways is to detect anomalities are by comparing an object of interest with an undamaged representation to align the damaged vehicle with a whole, following the testing and training of the results obtained.

    In this project we are aiming to evaluate prediction models, alongside the classification of images using Convolutional Neural Networks.


# Conclusion

## Training & Evaluating CNN
 
    Target size: 64 x 64:

          > training process is smooth and relatevely stable
  
          > loss is about 0.35
  
          > accuracy is more than 85%

    
    Target size: 128 x 128:

          > training process is a bit unstable
  
          > loss is about 0.55
  
          > accuracy is about 74%

        
    I suppose that the performance of the model with input size 128 X 128 might be imporved by experimenting the the architecture of the CNN hiden layers.

    Overall, I suppose that it is better to use the input size of 64 X 64 because it shows higher performance and less loss as well as trainig time.

# THANKS!!! :)

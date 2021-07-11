# ICCV-2021-Workshop-MIA-COV19D-TeliNet

This repository is the code for entry to ICCV 2021 Workshop: MIA-COV19D, https://mlearn.lincoln.ac.uk/mia-cov19d/.

This code classifies CT Scan COVID-19 images as covid and non-covid using a four layer Convolutional Neural Network.


## Getting Started

Clone this repository using 

``` 
git clone https://github.com/nayeemmz/TeliNet.git 
```

The data directories structure should be 

 
 * ``` 
    train
    |-- covid
        |-- images
         
    |-- non-covid
        |-- images
 
   ```
 * ```
   validation
   |-- covid
        |-- images
         
    |-- non-covid
        |-- images
   ```
 * ```
   train
   |-- to_be_predicted
       |-- images
 ```
 
 ``` 
 
## Dependencies

* matplotlib==3.3.3
* tensorflow==2.5.0rc2
* numpy==1.19.5
* tensorflow_addons==0.13.0

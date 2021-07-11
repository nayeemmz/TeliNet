# ICCV-2021-Workshop-MIA-COV19D-TeliNet

This repository is the code for entry to ICCV 2021 Workshop: MIA-COV19D, https://mlearn.lincoln.ac.uk/mia-cov19d/.

This code classifies CT Scan COVID-19 images as covid and non-covid using a four layer Convolutional Neural Network.

## What's included

In the repo there are three Jupyter notebooks in the Notebooks folder

```
preprocessing.ipynb 
``` 
This file provides the code for processing the files in the directory structure provided below.

```
teliNet.ipynb
```
This is the main file that contains the code for the CNN architecture that we propose in this research. It contains the code for training, validations as well as testing.

```
covid_ct_classification-VGG16.ipynb
```
This file contains only the code for training and validation datasets using VGGNet-16 architecture. Since its performance is not better than teliNet architecture, we do not run it on the test set.




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

## Contact

Contact ``` 
nayeem@umd.edu ```to ask questions or report issues, please open an issue on the issues tracker. Discussions, suggestions and questions are welcome!

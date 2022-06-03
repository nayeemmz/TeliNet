# ICCV-2021-Workshop-MIA-COV19D-TeliNet

This repository is the code for ICCV 2021 Workshop: MIA-COV19D, https://mlearn.lincoln.ac.uk/mia-cov19d/, in ICCVW: AI-enabled Medical Image Analysis Workshop and Covid-19 Diagnosis Competition (MIA-COV19D), International Conference on Computer Vision (ICCV) 2021, Montreal, Canada, October 11- 17, 2021.

This code classifies CT Scan COVID-19 images as covid and non-covid using a four layer Convolutional Neural Network.

## Paper Abstract
COVID-19 has led to hundreds of millions of cases andmillions  of  deaths  worldwide  since  its  onset.    The  fightagainst this pandemic is on-going on multiple fronts. Whilevaccinations  are  picking  up  speed,  there  are  still  billionsof unvaccinated people.  In this fight against the virus, di-agnosis of the disease and isolation of the patients to pre-vent any spread play a huge role.   Machine Learning ap-proaches have assisted in the diagnosis of COVID-19 casesby analyzing chest X-rays and CT-scan images of patients.To push algorithm development and research in this direc-tion of radiological diagnosis, a challenge to classify CT-scan series was organized in conjunction with ICCV, 2021.In  this  research  we  present  a  simple  and  shallow  Convo-lutional Neural Network based approach, TeliNet, to clas-sify these CT-scan images of COVID-19 patients presentedas part of this competition.  Our results outperform the F1‘macro’ score of the competition benchmark and VGGNetapproaches. Our proposed solution is also more lightweightin comparison to the other methods.

## What's included

In the repo there are four Jupyter notebooks in the Notebooks folder

```
* preprocessing.ipynb 
``` 
This file provides the code for processing the files in the directory structure provided below.

```
* teliNet.ipynb
```
This is the main file that contains the code for the CNN architecture that we propose in this research. It contains the code for training, and testing on the validation data set.

```

* teliNet-test-Code.ipynb
```
This file contains the code for testing data set. We have divided the code to report results on each subset of the test data set separately.

```

* covid_ct_classification-VGG16.ipynb
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

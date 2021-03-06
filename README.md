# IBM Coursera Capstone: Seattle Car Collision Severity factors

![Python 3.6](https://img.shields.io/badge/python-3.5%20%7C%203.6%20%7C%203.7-blue.svg)

## Describe project

It is always rainy and windy in Seattle, and on the way, you always come across a terrible traffic jam on the other side of the highway, with long lines of cars barely moving. It would be great if there is something in place that could warn you, given the weather and the road conditions about the possibility of you getting into a car accident and how severe it would be, so that you would drive more carefully or even change your travel if you are able to.

<p align="center">
<img src="https://github.com/eliuqiong/IBM_Coursera_Capstone/blob/master/Results/Seattle%20Injury%20Collision%20Heatmap.png" width="60%" height="60%">


## Objective

Luckily enough, The Seattle Police Department (SPD) has recorded all car collision accident from 2004 to present. Basing on those historical data (194,673 records), we can create a map and information chart to help us understand the high-risk areas, understand car injury factors to avoid accident, and plan our next trip to Seattle better.

## Datasource
The datasource is: 
http://data-seattlecitygis.opendata.arcgis.com/datasets/5b5c745e0f1f48e7a53acec63a0022ab_0.csv

## Algoritms
### Overall Result
<p align="center">
<img src="https://github.com/eliuqiong/IBM_Coursera_Capstone/blob/master/Results/Overall%20Result.png" width="60%" height="60%">

### - K nearest neighbors
<p align="center">
<img src="https://github.com/eliuqiong/IBM_Coursera_Capstone/blob/master/Results/k-Nearest%20Neighbor.png" width="60%" height="60%">

### - The Decision Tree Analysis
<p align="center">
<img src="https://github.com/eliuqiong/IBM_Coursera_Capstone/blob/master/Results/Decision%20Tree%20Analysis.png" width="60%" height="60%">

### - Logistic regression
<p align="center">
<img src="https://github.com/eliuqiong/IBM_Coursera_Capstone/blob/master/Results/Logistic%20Regression.png" width="60%" height="60%">

- Support Vector Machine (SVM) 


## Requirements
- Python 3.7.3 or more
```sh
sudo apt-get install Python3.7.3
```

- pip
```
sudo apt-get install python3-pip
```

- Python Virtual Environment
```sh
pip3 install --user virtualenv==16.6.0
```

- Git
```sh
sudo apt-get install git
```

## Running
1. Clone this repository
```sh
clone eliuqiong/IBM_Coursera_Capstone
cd challenge-keyrus
```

2. Choose which environment to running
 - [local](src/environment/README.md)
 - [virtual environment](src/environment/README.md)
 - [container](src/environment/README.md)

3. In terminal running command `jupyter-notebook` and navigate in this repository: `notebooks`

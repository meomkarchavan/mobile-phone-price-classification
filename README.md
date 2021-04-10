# Mobile-Phone-Price-Classification
Price Range Classification of Mobile Phone using Different Machine learning Model

It is an attempt to solve the following ML problem

https://www.kaggle.com/iabhishekofficial/mobile-price-classification

## Problem Description
Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is

## Data Description

The data is dived in 2 groups train.csv and test.csv, i.e `TRAIN DATA` and `TEST DATA`. There are total 20 features provided as listed below.
Training set has 2000 data rows, and test dataset has 1000 data rows.

| Feature name | Feature description | Type |
| ------------ | :-----------------: | ---: |
| battery_power	|Total energy a battery can store in mAh  |	Numeric |
| blue |	Has bluetooth or not	| Boolean |
|clock_speed|	Speed at which microprocessor executes instructions	|Numeric|
|dual_sim|	Has dual sim support or not	|Boolean|
|fc	Front| Camera mega pixels|	Numeric|
|four_g	|Has 4G or not	|Boolean|
|int_memory|	Internal Memory in Gigabytes|	Numeric|
|m_dep|	Mobile Depth in cm|	Numeric|
|mobile_wt|	Weight of mobile phone	|Numeric|
|n_cores|	Number of cores of processor|	Numeric|
|pc|	Primary Camera mega pixels	|Numeric|
|px_height|	Pixel Resolution Height	|Numeric|
|px_width|	Pixel Resolution Width	|Numeric|
|ram	|Random Access Memory in Megabytes	|Numeric|
|sc_h	|Screen Height of mobile in cm	|Numeric|
|sc_w	|Screen Width of mobile in cm	|Numeric|
|talk_time|	Longest time that battery will last by a call	|Numeric|
|three_g|	Has 3G or not	|Boolean|
|touch_screen|	Has touch screen or not	|Boolean|
|wifi|	Has wifi or not	|Numeric|

Following are results from my analysis:

![plot](https://github.com/meomkarchavan/mobile-phone-price-classification/blob/main/results.png)

# Mobile-Price-Range-Predicition
## *Problem Description*
### The rising demand for mobile phones has led to fierce competition in the market.Therefore,it is important to understand the relation  between the characteristics of the mobile phone and it’s selling price .This will help the companies to decide the appropriate price for their product.This project aims to identify the important features which influence the price of the phone and find the best Classification model which predicts the price range of the phone based on it’s characteristics

![devices](https://user-images.githubusercontent.com/65157529/184481188-999f538e-b670-4120-a463-a4822c2bb57e.png)

## *Data Description*
### The data contains 21 columns and 2000 rows. Each row contains the values of various features and specifications of a specific phone and its corresponding price range. The features given in the dataset are:
> * battery_power - Total energy a battery can store in one time measured in mAh
> * blue - Has bluetooth or not
> * clock_speed - speed at which microprocessor executes instructions
> * dual_sim - Has dual sim support or not
> * fc - Front Camera mega pixels
> * four_g - Has 4G or not
> * int_memory - Internal Memory in Gigabytes
> * m_dep - Mobile Depth in cm
> * mobile_wt - Weight of mobile phone
> * n_cores - Number of cores of processor
> * pc - Primary Camera mega pixels
> * px_height - Pixel Resolution Height
> * px_width - Pixel Resolution Width
> * ram - Random Access Memory in Mega Bytes
> * sc_h - Screen Height of mobile in cm
> * sc_w - Screen Width of mobile in cm
> * talk_time - longest time that a single battery charge will last when you are
> * three_g - Has 3G or not
> * touch_screen - Has touch screen or not
> * wifi - Has wifi or not
> * price_range - This is the target variable with values of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

## *Steps Performed*
### 1. EDA
###EDA is  the process of conducting preliminary investigations on data in order to uncover patterns, detect irregularities,and understand the relationship between different features in the data using descriptive statistics and visualization tools. Conclusions from EDA are:
> * Most of the phones currently available in the market  have 3G support
> * Relatively expensive phones have more RAM and higher capacity batteries.
> * Most of the phones do not contain front camera or have low quality front cameras.
> * Most expensive (category 3) phones have better cameras.
> * Relatively expensive phones have more  RAM.
> * Expensive phones have better pixel resolution.
> * Most expensive phones are light-weight and have wider screens as compared to phones belonging to lower price ranges.

### 2. Feature Enginneering
> * Feature scaling is a method used to normalize the range of independent variables or features of data. The scaling of features ensures that the weightage assigned to the features is unaffected by the value range they take. Here,we have used the Min-Max scaling method.
> * Feature selection is the process of selecting a subset of features that are important in predicting the target variable from the entire  set of features in the dataset. We have used SelectKBest  method for selecting 12 most relevant features.

### 3. Model Selection and Hyper parameter Tuning





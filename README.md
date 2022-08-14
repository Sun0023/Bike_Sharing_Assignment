# Bike Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [General Info](#general-information)
  - [Business Understanding](#business-understanding)
  - [Business Objective](#business-objective)
  - [Data Understanding](#data-understanding)
* [Technologies Used](#technologies-used)
* [Solutions Steps](#solution-steps)
* [Recommendations](#recommendations)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

### Business Understanding
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

### Business Objective
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Data Understanding
1. You can observe in the dataset that some of the variables like 'weathersit' and 'season' have values as 1, 2, 3, 4 which have specific labels associated with them (as can be seen in the data dictionary). These numeric values associated with the labels may indicate that there is some order to them - which is actually not the case (Check the data dictionary and think why). So, it is advisable to convert such feature values into categorical string values before proceeding with model building. Please refer the data dictionary to get a better understanding of all the independent variables.
 
1. You might notice the column 'yr' with two values 0 and 1 indicating the years 2018 and 2019 respectively. At the first instinct, you might think it is a good idea to drop this column as it only has two values so it might not be a value-add to the model. But in reality, since these bike-sharing systems are slowly gaining popularity, the demand for these bikes is increasing every year proving that the column 'yr' might be a good variable for prediction. So think twice before dropping it. 

Check out the dictionary to understand further!

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python 3.9.6
- Jupiter Notenook 6.4.12
- SciKit Learn 1.1.1
- Statsmodels 0.13.2


## Solution Steps
Here is the outline of steps of what we do in this notebook.

1. Understanding & Inspecting Data
2. Standardise Data
3. Data Visualization 
4. Data Preparation
5. Split Data into Train and Test
6. Building the MLR Models
7. Residual Analysis
8. Predictions on Test Data Using the Best Model
   - Results
9. Model Evaluation
   - Interpretation 
   - Recommendations


## Recommendations
Here are the recommendations for the BoomBikes to meet their business goals.

- Consider the **temp**. Good temperature means good business for you! Have a weather forecast to handle the demand   for the bike rentals
- Cash in on **Winter**, **Sep**, **Summer**
- **Year** is a plus point. Before the Pandemic, the rentals increase from 2018 to 2019. If there were no Pandemic,   the rentals would have increased in 2020, 2021, and so on. Because the developed countries like U.S. have more   
  bike-friendly policies and people have become more environmental-conscious.

But, here is a catch for you!

- Becareful about these weather negative influences like **windspeed**, **Light_Snow**, **Misty_Cloudy** because  
  they hamper biking. So people won't show much interest in getting a bike.
- **Sun**day is a dampener for the bike rentals. As the U.S. is a Christian country, they spend time on 
  church-going or spending time with the family.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@Sun0023] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

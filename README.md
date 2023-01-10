# Project Name
> Outline a brief description of your project.




<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
## Business Goal:
- It is  required to model the demand for shared bikes with the available independent variables. 
- It will be used by the management to understand how exactly the demands vary with different features. 
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Analysis on the problem

- The coefficient value signifies how much of the dependent variable changes given a one-unit shift in the independent variable while holding other variables in the model constant.

- The month variables 3, 5, 6, 8 ,9, 7 , 10 have positive coefficients. It meams that the demands increases in these months.

- The Yr has also positive coefficient. It means that demand in year 2019 is more than that of 2018.

- We also see there are some variables with negative coefficients. A negative coefficient suggests that as the independent variable increases, the dependent variable tends to decrease.

- We have spring, mist cloudy , light snow variables with negative coefficient.

- Days of the week such as Sunday and Holidays have negative coeffiecients and has low demand
#### Analyst's Final Recommendations on the Entire Analysis
## Selecting out of various Regression Models

- We will go with the model lr21 from the all the developed model as it has better accuracy and the feature set in the final model. The sellected feature sets are also inline from the domain point of view.
- This feature set is inline with expert opinions about the significant fearures that actually impact the Bike Demand.

## The features affecting Bike Demand are the following in the decreasing order of importance

- Year varaiable ( 2018 and 2019) deamd changes
- The month variables 3, 5, 6, 8 ,9, 7 , 10 (number signifies corresponding month of year)
- Harsh Weather Conditions which affects the demand negatively are spring, mist cloudy , light snow
- Holidays affects the demand negatively
- On Sunday Bike denand has negative impact
-
## The final model

cnt= 0.4085 + 0.2469 X yr - 0.1980 X Spring - 0.3212 X Light rain_Light snow_Thunderstorm - 0.0907 X Mist_Cloudy +0.0635 X 3 + 0.1230 X 5 + 0.1483 X 6 +0.1538 X 8 + 0.1937 X 9 + 0.1168 X 10 + 0.1264 X 7-0.0498 X Sunday - 0.0836X holiday
## Recommendations for the company
 - Working days as they have good influence on bike rentals. So it would be great to provide offers to the working individuals
 - Demand is higher in month of 3, 5 , 6, 8, 9 ,7 and 10. So premium pricing may be good strategy in these peak demand months
 - The year 2019 had more demand than year 2018 so a detailed EDA should be performed to explore the influencing factors for these changes.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->





## Contact
Created by SHKADRE - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

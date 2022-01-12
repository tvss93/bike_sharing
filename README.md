# Boom Bikes Demand Prediction

> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- Modelling demand for shared bikes with the available independent variables which will be used by the management to understand how exactly the demands vary with different features.
- Linear Regression combined with RFE is used extensively in this approach

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The final model contains 15 variables
- On test set it has an adjusted r squared of 81.8% and 83.7% on train. This does not indicate any over fitting
- The pvalue of all the fitted variables is less than 0.05, indicating they are all signifcant in predicting the output
- The vif values of all variables is less than 10, indicating there is no multicollinearity

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to Upgrad Team


## Contact
Created by [@tvss93] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
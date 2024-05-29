# Project Name
> Outline a brief description of your project.
BoomBike Case Study - Multiple Linear regression


## Table of Contents
* [General Info](#general-information)
* 
[Technologies Used](#technologies-used)
* 
[Conclusions](#conclusions)
* 
[Acknowledgements](#acknowledgements)


<!-- You can include any other section that is pertinent to your problem -->


## General Information

The main objective of the case study is to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Here, I am trying to build a multiple linear regression model for the prediction of demand for shared bikes.
It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusions
- 
1. The R-squared value of the train set is 84.37% whereas the test set has a value of 80.69% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

2. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

3. The bike demands for the BoomBikes is company is dependent on the **temperature** and whether it is a **workingday** or not. 
4. More rentals seem to be demanded on the **fall** and **summer** as compared to the winter and spring. 
5. The months from **June** to **September** had higher use of rentals.


**Recommendations: **
1. There should be aggressive marketing in the summer and fall season to increase rentals. 

2. A good approach required to introduce more users on days when the weather is less clear, perhaps with exciting deals and offers. Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed to this idea and strong analysis should be done to retain the repeative customers.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Technologies Used


-Programming language - Python

- IDE - Colab/ Jupyter notebook

- libraries
    
	- Numpy
    
	- Pandas
    
	- Matplotlib
    
	- Seaborn
    
	- statsmodels
	- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Acknowledgements

Give credit here.

- This project was based on building predictive analytics model using Multiple linear regression [this tutorial](https://www.learn.upgrade.com).



## Contact
Created by Mayuri Ladi  [@mayuri-techie23] - feel free to contact me!



<!-- Optional -->

<!-- ## License -->

<!-- This project is open source and available under the [... License](). -->


<!-- You don't have to include all sections - just the one's relevant to your project -->
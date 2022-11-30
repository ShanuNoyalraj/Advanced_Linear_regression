# Advanced linear regression Assignment
> 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Numpy, Pandas, Matplotlib, Seaborn
- SKLearn

## Conclusions
- The important variables in determining the price of house are OverallQual_9, Neighborhood_Crawfor, OverallCond_9, Functional_Typ, OverallCond_8,GrLivArea,  OverallQual_8, MSZoning_FV, Exterior1st_BrkFace, Neiighborhood_StoneBr 
  as we will proceed with Ridge regression
- GrLivArea: If above grade (ground) living area increases by one square feet the price will increase by 1.07 times
- Neighborhood_Crawfor : If neighborhood is Crawford, price increases by 1.09 times
- OverallCond : If overall condition is 8 or 9, price increases by 1.08 and 1.09 times respectively
- FunctionalTyp : If house is of typical functionality, price increases by 1.09 times
- OverallQual : If overall quality is 8, price increases by 1.07 times
- Optimal value of alpha for ridge : 7, alpha : 0.001
- R2 square for Ridge model : 0.92, Lasso : 0.91


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [ShanuNoyalraj@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

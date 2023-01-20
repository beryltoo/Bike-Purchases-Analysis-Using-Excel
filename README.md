# Bike-Purchases-Analysis-Using-Excel
## Overview.
The dataset contains 14 columns and 1001 rows. The columns contained in the dataset are :
  -  *ID*:Unique ID for buyer
  -  *Marital Status*:Marital status for buyer
  -  *Income*:Income earned
  -  *Children*:Number of children the buyer has
  -  *Education*:Highest education level of buyer
  -  *Occupation*:Current job role 
  -  *Home Owner*:Whether the buyer owns a home
  -  *No of Cars*: No of Cars Owned
  -  *Commute Distance*:Distance travelled by car
  -  *Region*
  -  *Age*:Age of buyer
  -  *Purchased Bike*:Whether or not they purchased a bike.
## Data Cleaning
 - Marital Status had S and M , which were not descriptive. Used Find and Replace ,to replace S with Single and M with Married
 - Gender had F to decsribe female and M to describe Male,which were also not descriptive.Used Find and Replace to replace F with femal and M with Male
 - Removed decimal places on the income tab ,using the number tab.
 ![reducing numbers on excel](https://user-images.githubusercontent.com/29771961/213467496-5b2414a2-88c5-47ff-9413-97bd231acbf4.png)

- Added age brackets column using IF statemets on the age column, adolescent being less than 31 ,middle age being greater than 31 and old being greater than 54 years.

## Data Analysis.
Created pivot tables of average income by gender and whether they purchased a bike,total commute distance and whether they purchased a bike or not ,age bracket and whether they purchased a bike or not,



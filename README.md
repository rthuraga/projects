## Project: Will a Customer Accept the Coupon?

When driving through town and a coupon is delivered to cell phone of a driver for nearby restaraunt or bar or coffee house. 
Would driver accept that coupon?

## Approach
Used visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Findings
- Original dataset has <B>12684</B> rows and <B>26</B> columns. There were <B>74</B> duplicate rows. Duplicate rows removed
- There are six columns with missing values and more than <B>99%</B> of the 'car' feaure values are missing 
- Dropped the car feature and used mode imputation to fill the missing values for other features

  **Hypothesize about drivers who accpeted the bar coupons:**
  - Total bar coupons offered = <B>2010</B> and Total Bar coupons accepted = <B>824</B> (<B>41%</B>)
  - Customers who go to bar frequently (more than 3 times a month) has highest % of acceptance rate: <B>76.88%</B>
  - Drivers with no kid passenger accepts <b>higher percentage</B> of bar coupons
  - Drivers with low income accepts <B>lower percentage</B> of bar coupons
  
  **Hypothesize about drivers who accpeted Cofee Coupons:**
    - Total Coffee coupons offered = <B>3989</B> and Total Coffee coupons accepted = <B>1989</B> (<B>49.86%</B>)
    - Drivers with friend(s) as passenger accepts <B>higher percentage</B> of coffee coupons.
    - Approximtely same percentage of coffee coupons accepted by gender basis



## Project Notebook
  https://github.com/rthuraga/projects/


## Authors
 Ravinder Thuraga

## Versions
- 0.1
    - Initial Release

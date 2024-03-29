# Height-predicting-model-python
# Description
It determined height of ball using velocity.The program uses liabraries like numpy ,pandas ,matplotlib and sklearn's modules like Linear Regression and PolynomialFeatures.We first made it in matlab and after we implement in python. We made dataset ourselves using formul (1/(2g))(v)^2.
# Getting Sarted
## Dependencies ##
* Windows 11/Mac OS/Linux.
## Installing ##
* Made in jupyter notebook.
## Exexuting program ##
* Download the pyton file and dataset and install the liabraries and good to go.
### Files  ###
The file 'dataset.csv' contains the dataset. It has almost 100 samples. The "height" is calculated by (1/(2g))(v)^2.

![image](https://user-images.githubusercontent.com/84980384/157911518-ae9f5d13-8e0e-40d0-bd09-9cb987889fc3.png)

### Code ###
* Imported dataset.
* Imported liabraries.
* Used .head() to learn about datset using first few lines
Alocated 'y' the "height" column, the 1st column.

![image](https://user-images.githubusercontent.com/84980384/157911805-79c2430b-8162-46f2-9b44-cee8e80d525b.png)

![image](https://user-images.githubusercontent.com/84980384/157911833-99fc9190-488b-4428-bfab-2f4b45e5a7da.png)

* Alocating 'X' the "veclocity" columns of dataset 
* Using numpy to to convert it into numpy array and Reshaping it , so that it can be used later.

![image](https://user-images.githubusercontent.com/84980384/157911891-c53892ad-7190-4028-bfa2-6064fad2591e.png)

* plotting Scatter plot between 'X' and  'y' , keeping alpha=0.4 and s=8 so that we can see overlapping points
* Adding xlabel and  ylabel
* Adding title of plot

![image](https://user-images.githubusercontent.com/84980384/157911921-eb5c422b-a1e8-499d-bef1-e0936d5f783e.png)

* Initializing  Polynomial Feature with degree 2
* It is fiiting and transforming 'X' variable or features simultaneously. 
* Now the Linear Regression is initialized.
* It is fiting the new X.
* It is predicting it as well.

![image](https://user-images.githubusercontent.com/84980384/157911953-a0f507da-75db-4ff8-a1b8-5648213a6511.png)

* Checking the accuracy score.

![image](https://user-images.githubusercontent.com/84980384/157911994-2d8ea0a9-a7ed-4535-bf68-648b8b2daa75.png)

* We are sorting X and y , so that irregular graph is avoided.
* We are plotting the X and y

![image](https://user-images.githubusercontent.com/84980384/157912020-f25d26c2-5988-426f-828a-1a0b9d7c9346.png)

* Comparing the model predicted value and original value.

![image](https://user-images.githubusercontent.com/84980384/157913189-9821aed7-8354-4a16-8b78-73b34f8b40cd.png)


# Authors
1. Ahmed Aleem\
   ahmadaleem13@gmail.com\
   [​LinkedIn​](https://www.linkedin.com/in/ahmad-aleem-45a2251bb/)
2. Mohsin Ali Mirza\
   Mohsinalimirxa@gmail.com\
   [​LinkedIn​](https://www.linkedin.com/in/mohsin-ali-mirza-63878620a/)
 3. ​Waleed Gul<br> 
 ​hwaleed0035@gmail.com<br> 
 ​[​LinkedIn​](https://www.linkedin.com/in/mohsin-ali-mirza-63878620a)

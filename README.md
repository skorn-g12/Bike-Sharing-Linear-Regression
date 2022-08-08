# Bike Sharing Linear Regression Assignment
> This repo houses a Jupyter notebook that tries to solve a bike sharing problem based on the dataset present in day.csv.
> We model it as a linear regression problem and try to get a good prediction on the number of bikes rented in a day. 


## General Information
- A bike company wants to stand out in the market by coming up with a mindful business plan. The objective here is to first find the key features/indicators that capture the demand for bike rentals among the population.
- Once identified, the next goal is to build a model(linear regression) that can accurately the number of bike rentals based on the features in the csv.
- Along the way, EDA is expected and post model building, residual analysis will also be done



## Conclusions
#### $\Rightarrow$ <font color="asparagus">  According to the params above, the major impact on the bumber of bike rentals are coming from the following variables: <br> </font>
- weathersit_3: As predicted from our bivariate analysis, a bad weather really seems to impact the sales. -2581.97 is the coefficient associated with it(i.e. if weathersit_3 is 1, keeping everything 0, the number of sales will drop by -2504.93 units) Therefore, the bike rental company can expect less sales in a such a weather. <br> From the data dictionary, 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds <br>
- yr: The year 2019 has more sales as indicated by the coefficient 2035.43 <br>
- month_9: More weightage is given to September by the linear regression model. Coeff: 1667.7<br>
- month_5: Coeff: 1533.0627
- season_4: According to the linear regression model, season_4 gives more sales. Coeff: 1401.7 <br>
This is followed by some more month variables and then
- temp: Temperature has a good impact on bike rentals too with a coefficient of 819.1 </font>
- 
#### $\Rightarrow$ <font color="asparagus"> On training data, we have the following: </font>
- r2_score: 0.843<br>
- adjusted r2_score: 0.831<br> </font>

#### $\Rightarrow$ <font color="asparagus"> On test data, we have the following:</font>
- r2_score: 0.817<br>
- adjusted r2_score: 0.803<br> </font>

There doesn't seem to be any indication of overfitting as the r2 scores on test and training data are pretty quite close to each other.







## Contact
Created by [@skorn-g12] - feel free to contact me!


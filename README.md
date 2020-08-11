# used_cars_model_improvement
This code is an exercise for a Data Science Online Bootcamp

The idea of the exercise was to improve a used car price predictor model. 
The R squared for the model was 0.744996578792662.
The adjusted R square for it was 0.7435868037811093

So we have to beat those!

This code is based around the adding of the car model variables. 
For that, I used around 250 dummy variables to account for the amout of categorical data.

If you take a close look on the code, I start to build the model from the very beginning, there is some pre processing involved.
I do some data cleaning and OLS assumptions relaxing. There is some non-linearity, for instance, which is relaxed by getting the log of the variables.

After that, I do the regression model. First, I scale the variables and then test/split it for overfitting prevention. 
Once that is done, the equation is created and the model is tested.

During testing, I came up with a R squared of 0.8432293874209928!
Also, the adjusted R squared is: 0.8259480308458563!

So, this shows that the adding of the car models variables are a great sucess!

Also, when we check the difference between the test and the targets (aka 'residuals'), we see less error!
Great win!

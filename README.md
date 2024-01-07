# Machine learning 
#### Hi,in this repository I will be adding what all I have learnt in machine learning 
## Types of Machine Learning
1. Supervised learning 
2. Unsupervised learning

### Supervised Learning
- In this, the machine has to be first trained on the dataset we want to work with and then later tested.
  - Logistic Regression
  - Linear Regression
  - Decision Tree
### Unsupervised Learning
- In this, the machine can make its own paarent and test the dataset in the way it wants to.

##### Linear Regression 
- In this model we use Y=MX+B formula, the machine corelates the two quantifiable data and tries to bring out a linear relationship.
- We need to find the best fit line, fit line- it is error predcted between the actual values and the predicted and is kept minimum.
- Cost Function
  - Error difference between the predicted value and the true value
  - MSE- Mean Squared Error - Purpose is the determine the optimal values for the 
  intercept
  - MSE can be calculated as
    Cost Function= 1/n(Σ)(y^<sub>i</sub>-y<sub>i</sub>)<sup>2</sup>
- Gradient Descent
  - It reduces the cost function and achives the best-fit line model
###### This to keep in mind for Linear regression
- Linearity: The independent variables and the dependent variables have a linear relation with each other.
- Independence: The observation in the dataset are independent of each other.
- Normality: The residuals sould be normally distributed, The residual must follow a bell-shaped curve. If the residual are not normally distributed, then the linear regression will not be an accurate model.
  ######Disadvantages:
  - It assumes that the relation is linear, many a times it needent be that the relation has to be linear, then, the model will not perform properly.
  - It is sensitive to multicollinearity.
  - It is susceptible to overfitting and underfitting.
    - Overfittingp Model learns too well and fails to generalize to unseen data.
    - Underfitting occurs whan the model is to simple to capture the underlying relationships in the  data 
  


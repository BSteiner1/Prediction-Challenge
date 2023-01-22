# ST310-Individual-Project

### :crystal_ball: A Coursework Prediction Challenge 

#### :one: Challenge One: 
Create models and predict the outcome for the Challenge 1 Test csv file using the model with the lowest classification error rate.
#### 🔎 Findings:
More complex methods such as Random Forests and Boosting performed the best (~30% error rate) compared to the more simple methods (~32.5% error rate)

#### :two: Challenge Two: 
Create models and predict the outcome for the Challenge 2 Test csv file with the model that minimises the MSE.
#### 🔎 Findings:
After some tuning, Lasso performed the best by far (MSE ≈ 2.5) compared to other methods (MSE > 25). This is an expected result given the dataset being "high-dimensional" with more predictors (p=435) than observations (n=220). Lasso will set some coefficients to zero and we found that MSE is minimised with only around 50 non-zero coeficients.

## 📌 What is a Good Model?
A good statistical model should satisfy the following two major criteria:

### ✅ 1. Good Explanatory Model  
A model that fits the **training data** well by minimizing the error.

- Goal: Minimize the **training error**
- MSE<sub>(training)</sub> = (1/n)*(Y − Ŷ)²= (1/n) * Σ (yᵢ - ŷᵢ)²
- This ensures the model **explains the current data accurately**.

### ✅ 2. Good Predictive Model  
A model that performs well not only on the training data but also on **test data**.

- Goal: Minimize the **test error**
- This measures the model’s ability to **generalize** to new data.
- Prevents **overfitting** to training data.

#### Bias-Variance Trade off
Let $$\hat{f}(x)$$ be the fitted model.
![Bias-Variance Trade off](https://raw.githubusercontent.com/Chaewon-Park-STUDY/High-Dimension/main/images/1.png)
![Bias-Variance Trade off](https://raw.githubusercontent.com/Chaewon-Park-STUDY/High-Dimension/main/images/2.jpeg)

- In high-dimensional settings (p>>n), models can suffer from **high variance**
  --> lead to unstable predictions and poor generalization.

- To mitigate this, **regularization** is used to reduce variance, even if it introduces some bias.
- As long as the reduction in variance outweighs the increase in bias, the model’s predictive performance improves.
<br>


🎯 Graphical understanding
<br>
![Graphical definition](https://raw.githubusercontent.com/Chaewon-Park-STUDY/High-Dimension/main/images/3.png)

- The red dot represents the true value, while the blue dots represent predictions on test data.
- When predictions are close to the red dot, bias is low. When predictions are tightly clustered together, variance is low.
<br>
![Graphical definition](https://raw.githubusercontent.com/Chaewon-Park-STUDY/High-Dimension/main/images/4.png)





---






* 참고자료:  
-https://www.youtube.com/watch?v=pJCcGK5omhE  
-https://scott.fortmann-roe.com/docs/BiasVariance.html

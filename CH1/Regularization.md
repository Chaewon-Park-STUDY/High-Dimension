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
![Bias-Variance Trade off](https://raw.githubusercontent.com/Chaewon-Park-STUDY/High-Dimension/main/images/1.png)



---






* 출처:
이 글은 https://www.youtube.com/watch?v=pJCcGK5omhE <산업경영공학부 김성범 교수님의 강의영상>을 참고로 작성되었습니다

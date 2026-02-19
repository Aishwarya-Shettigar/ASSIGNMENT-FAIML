# Variance and Bias
## Introduction

In Machine Learning, the goal of a model is to learn patterns from training data and make accurate predictions on unseen data.

However, errors in prediction mainly occur due to two important factors:
  - Bias

  - Variance

Understanding these concepts helps in preventing:
 -  Underfitting

 - Overfitting
The ideal model should balance both bias and variance.

## 2.What is Machine Learning Model Training

Model training is the process of teaching a machine learning algorithm to learn patterns from training data by minimizing prediction error.

Steps in Model Training:

1.Provide training dataset (input features and target output).

2.Model makes predictions.

3.Error is calculated using a loss function.

4.Model parameters are updated.

5.Process repeats until error is minimized.

A properly trained model should generalize well to new data.

## 3.Bias in Machine Learning

Bias is the error caused due to overly simple assumptions in the learning algorithm.

High Bias Characteristics:

- Model is too simple

- Cannot capture complex patterns

- High training error

- High testing error

**High Bias leads to Underfitting**

## 4.Variance in Machine Learning

Variance is the error caused when the model is too sensitive to small changes in the training data.

High Variance Characteristics:

- Model is too complex

- Very low training error

- High testing error

- Captures noise in data

**High Variance leads to Overfitting**

## 5.Underfitting (High Bias, Low Variance)
Underfitting occurs when the model is too simple to learn the true pattern.

<img width="532" height="295" alt="Screenshot 2026-02-19 163753" src="https://github.com/user-attachments/assets/75341e20-ba55-4256-a7a3-b627e329ee22" />

Explanation:

- Model is a simple straight line.

- Fails to capture curved pattern.

- High training error.

- High testing error.

- Model is too simple.

## 6.Overfitting (Low Bias, High Variance)

Overfitting occurs when the model learns noise along with actual data patterns.

<img width="532" height="295" alt="Screenshot 2026-02-19 163805" src="https://github.com/user-attachments/assets/e477996e-46be-422c-8869-414e65827cfb" />

Explanation:

- Model is a complex curve.

- Fits every training point.

- Very low training error.

- High testing error.

- Model is too complex.

## 7.High Bias and High Variance (Worst Case Scenario)

High Bias and High Variance occur when a model is both:

- Too simple to capture the true pattern (High Bias)

- Too unstable or inconsistent across different datasets (High Variance).

This is a rare but possible worst-case situation where the model neither learns properly nor generalizes well.

<img width="743" height="347" alt="image" src="https://github.com/user-attachments/assets/e2222285-b51a-4461-b8f9-d86a4aeff949" />

Explanation

- The model fails to capture the true relationship (like underfitting).

- At the same time, its predictions vary significantly when trained on different data (like overfitting).

- Training error is high.

- Testing error is also high.

- The model is unreliable and unstable.

## 8.Best Fit Model (Low Bias, Low Variance)

The best model captures the true pattern without fitting noise.

<img width="537" height="300" alt="Screenshot 2026-02-19 163827" src="https://github.com/user-attachments/assets/c1fde64e-8640-4af9-8e8a-e83a1bde5ada" />

Explanation:

- Smooth curve follows overall trend.

- Low training error.

- Low testing error.

- Good generalization.

- Balanced bias and variance.

## 9.Bias–Variance Tradeoff

Total prediction error is:

<img width="614" height="56" alt="Screenshot 2026-02-19 170435" src="https://github.com/user-attachments/assets/41cde960-1d53-4824-b5f7-36ec57f98a9b" />

As model complexity increases:

 - Bias decreases

- Variance increases

The optimal model lies at the balance point where total error is minimum.

## 10.Conclusion

**For the best fit model, we must have low bias and low variance**. Low bias ensures that the model correctly captures the true underlying pattern in the data, while low variance ensures that the model performs consistently well on new, unseen data. Therefore, a model with low bias and low variance achieves good generalization and minimizes overall prediction error.

We will testing different Machine Learning models to study their results on different samples collected using different sampling techniques.

# Experimental Results:

## Accuracy Matrix

| Model                 | Simple Random Sampling | Stratified Sampling | Systematic Sampling | Cluster Sampling | Convenience Sampling |
|-----------------------|------------------------|---------------------|---------------------|------------------|----------------------|
| **Random Forest**     | 99.71                 | 99.86              | 99.71              | 99.57           | 99.86               |
| **SVM**               | 66.04                 | 70.22              | 74.24              | 73.96           | 87.91               |
| **Logistic Regression**| 95.54                | 94.82              | 95.83              | 95.54           | 96.12               |
| **Decision Tree**     | 98.99                 | 99.14              | 99.57              | 99.57           | 99.86               |
| **Naive Bayes**       | 96.12                 | 96.55              | 95.54              | 95.40           | 96.83               |



# Final Discussion

## Best Model and Sampling Technique
The best-performing model is **Random Forest**, and the highest accuracy of **99.86%** is achieved using **Stratified Sampling** and **Convenience Sampling**.

## Discussion of Results

1. **Random Forest Model:**
   - It provides the highest accuracy across all sampling techniques, showcasing its robustness and ability to handle complex data relationships.
   - Stratified Sampling ensures balanced class representation, making it an ideal choice for improving the model's generalization.

2. **Sampling Techniques:**
   - **Stratified Sampling:** Offers consistent and high accuracy due to balanced class distribution.
   - **Convenience Sampling:** Delivers strong performance but may introduce bias, limiting generalization.
   - Other techniques like Systematic and Cluster Sampling perform well but not as consistently.

3. **Other Models:**
   - **SVM:** Shows limited accuracy improvement, highlighting its sensitivity to sampling methods.
   - **Logistic Regression and Naive Bayes:** Achieve reliable accuracy but are outperformed by ensemble models.

## Recommendation
For optimal performance and generalizability, use **Random Forest** with **Stratified Sampling**.

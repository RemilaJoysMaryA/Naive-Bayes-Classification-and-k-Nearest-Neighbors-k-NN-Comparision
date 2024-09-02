This project focuses on improving the classification accuracy of rice plant disease detection using dimensionality reduction techniques. The dataset used is the "Rice Plant Diseases" dataset. Two approaches were tested: Principal Component Analysis (PCA) with Naive Bayes and Linear Discriminant Analysis (LDA) with K-Nearest Neighbors (KNN).

Inference
PCA with Naive Bayesian Classification:
●	Before PCA: 61.69% validation accuracy.
●	After PCA: 66.28% validation accuracy.

LDA with K-Nearest Neighbors:
●	Before LDA: 55.82% validation accuracy.
●	After LDA: 94.24% validation accuracy.

Comparison: 
Applying PCA improved the validation accuracy of the Naive Bayesian Classification model by approximately 4.59 percentage points, indicating that PCA helped in enhancing the model's performance slightly by reducing dimensionality and possibly removing noise.
On the other hand, applying LDA significantly boosted the validation accuracy of the K-Nearest Neighbors model by 27.35 percentage points, suggesting that LDA was highly effective in improving classification performance by better capturing the linear separability of the data. This substantial improvement indicates that LDA was more beneficial in this case compared to PCA.
KNN, even before applying LDA, had a higher baseline accuracy compared to Naive Bayesian Classification. After applying LDA, KNN achieved a much higher accuracy, surpassing Naive Bayesian Classification even with PCA.

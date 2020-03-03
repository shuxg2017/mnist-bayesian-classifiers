# Bayesian Classifier (BC)
Three approachs based on NBC to classify handwritten digits (mnist dataset).
<br>
<br>
Gaussian naive BC learns the means and variances from the dataset.
<br>
Gaussian BC Version 2 learns the means and covariance matrix.
<br>
Binomial naive BC learns the frequencies of 1s and 0s.
<br>
For Binomial naive BC, we need to preprocess (binary threshold) the images because the pixel values in digit images are between 0 and 255.
<br>
<br>
Each BC above is trained with training dataset (60k images).
<br>
The table below is the results by using the testing dataset (10k images).

Model	| Parameters | 	Accuracy
------|------------|-----------
Gaussian naive BC | means, variances |	81.7%
Gaussian BC |	means, covariance matrix | 	95.4%
Binomial naiveBC | frequencies of 1s and 0s	| 83.8%

### Learned Parameters (Means)

![Mean of Each Category](/Parameters%20&%20Results/means.png)

### Learned Parameters (Variances)

![Variance of Each Category](/Parameters%20&%20Results/variances.png)

### Learned Parameters (Covariance Matrixes)

![covariance matrix of Each Category](/Parameters%20&%20Results/covariance%20matrix.png)

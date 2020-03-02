# Naive Bayesian Classifier (NBC)
Three approachs based on NBC to classify handwritten digits (mnist dataset).
<br>
<br>
Gaussian NBC Version 1 learns the means and variances from the dataset.
<br>
Gaussian NBC Version 2 learns the means and covariance matrix.
<br>
Binomial NBC learns the frequencies of 1s and 0s. Because the pixel values in digit images are between 0 and 255, so to implement Binomial NBC thresholding images will be the first step.
<br>
<br>
Each NBC above is trained with training dataset (60k images).
<br>
The table below is the results by using the testing dataset (10k images).

Model	| Parameters | 	Accuracy
------|------------|-----------
Gaussian NBC Version 1 | means, variances |	81.7%
Gaussian NBC Version 2 |	means, covariance matrix | 	95.4%
Binomial NBC | frequencies of 1s and 0s	| 83.8%

## Project
In this project, we worked on email-spam dataset. We trained our dataset with naive bayes algorithms. 

## Python Packages Used
* Pandas: For data manipulation and analysis.
* NumPy: For numerical operations.
* Matplotlib: For data visualization.
* Scikit-learn: For machine learning and data mining.

## Code structure
* Load the dataset, specifying the encoding
* Exploratory Data Analysis (EDA) - Pie Chart
* Split Data into Features (X) and Target (y)
* Split Data into Training and Testing Sets
* Vectorization
* Feature Binarization for Bernoulli Naive Bayes
* Train and Evaluate Multinomial Naive Bayes
* Train and Evaluate Gaussian Naive Bayes
* Train and Evaluate Bernoulli Naive Bayes
* Checking the best n bins value for categorical naive bayes (diabetes)

## Results and evaluation 
In this project, we trained our email-spam dataset. We observed the results of our various naive bayes algorithms. 
The accuracy in Multinomial Naive Bayes and Bernoulli Naive Bayes was higher than that in Gaussian Naive Bayes. 

## Comparison of Naive Bayes algorithms
Naive Bayes classifiers assume that features are conditionally independent of each other.
* Multinomial Naive Bayes : It assumes that the features come from a multinomial distribution. This means that each sample is generated from a number of features with a certain probability distribution.Suitable for spam detection, document classification.
* Gaussian Naive Bayes: It assumes that each continuous valued feature for each class has a Gaussian (normal) distribution. use of examples in classification problems with numerical features, image processing (if pixel values are close to normal distribution).
* Bernoulli Naive Bayes : Assumes that properties take binary or boolean values (0 or 1). Example usage: Word presence/absence in text classification, disease presence/absence.
* Categorical Naive Bayes : It assumes categorical distribution of each feature for each class.


# Whitening-vs-Standardising-data

Extracted the useful information from the data and fit a 2D Gaussian on it. 
For better visualisation, Gaussian was plotted as an ellipse superimposing the scatter plot of data points. All this was done on Raw Data.
Next, standardised data and whitened data were used to perform the above task.


### Standardising

Standardising is an important pre-processing step. It is done when input data has large differences in ranges or when they are measured in different units.


After Standardisation, all features will have a mean of 0 and standard deviation as 1.
It is performed before PCA, SVM, KNN, Lasso and RIdge Regression.

![WhatsApp Image 2021-04-18 at 11 59 01 PM](https://user-images.githubusercontent.com/62426111/115157225-bc0dc880-a0a5-11eb-8900-18dcb3e491ba.jpeg)

### Whitening

Whitening transforms a vector of random variables into a new set of variables whose covariance matrix is Indentity Matrix. Whitening is done to make the input data less redundant, as it removes dependancy in data. The Data becomes uncorelated and of equal variance in all directions. Whitening is therefore also called sphering.

![WhatsApp Image 2021-04-19 at 12 20 10 AM](https://user-images.githubusercontent.com/62426111/115157222-b6b07e00-a0a5-11eb-8f8a-95d5368dbdfd.jpeg)

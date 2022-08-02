# Support-Vector-Machine

### When To Use

SVM is a supervised machine learning algorithm which can be used for classification or regression problems. It uses a technique called the kernel trick to transform your data and then based on these transformations it finds an optimal boundary between the possible outputs.

It can handle both classification and regression on linear and non-linear data.


### Kernel functions
#### Linear
These are commonly recommended for text classification because most of these types of classification problems are linearly separable.

#### Gaussian Radial Basis Function (RBF)
One of the most powerful and commonly used kernels in SVMs. Usually the choice for non-linear data.

### Pros
1. Effective on datasets with multiple features, like financial or medical data.
2. Effective in cases where number of features is greater than the number of data points.
3. Different kernel functions can be specified for the decision function. You can use common kernels, but it's also possible to specify custom kernels.
4. It is effective in high dimensional spaces.



### Cons
1. It doesn’t perform well when we have large data set because the required training time is higher
2. It also doesn’t perform very well, when the data set has more noise i.e. target classes are overlapping
3. SVM doesn’t directly provide probability estimates, these are calculated using an expensive five-fold cross-validation. It is included in the related SVC method of Python scikit-learn library.

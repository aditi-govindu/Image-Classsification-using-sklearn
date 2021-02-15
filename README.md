# Image Classsification using sklearn
Using Machine learning algorithms to classify images under 3 categories

# sklearn
sklearn or scikit learn is a library in Python with efficient tools for machine learning and statistical modelling.
This project uses the **SVM** or Support Vector machine module under sklearn library to classify images under 1 of 3 categories

# Support Vector Machine (SVM)
SVMs are supervised machine learning algorithms that are used for 2 group classifications (They can be used for more than 2 classes, by changing the kernel parameters). Data is classified when an optimal hyperplane is drawn, maximum distance away from the data points. All data points with minimum distance to the hyperplane are called *Support Vectors*. 
In this code, we have 3 classes to classify:
```
Pizza
Burger
Momos
```
## Kernel
The popular kernels in sklearn are: *linear, polynomial, radial basis function(rbf) and sigmoid*. Kernel is used to map the distance between 2 points of the dataset. A score is assigned to the distance, where closer the points, higher the score. This score can be used for mapping points to more dimensions (kernel trick). RBF kernel is used in this code, as it gives good classification report results (compared to others). Best parameters are evaluated using **GridSearchCV()** function in sklearn.

# Libraries used
Refer to **requirements.txt** to see which files and versions are necessary to run this code

# References
https://scikit-learn.org/stable/modules/svm.html
https://towardsdatascience.com/multiclass-classification-with-support-vector-machines-svm-kernel-trick-kernel-functions-f9d5377d6f02
https://www.youtube.com/watch?v=dw96S_iFFbI&t=7346s

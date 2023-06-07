# PCA
Principle Component Analysis (PCA):

PCA is a technique or algorithm for dimensionality reduction. It means PCA is a tool to reduce multidimensional data to lower dimensions while retaining most of the data. For example, we can use PCA to reduce 7-dimensional data to 3-dimensional data and still this 3-dimensional data will have same contribution to the machine learning model as 7-dimensional data did.



When we take 7-dimensional data, it is represented using 7 axes. This type of representation and visualization of data will be very difficult, we human live in 3-dimnesional 3D space and hence visualizing the objects in 3D and lower dimensions (1D,2D) become easy for us. This is the reason for reducing the dimensions it will also make better visualization.



Advantages of PCA:

1.     The speed of the machine learning model will improve. The reason is that the no. of columns handled by the model will reduce.

2.     Data redundancy can be reduced. Data redundancy is at term related to duplicate data. In PCA, the same data points are overwritten and hence duplicates can be eliminated.

3.     Visualizing the data will become easy due to reduce in the dimensions. That means it is possible to plot the data easily.

4.     In case of images, videos, audios files, PCA ignores small variations in the background. Only the variations around the peak are considered. Hence noise in the images, audios and videos are reduced. 



Steps for PCA Algorithm

1. Standardize the data: PCA requires standardized data, so the first step is to standardize the data to ensure that all variables have a mean of 0 and a standard deviation of 1.



2. Calculate the covariance matrix: The next step is to calculate the covariance matrix of the standardized data. This matrix shows how each variable is related to every other variable in the dataset.



3. Calculate the eigenvectors and eigenvalues: The eigenvectors and eigenvalues of the covariance matrix are then calculated. The eigenvectors represent the directions in which the data varies the most, while the eigenvalues represent the amount of variation along each eigenvector.



4. Choose the principal components: The principal components are the eigenvectors with the highest eigenvalues. These components represent the directions in which the data varies the most and are used to transform the original data into a lower-dimensional space.



5.Transform the data: The final step is to transform the original data into the lower-dimensional space defined by the principal components. 

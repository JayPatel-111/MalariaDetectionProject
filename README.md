<h1>Project: Malaria Detection</h1>



<h2>Description</h2>
The code performs image classification on a dataset of healthy and malaria-infected cells using two different methods: pixel values and Histogram of Oriented Gradient (HOG) features.

In the first method, the code resizes the images to a fixed size of 40x40 pixels and converts them into one-dimensional feature vectors by flattening the pixel values. These pixel-based features are then used to train Logistic Regression and Linear SVM models. The accuracy of the models is evaluated on both the training and validation sets.

In the second method, the code resizes the images to a standardized size of 128x64 pixels and extracts HOG features. HOG features capture information about the distribution of gradients and edges in an image. These features are then used to train Logistic Regression and Linear SVM models. The accuracy of these models is also evaluated on the training and validation sets.

The results obtained from the two methods show that the models built using HOG features outperform the models built using pixel values as features. The Logistic Regression model using HOG features achieves a training accuracy of 89.84% and a validation accuracy of 82.19%. The Linear SVM model using HOG features achieves a training accuracy of 92.69% and a validation accuracy of 81.00%.

Overall, the code demonstrates the process of feature extraction and model training for image classification tasks using different feature representations. It highlights the advantages of using HOG features for better accuracy in this specific classification problem.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Libraries: OS, numpy, pandas, matplotlib, sklearn, </b>

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>


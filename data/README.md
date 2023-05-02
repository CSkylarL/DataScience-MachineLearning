
# Data

This folder encompasses various datasets employed throughout this repository. Each dataset is stored in either `.csv` or `.npy` formats. Alongside the datasets, a Jupyter notebook is included which provides comprehensive details about the background, creation process, and distinct characteristics of the corresponding data. 

The dataset is as follows:

- [Iris](./iris/): The Iris dataset is a classic dataset for classification, machine learning, and data visualization, consisting of measurements of four features (sepal length, sepal width, petal length, petal width) of three types of iris flowers (Setosa, Versicolour, and Virginica).
- [Wine](./wine/): The Wine dataset is a classic multi-class classification dataset that consists of 13 features that are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars.
- [Digits](./digits/): The Digits dataset is made up of 1,797 8x8 images of hand-written digits, useful for teaching image classification techniques.
- [Fashion MNIST](./fashion_mnist/): Fashion MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples, each example is a 28x28 grayscale image, associated with a label from 10 classes.
- [Breast Cancer](./breast_cancer/): The Breast Cancer Wisconsin (Diagnostic) dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, useful for binary classification problems.
- [Lung Cancer](./lung_cancer/): The Lung Cancer dataset consists of immune marker gene expressions of 58 patients having Lung Adenocarcinoma (LUAD). Each patient has paired normal and primary tumors. I generated this dataset from the original dataset available at [Broad Institute's Genome Data Analysis Center (GDAC)  Firehose](https://gdac.broadinstitute.org/). This dataset is useful for binary classification, feature selection, and dimensionality reduction tasks.
- [Stroke](./stroke/): The Stroke dataset contains comprehensive clinical data of patients and their stroke status, used to predict the likelihood of a patient having a stroke based on input parameters like gender, age, various diseases, and smoking status.
- [California Housing](./california_housing/): The California Housing dataset serves regression tasks, it comprises of the census data of California housing, containing features like population, median income, median housing price, etc. for blocks group in California.
- [Make Moon, Blob and Circle](./make_moon_blob_circle.ipynb): This notebook focuses on generating artificial datasets for binary classification or clustering tasks using the sklearn.datasets module. The generated datasets can be used to visualize and gain insights into the performance of different algorithms.
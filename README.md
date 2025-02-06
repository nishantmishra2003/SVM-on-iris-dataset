# SVM-on-iris-dataset

📌 Overview
This project implements a Support Vector Machine (SVM) model to classify the Iris dataset into different species based on sepal and petal features.

📊 Dataset
The Iris dataset consists of 150 samples with four features:

>Sepal Length
>Sepal Width
>Petal Length
>Petal Width

There are three target classes:

>Setosa
>Versicolor
>Virginica

🛠️ Technologies Used
>Python
>Scikit-learn
>NumPy
>Pandas
>Matplotlib (for visualization)

🏗️ Implementation Steps
>Load the dataset using sklearn.datasets.load_iris().
>Preprocess the data by splitting it into training and testing sets.
>Train an SVM classifier using the SVC class from sklearn.svm.
>Tune hyperparameters (kernel type, C value, gamma).
>Evaluate the model using accuracy, confusion matrix, and classification report.
>Visualize the decision boundaries.

📈 Results
>Achieved high classification accuracy.
>Explored different SVM kernels (linear, polynomial, RBF).
>Plotted decision boundaries to understand model performance.

🏆 Key Learnings
>SVM works well for small datasets with clear decision boundaries.
>Proper kernel selection and hyperparameter tuning significantly impact performance.

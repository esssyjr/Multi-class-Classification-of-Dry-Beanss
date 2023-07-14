# Multi-class-Classification-of-Dry-Beanss
Multi-class-Classification-of-Dry-Beans
This project demonstrates the classification of the Dry Bean Dataset using a deep learning model implemented in TensorFlow and Keras. The Dry Bean Dataset contains various features of different types of dry beans, and the goal is to predict the class of a given dry bean sample.

Dataset
The dataset used in this project is the "Dry_Bean_Dataset.xlsx" file, which contains the following columns:

Bean ID
Area
Perimeter
MajorAxisLength
MinorAxisLength
AspectRation
Eccentricity
ConvexArea
EquivDiameter
Extent
Solidity
roundness
Compactness
ShapeFactor1
ShapeFactor2
ShapeFactor3
ShapeFactor4
Class
Running the Code
Clone the repository or download the code files.
Place the "Dry_Bean_Dataset.xlsx" file in the same directory as the code files.
Open a terminal or command prompt and navigate to the directory containing the code files.
Run the following command to execute the code:
python code_file.py
The code will load the dataset, preprocess the data, train the model, and display the training progress and evaluation metrics.
After training, the code will make predictions on a test set and compare them with the true labels.
Understanding the Code
The code starts by importing the necessary libraries, including pandas, matplotlib, numpy, scikit-learn, TensorFlow, and Keras.
It reads the dataset from the "Dry_Bean_Dataset.xlsx" file using the pandas library.
The data is preprocessed by standardizing the features using the StandardScaler and encoding the class labels using LabelEncoder.
The dataset is split into training and testing sets using train_test_split from scikit-learn.
A deep learning model is created using the Sequential API from Keras, with multiple dense layers.
The model is compiled with an optimizer, loss function, and evaluation metric.
The model is trained using the training set and evaluated on the testing set.
Finally, the model makes predictions on a subset of the testing set, and the predicted and true labels are compared.
Feel free to explore and modify the code to suit your needs. Data Source: The Dry Bean Dataset used in this project is sourced from the UCI Machine Learning Repository, contributed by Dr. İlker Çam and Dr. Kemal Polat. Please refer to the following publication when citing the dataset: KOKLU, M. and OZKAN, I.A., (2020), “Multiclass Classification of Dry Beans Using Computer Vision and Machine Learning Techniques.” Computers and Electronics in Agriculture, 174, 105507.

DOI: https://doi.org/10.1016/j.compag.2020.105507

# Objective
To apply CNN model for image classification.

# Dataset
The dataset is available on kaggle - "A-Z Handwritten Alphabets in .csv format".
Link to the website - https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format

## Description of the dataset
The dataset contains 26 folders (A-Z) containing handwritten images in size 2828 pixels, each alphabet in the image is centre fitted to 2020 pixel box.
Each image is stored as Gray-level.
Kernel CSVToImages contains script to convert .CSV file to actual images in .png format in structured folder.

# Approach
* To create a CNN to classify the given image as an English alphabet. 
* To convert the given data form to a matrix form to visulaise it.

# Accuracy score of the CNN Model
Accuracy : 0.9938

# Conclusion
The trained CNN model can be used to recognise a handwritten English alphabet with high accuracy. The data given had 784 columns (excluding the label column). Hence, the images were 28 x 28, whose matrix was flattened to give the csv file. 

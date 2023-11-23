# Module-13-Challenge
In this repository you will find a .ipynb file named Venture_Fund_Deep_Learning, in this file we assume the role of a risk management associate at Alphabet Soup, a fictitious venture capital firm. The Alphabet Soup business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will become successful if funded by Alphabet Soup.
# Part 1 Prepare the Data for Use on a Neural Network Model
We will read the applicants_data.csv file into a Pandas DataFrame. Review the DataFrame, checking for categorical variables that will need to be encoded and for columns that might eventually define our features and target variables.
We will then drop the “EIN” (Employer Identification Number) and “NAME” columns from the DataFrame, because they’re irrelevant for the binary classification model.
We will then  encode the categorical variables of the dataset by using OneHotEncoder, and then place the encoded variables in a new DataFrame.
We will then add the numerical variables of the original DataFrame to the DataFrame that contains the encoded variables.
Using the preprocessed data, create the features (X) and target (y) datasets. The “IS_SUCCESSFUL” column in the preprocessed DataFrame should define the target dataset. The remaining columns should define the features dataset.
Then Split the features and target datasets into training and testing datasets.
Use StandardScaler from scikit-learn to scale the features data.

# Part 2 Compile and Evaluate a Binary Classification Model Using a Neural Network
We will use Tensorflow’s Keras to create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer.
Then we will save and export our model to an HDF5 file, and name the file AlphabetSoup.h5.

# Part 3 Optimize the Neural Network Model
Using my knowledge of TensorFlow and Keras, I will optimise my model to improve its accuracy. 
I will then use at least three new deep neural network models (that is, the original plus two optimisation attempts). 
For each, try to improve my first model’s predictive accuracy.
I will then display the accuracy scores that each model achieved, and then compare the results.
I will lastly save each model as an HDF5 file.

# End of Module 13

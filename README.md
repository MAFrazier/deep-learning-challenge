# Deep Learning 

## View [Analysis Report](Analysis_Report.pdf) for Summary 

### The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

### From Alphabet Soup’s business team, [Charity Data.csv]("https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv") was recieved containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

    EIN and NAME—Identification columns
    APPLICATION_TYPE—Alphabet Soup application type
    AFFILIATION—Affiliated sector of industry
    CLASSIFICATION—Government organization classification
    USE_CASE—Use case for funding
    ORGANIZATION—Organization type
    STATUS—Active status
    INCOME_AMT—Income classification
    SPECIAL_CONSIDERATIONS—Special considerations for application
    ASK_AMT—Funding amount requested
    IS_SUCCESSFUL—Was the money used effectively

### Instructions

#### Step 1: Preprocess the Data

#### Step 2: Compile, Train, and Evaluate the Model
##### Using your knowledge of TensorFlow, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset. You’ll need to think about how many inputs there are before determining the number of neurons and layers in your model. Once you’ve completed that step, you’ll compile, train, and evaluate your binary classification model to calculate the model’s loss and accuracy.

#### Step 3: Optimize the Model
##### Using your knowledge of TensorFlow, optimize your model to achieve a target predictive accuracy higher than 75%.
##### Use any or all of the following methods to optimize your model:

    Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
    Dropping more or fewer columns.
    Creating more bins for rare occurrences in columns.
    Increasing or decreasing the number of values for each bin.
    Add more neurons to a hidden layer.
    Add more hidden layers.
    Use different activation functions for the hidden layers.
    Add or reduce the number of epochs to the training regimen.
    
### Note: If you make at least three attempts at optimizing your model, you will not lose points if your model does not achieve target performance.
##### Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity_Optimization.h5

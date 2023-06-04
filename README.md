# kaggle_competitions
## Crab Age Data Prediction

This project focuses on data cleaning and model training using the provided `train.csv` and `test.csv` files. The following steps were undertaken:

1. Null values and column data types: Initially, the dataset was examined to identify any null values and assess the data types of each column.

2. One-hot encoding: As the "Sex" column contained text values, it was necessary to convert it into numerical form. One-hot encoding was employed for this purpose.

3. Visual representation: After performing data cleaning, some visual representations were created to explore the relationship between different features.

4. Model training and testing: The cleaned data was used to train the model, utilizing the `train.csv` file. Subsequently, the trained model was tested on the `test.csv` file to assess its performance.

5. Model fitting: The model was imported from the `sklearn` library and fitted with the cleaned and preprocessed data.

6.Model Testing : The model was then tested usinng the `test.csv` file and the results are stored in csv file named `submission.csv` . 

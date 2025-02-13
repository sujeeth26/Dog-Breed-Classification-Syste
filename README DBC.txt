# DOG BREED CLASSIFICATION

The Dog Breed Classification project aims to develop a machine learning
model capable of classifying dog images into different breeds by
leveraging the abilities of Big data tools like Pyspark and MongoDB.
This project utilizes deep learning techniques, specifically
Convolutional Neural Networks (CNNs), to achieve accurate breed
classification.

## System Requirements:

Pyspark Environment (we used Google Colab Pro Plus subscription for
execution to ensure sufficient memory and processing power). Internet
connection to access MongoDB and download data from Kaggle)

## Set up MongoDB

Ensure that MongoDB is accessible as per the connection string provided
in the code. Modify the connection details if necessary.

## Install Required Libraries

-   Pymongo
-   Pyspark
-   Pillow
-   Pandas
-   Tensorflow
-   matplotlib
-   opencv

## Download Data

Use Kaggle API to download the necessary dog breed photos dataset.
Ensure you have the Kaggle API key configured.

## Usage

1.  **Data Collection**: Connect to MongoDB, retrieve data, and save it
    as a CSV file. Additionally, download and unzip the dataset from
    Kaggle.
2.  **Data Cleaning and Preprocessing**:
    -   Convert the data into a Spark DataFrame.
    -   Filter images based on size and aspect ratio.
    -   Convert images to grayscale and resize them.
3.  **Model Development**:
    -   Train a CNN model .
    -   Split the data into training, validation, and test sets.
    -   Perform model training and save the trained model.
4.  **Visualization and Results**:
    -   Generate predictions using the trained model.
    -   Display images with predicted and actual labels.
    -   Plot learning curves, histograms of predicted probabilities, and
        a confusion matrix.

## Running the Project

1.  Open the project in Pyspark Environment.
2.  Install All dependencies including Datasets
3.  Run each cell in the provided notebook sequentially to perform data
    collection, preprocessing, model training, and evaluation.

## Contributing

Contributions to the project are welcome. Please fork the repository,
make changes, and submit a pull request.

## Credits

Data provided by MongoDB and Kaggle dataset by Enashed.

## License

Include information about the project's license here, specifying how it
can be used by others.

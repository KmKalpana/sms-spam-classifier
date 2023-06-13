# Spam SMS Detection

This is a machine learning project aimed at detecting spam SMS messages. The project utilizes the Scikit-learn library and is implemented in Python.
## Project Overview

The goal of this project is to build a classification model that can accurately distinguish between spam and ham (non-spam) SMS messages. By utilizing machine learning algorithms and natural language processing techniques, the project aims to identify patterns and features in the text data to make accurate predictions.

## Project Details

The project involved the following key steps:

1. **Data Cleaning**: Duplicates, null values, and irrelevant columns were removed from the dataset. This step ensures the quality and integrity of the data.

2. **Exploratory Data Analysis (EDA)**: EDA was performed to gain insights into the dataset and understand its characteristics. Visualizations using libraries such as Pandas, NumPy, Matplotlib, Collection, and Seaborn were utilized to explore the distribution of spam and ham messages.

3. **Text Preprocessing**: The text data underwent preprocessing to convert it into a suitable numerical format for machine learning algorithms. This involved tokenization, stemming, and removing stop words. These steps transform the raw text data into feature vectors that can be used as input for classification algorithms.

4. **Classification Model Selection**: Various classification algorithms, including Naive Bayes, Logistic Regression, K-Nearest Neighbors, etc., were implemented to build and train the models. Evaluation metrics such as accuracy, precision, and confusion matrix were used to assess the performance of each model. The best-performing model was selected based on these metrics.

## Dependencies

To run this project, the following dependencies are required:

- Python (version 3.0 or higher)
- Scikit-learn (version 0.24.0 or higher)
- Pandas (version 1.2.0 or higher)
- NumPy (version 1.19.5 or higher)
- Matplotlib (version 3.3.4 or higher)
- Collection (version 0.6.0 or higher)
- Seaborn (version 0.11.1 or higher)

You can install the dependencies using `pip`:

```bash
pip install scikit-learn pandas numpy matplotlib collections seaborn
```

## Usage

To run the project, follow these steps:

1. Clone the project repository from GitHub:

```bash
git clone https://github.com/KmKalpana/sms-spam-classifier.git
```

2. Change into the project directory:

```bash
cd spam-sms-detection
```

3. Run the main script:

```bash
python main.py
```

The script will perform data cleaning, exploratory data analysis, text preprocessing, and build the classification model. The results will be displayed in the console and any visualizations will be saved in the output directory.

## Conclusion

The Spam SMS Detection project showcases the application of machine learning algorithms and natural language processing techniques to classify SMS messages as spam or ham. By following the steps outlined in this project, you can replicate the process, experiment with different algorithms, and potentially improve the accuracy of the classification model.

# Data-Cleaning


# Objective
The goal of this task was to clean and prepare a raw dataset using Python (Pandas) for further analysis or modeling.The cleaned dataset is intended to be used for further analysis, visualization, or machine learning tasks.

# Tools & Technologies Used
Python Language
Pandas – for data manipulation and cleaning
Google Colab – for writing and executing the code
CSV File – Netflix Movies and TV Shows dataset

# Dataset Overview
The original dataset contains information about movies and TV shows available on Netflix, such as:
Show ID, Title, Director, Cast
Country, Date Added, Release Year
Rating, Duration, Genre



# Steps Performed
Data Loading-
Loaded the dataset using pandas.read_csv().

Initial Inspection-
Checked data structure using .info().
Identified missing values using .isnull().sum().

Missing Value Handling-
Filled missing values in columns like director, cast, and country with default values like 'Unknown' or 'Not Specified'.
Dropped rows where important values like date_added or rating were missing.

Duplicate Removal-
Removed duplicate records using .drop_duplicates().

Text Standardization-
Standardized text in columns like country and rating by converting to lowercase or uppercase and stripping spaces.

Date Conversion-
Converted the date_added column to datetime format using pd.to_datetime().

Column Renaming-
Renamed all column headers to lowercase and replaced spaces with underscores for uniformity.

Data Saving-
Exported the cleaned dataset to a new CSV file named cleaned_netflix_dataset.csv.



This project helped me understand practical data cleaning techniques using Pandas, such as:
Identifying and fixing missing data
Dealing with inconsistencies in text data
Date parsing and formatting
Structuring datasets for analysis





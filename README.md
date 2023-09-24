# Datagrokr_Assignment

## Data Analysis and API Development Assessment

This repository contains the code and documentation for a data analysis and API development assessment. The assessment consists of three main sections:

## Section 1: Environment Setup and Data Cleaning
In this section, we set up the environment using Google Colab, read a dataset from a CSV file, and perform data cleaning operations. The cleaning steps include removing unnecessary columns, discarding rows with null values in specific fields, and separating the data into two tables: Property_Details and Property_Price_Details. The cleaned data is then loaded into a local SQL database using SQLAlchemy and SQLite.

**Deliverables:**
- Jupyter Notebook with data cleaning commands and cleaned dataframes.
- Code to connect to the local SQL database.

## Section 2: Data Analysis
This section involves querying the cleaned local database to retrieve specific insights and answers to various questions about the dataset. The analysis includes tasks such as identifying high-priced properties, categorizing properties by surface area, finding properties with the same number of bedrooms and bathrooms, calculating average price per square meter, and more.

**Deliverables:**
- Jupyter Notebook with SQL queries for data analysis tasks.

## Section 3: Expose the Results in API
In this section, we set up a Flask server to create a REST API. The Flask server provides API endpoints for each of the data analysis tasks from Section 2. The API responds to GET requests with the results of the corresponding analysis queries. Error handling is implemented to handle invalid requests.

**Deliverables:**
- Flask server code in a Jupyter Notebook.
- API endpoints for each data analysis question.
- Basic error handling for invalid requests.

## Bonus:
As a bonus, you can deploy the Flask API using ngrok to create a publicly accessible URL for testing and sharing the API with others.

**Deliverables (Bonus):**
- Ngrok setup for the Flask API.

## Dataset
The dataset used for this assessment can be downloaded from the following link: [Dataset Link](https://drive.google.com/file/d/1R1whj-7C5h9_rYoup_YrAuwwuvfBhWTn/view?usp=drive_link).

To use the dataset in the assessment, download it and place it in the same directory as the Jupyter Notebook files.

## Usage
1. Start with Section 1 to clean the data and set up the local database.
2. Proceed to Section 2 to perform data analysis and run SQL queries.
3. Move on to Section 3 to set up and run the Flask API to expose the analysis results.

Ensure that you follow the instructions in each section and use the provided dataset for the assessment.

Feel free to explore the code and documentation in this repository for a detailed understanding of the assessment process and results.

**Note:** This assessment was completed successfully as per the provided instructions and requirements.

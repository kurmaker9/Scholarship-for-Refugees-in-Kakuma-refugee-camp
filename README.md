# Scholarship-for-Refugees-in-Kakuma-refugee-camp
Scholarship Data Analysis Project

Project Description
This project involves analyzing and cleaning a dataset of scholarship applicants using Microsoft Excel and R. The dataset includes information on personal details, education, employment status, and financial situations of applicants. The goal is to prepare the data for analysis, extract insights, and generate visualizations.

Dataset Information

The dataset is stored in an Excel file named Scholarship_Data Cleaning.xlsx with the following key features:

Sheet Name: Sheet1

Columns:

Your Name in Full: Full name of the applicant.

Your Gender: Gender of the applicant.


Your Email Address: Contact email of the applicant.

Your Individual Number/ID Number: ID number of the applicant.

What is Your Nationality?: Nationality of the applicant.

What is Your Marital Status?: Marital status.

Where Are You Currently Located?: Current location.

What is Your Preferred Language of Communication?: Preferred communication language.

What is Your Level of Education?: Highest level of education completed.

What Was the Year of Completion?: Year of completing the highest education level.

What is Your Final Grade?: Grade attained in school or university.

And other columns related to vocational studies, employment, and financial status.

Tools Used

Microsoft Excel: For initial dataset review and simple data manipulations.

R Programming Language:

Libraries:

readxl: To load the Excel file into R.

dplyr: To manipulate and filter the dataset.

ggplot2: To create visualizations and insights.

Steps in the Project

1. Data Preparation in R
The dataset is loaded into R using the readxl library.
Missing values are identified and handled.
Column names are standardized for easier reference.
2. Data Cleaning
Empty or blank fields are replaced with NA values.
Columns are reformatted as necessary (e.g., numeric conversions for grades or years).
3. Analysis and Visualization
Summary Statistics:
Gender distribution.
Education levels and their relationship with other factors.
Filtering:
Extracting employed individuals or those with specific financial statuses.
Visualizations:
Bar plots for gender distribution and education levels by gender.
4. Output
A cleaned version of the dataset is saved as a CSV file named cleaned_scholarship_data.csv.

Instructions for Running the R Script

Prerequisites:

Ensure you have R installed on your machine.

Install the required R packages using the following commands:

R

Copy code

install.packages("readxl")

install.packages("dplyr")

install.packages("ggplot2")

Running the Script:


Save the R script as scholarship_analysis.R.

Place the Excel file (Scholarship_Data Cleaning.xlsx) in the same directory as the R script.

Run the script in RStudio or your preferred R environment.

Expected Outputs:

Summary statistics printed in the console.

Visualizations saved as plots in the RStudio viewer or exported manually.

A cleaned dataset file: cleaned_scholarship_data.csv.

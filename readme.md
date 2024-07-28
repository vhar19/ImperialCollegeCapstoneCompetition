# Capstone Competition

## Quick start

Visit the github repo at: https://github.com/vhar19/ImperialCollegeCapstoneCompetition for the latest version of this code

1. Open function_w10.ipynb
2. Ensure variables are set with values `file=1` and `resultsFile = "data/results10.csv"` at the beginning of the script
3. Run the notebook

## Overview

Folder structure: This project was integrated at a later stage to git, therefore the intial version control was done one file per week and the versions with changes in this project are: function_w7, function_w8, function_w9 and finally function_w10

## Inputs

Each week results are copied to a new CSV file in the `data` folder with the week number in the name, e.g. reaults06.csv are the results of week 6

All data used for the model is the latest results combined with the folder `initial_data` which has the initial values used for the first submission

## Outputs

Each week submissions were updated in the `answers.txt` file

## To run the latest code with latest data:

Open the latest code file .ipnyb and update `resultsfile` and `file` variables:

- Check resultsfile is pointing to latest data
- Set file to the respective function to run, values are 1 to 8

## Usage

In addition to late integration with github the files were designed to work as cross-reference in mind, meaning a data file from week 5 can run against a code file from week 6, etc. Usually code of week7 runs against data of week7, and so on.

Some usage examples:

- functionw8.ipynb (old code) and functionw9.ipynb (new code) can both reference results09.csv (new data) to check how both code files compare with the new data file.

- functionw9.ipynb (new code) can point to results08.csv (old data) to check how the new algorithm compares with results generated from last week

**In order to add new results every week:**

1. Copy results to data folder with a new version number, e.g. results09.csv
2. Copy the ipnyb file and assign a new name with matching number, e.g. function_w9.ipnyb
3. Update variables as described above

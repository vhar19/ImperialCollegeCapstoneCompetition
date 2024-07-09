# Capstone Competition

## Inputs

Each week results are copied to a new CSV file in the `data` folder with the week number in the name, e.g. reaults06.csv are the results of week 6

All data used for the model is the latest results combined with the folder `initial_data` which has the initial values used for the first submission

## Outputs

Each week submissions are updated in the answers.txt file

## To run the latest code with latest data:

Open the latest code file .ipnyb and update `resultsfile` and `file` variables:

- Check resultsfile is pointing to latest data
- Set file to the respective function to run, values are 1 to 8

## Usage

The folder structrue was designed to give the flexibility to run predictions from code in current and previous weeks against results from previous and new data. Like a mix-and-match approach.

Each week a new results file is added with a consecutive number, a matching .ipnyb file is generated and the parameters are updated to point to the new data file. In the same approach any code file can point to different old or new data to evaluate and compare results.

Some usage examples:

- functionw8.ipynb (old code) and functionw9.ipynb (new code) can both reference results09.csv (new data) to check how both code files compare with the new data file.

- functionw9.ipynb (new code) can point to results08.csv (old data) to check how the new algorithm compares with results generated from last week

**In order to add new results every week:**

1. Copy results to data folder with a new version number, e.g. results09.csv
2. Copy the ipnyb file and assign a new name with matching number, e.g. function_w9.ipnyb
3. Update variables as described above

# Capstone Competition

## Inputs

Each week results are copied to a new CSV file in the `data` folder with the week number in the name, e.g. reaults06.csv are the results of week 6

All data used for the model is the latest results combined with the folder `initial_data` which has the initial values used for the first submission

## Outputs

Each week submissions are updated in the answers.txt file

## Usage

The folder structrue was designed to be able to run predictions from previous weeks just by referencing the previous results file and the previous ipynb file with matching consecutive number. In the same way a previous file can reference a higher number to compare results using the previous and new code, some examples:

- functionw8.ipynb and functionw9.ipynb can both reference results09.csv to check the results obtained by old and new algorithms with latest data
- functionw9.ipynb can point to results08.csv to check how the new algorithm compares with results obtained from last week

To provide new results:

1. Copy results to data folder with a new version number, e.g. results09.csv
2. Copy the ipnyb file and assign a new name with matching number, e.g. function_w9.ipnyb
3. Open function_w9.ipnyb and set:
   - resultsfile = "results09.csv"
   - file = 1

Run the code and it will generate the results for function 1, copy the results and update file =2 to calculate results for function 2, and so on.


# Fictional Army Data Analysis: Filtering and Sorting

This project involves the analysis of a fictional army dataset using Python and the Pandas library. The dataset provides information about different attributes related to various army regiments.

## Project Overview

This repository contains Python code for analyzing a fictional army dataset using the Pandas library. The analysis includes steps to create a DataFrame, filter and select data, and answer questions related to specific rows and columns. The primary goals of this project are:

- Create a DataFrame named `army` from provided data.
- Filter and select data based on specific criteria.
- Perform slicing and indexing operations on the DataFrame.

## Steps in the Analysis

1. Import the necessary library, pandas.
2. Create a DataFrame named `army` using the provided raw data dictionary.
3. Set the 'origin' column as the index of the DataFrame.
4. Print the 'veterans' column.
5. Print columns 'veterans' and 'deaths'.
6. Print the names of all the columns.
7. Select the 'deaths', 'size', and 'deserters' columns from "Maine" and "Alaska".
8. Select rows 3 to 7 and columns 3 to 6.
9. Select every row after the fourth row and all columns.
10. Select every row up to the fourth row and all columns.
11. Select the third column up to the seventh column.
12. Select rows where 'deaths' is greater than 50.
13. Select rows where 'deaths' is greater than 500 or less than 50.
14. Select all the regiments not named "Dragoons".
15. Select the rows named "Texas" and "Arizona".
16. Select the third cell in the row named "Arizona".
17. Select the third cell down in the column named "deaths".

## Repository Structure

```
Fictional-Army-Filter-Sort/
│
├── army_filter_sort.ipynb         # Jupyter Notebook with analysis code
└── readme.md                      # Project summary
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/Fictional-Army-Filter-Sort.git`
2. Navigate to the repository: `cd Fictional-Army-Filter-Sort`
3. Open the `army_filter_sort.ipynb` notebook to see the detailed analysis steps and results.

## Acknowledgments

- The data was inspired by [chrisalbon](http://chrisalbon.com/python/).
- Special thanks to the contributors of the Pandas library for providing the tools for data analysis.

---

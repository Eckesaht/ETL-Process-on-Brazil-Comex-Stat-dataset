# ETL - Brazil Comex

## Overview

This project implements an Extract, Transform, Load (ETL) process for analyzing import and export data. The data is extracted from CSV files, transformed using Python and the Pandas library, and finally, the transformed data is saved into new CSV files.

## Structure

The Jupyter Notebook is structured into several cells, each representing a stage in the ETL pipeline:

1. **Setup and Imports**: Importing necessary Python packages.
2. **Data Extraction**: Loading data from CSV files.
3. **Initial Data Cleaning and Renaming**: Initial cleaning and formatting of the data.
4. **Advanced Data Manipulation**: Detailed transformation of the data including pivoting and merging.
5. **Calculations and Final Adjustments**: Performing calculations and final data adjustments.
6. **Data Export**: Saving the transformed data to CSV files.

## Prerequisites

To run this project, you need to have the following installed:
- Python 3.x
- Pandas library
- NumPy library

## Installation

Clone this repository to your local machine using:

```bash
git clone https://github.com/psilva8769?tab=repositories
```

## Usage

Open the Jupyter Notebook (`etl.ipynb`) in a Jupyter environment and run each cell in sequence. Ensure that the CSV files are placed in the specified file paths before running the notebook.

## Data Files

- **Import Data (`IMP_2022.csv`)**: Contains import data for the year 2022.
- **Export Data (`EXP_2022.csv`)**: Contains export data for the year 2022.

## Output

The final output will be a set of CSV files, each corresponding to a specific state's import and export data for the year 2022, saved in the specified export directory.

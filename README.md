# Data Standardization and Cleaning Project

## Overview

This project focuses on the standardization and cleaning of a dataset to ensure it is optimized for further analysis and use. The main tasks involved in this process include removing duplicates, correcting formatting issues, and fixing encoding problems in the data.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Data Cleaning Process](#data-cleaning-process)
- [File Structure](#file-structure)
- [Installation](#installation)
- [Usage](#usage)


## Project Description

The goal of this project is to prepare a dataset by cleaning and standardizing it. This involves various steps to ensure that the data is free of duplicates, correctly formatted, and properly encoded. The cleaned data is ready for efficient analysis and use in any subsequent processes.

## Features

- **Duplicate Removal**: Eliminated duplicate rows and columns to maintain data integrity.
- **Data Formatting**: Ensured all data fields are in the correct format for easy and efficient use.
- **Column Filtering**: Cleaned and formatted specific columns, such as the salary column, to standardize their format.
- **Vice Column Cleanup**: Removed or corrected entries in the Vice column that were either duplicates or improperly filled.
- **Date Formatting**: Unified the date formats across the dataset to a single, consistent format.
- **Encoding Fix**: Resolved a bug in the President column where data was incorrectly displayed due to UTF-8 encoding issues.

## Data Cleaning Process

### 1. Duplicate Removal
- Removed all duplicate rows and columns to ensure data uniqueness.

### 2. Data Formatting
- Applied consistent formatting to the entire dataset to make it suitable for analysis.

### 3. Column Filtering and Formatting
- Filtered out columns that were not in the correct format.
- Standardized the salary column and other relevant fields.

### 4. Vice Column Cleanup
- Corrected entries in the Vice column by removing duplicates and ensuring all entries were properly filled.

### 5. Date Formatting
- Converted all date fields into a single, standardized format.

### 6. Encoding Fix
- Addressed a bug in the President column where data was incorrectly displayed due to UTF-8 encoding issues.

## File Structure

```plaintext
├── data/
│   ├── raw_data.csv
│   ├── cleaned_data.csv
├── scripts/
│   ├── clean_data.py
│   ├── standardize_data.py
├── README.md
└── LICENSE
```

## Installation

To use the scripts provided in this repository, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/yourusername/data-cleaning-project.git
cd data-cleaning-project
pip install -r requirements.txt
```

## Usage

To run the cleaning and standardization scripts use the following commands:

```bash
python scripts/clean_data.py
python scripts/standardize_data.py
```

These scripts will process the raw data and output a cleaned version in the `data/` directory.



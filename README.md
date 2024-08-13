# MIMIC-III Extubation Failure Analysis

Repository for analyzing extubation failure in ICUs using the MIMIC-III dataset. This repository contains all the necessary files and scripts for data processing and analysis.

## Repository Structure

- **data/**: Contains raw and processed data files.
- **notebooks/**: Jupyter notebooks for data processing and analysis.
- **scripts/**: Python scripts for various data processing tasks.
- **results/**: Output files and visualizations generated from the analysis.

## Objective

The primary objective of this repository is to process the MIMIC-III dataset and gain insights into extubation failure in ICUs. The analysis includes:

- Filtering and cleaning the data
- Calculating procedure durations and overlaps
- Labeling procedures based on time since last intubation
- Analyzing the influence of various other variables (e.g., Heart Rate) on the extubation process

## MIMIC-III Dataset

The MIMIC-III (Medical Information Mart for Intensive Care III) dataset is a large, freely-available database comprising de-identified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012. The dataset includes information such as demographics, vital signs, laboratory tests, medications, and more.

## Scripts Overview

The scripts in this repository are designed to load and process the MIMIC-III files to extract meaningful insights. Key scripts include:

- **data_loading.py**: Loads the raw MIMIC-III data files into pandas DataFrames.
- **data_cleaning.py**: Cleans and preprocesses the data, handling missing values and filtering relevant records.
- **procedure_analysis.py**: Analyzes procedure durations, identifies overlaps, and labels procedures based on specific criteria.
- **visualization.py**: Generates visualizations to help understand the data and the results of the analysis.

## Getting Started

1. **Clone the repository**:
    ```sh
    git clone <repository_url>
    cd <repository_name>
    ```

2. **Install dependencies**:
    Ensure you have Python and the required libraries installed. You can install the dependencies using:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the notebooks**:
    Navigate to the `notebooks/` directory and open the Jupyter notebooks to start processing and analyzing the data.


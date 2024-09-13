# MIMIC-III Extubation Failure Analysis

Repository for analyzing extubation failure in ICUs using the MIMIC-III dataset. This repository contains all the necessary files and scripts for data processing and analysis.

## Repository Content

MIMICIII_dataprocessing.ipynb - Notebook with the code that selects IMV patients 

heart_rate.ipynb - Notebook with the code for gathering the HR data from the MIMIC-III dataset and match them with the selected patients

## Objective

The primary objective of this repository is to process the MIMIC-III dataset and gain insights into extubation failure in ICUs. The analysis includes:

- Filtering and cleaning the data
- Calculating procedure durations and overlaps
- Labeling procedures based on time since last intubation
- Analyzing the influence of various other variables (e.g., Heart Rate) on the extubation process

## MIMIC-III Dataset

The MIMIC-III (Medical Information Mart for Intensive Care III) dataset is a large, freely-available database comprising de-identified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012. The dataset includes information such as demographics, vital signs, laboratory tests, medications, and more.



## Getting Started

1. **Clone the repository**:
    ```sh
    git clone https://github.com/felipe-matsuoka123/MIMIC-III-Extubation-Failure-Analysis
    cd MIMIC-III-Extubation-Failure-Analysis
    ```

2. **Install dependencies**:
    Ensure you have Python and the required libraries installed. You can install the dependencies using:
    ```sh
    pip install -r requirements.txt
    ```



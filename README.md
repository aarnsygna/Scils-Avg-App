# Scils-Avg-App

## Overview
Scils-Avg-App processes tab-separated `.csv`,collected from SCILS software, files by calculating the average number of values in columns containing m/z values. The results are then output to a new `.csv` file.

## Features
- **Input:** TSV-formatted `.csv` files.
- **Functionality:** Calculates the average for columns with m/z values.
- **Output:** Generates a processed `.csv` file with calculated averages.

## Requirements
- Python (compatible with Jupyter Notebook)
- Required libraries listed in `requirements.txt`

## Usage
1. Clone the repository:
   ```sh
    git clone https://github.com/aarnsygna/Scils-Avg-App.git
   ```
2.	Navigate to the project directory and install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3.	Run the application via Jupyter Notebook:
   ```sh
  	jupyter notebook scils-avg.py.ipynb
   ```
4.	Follow the instructions in the notebook to process your .csv file.

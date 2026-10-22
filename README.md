# Health Data Analysis

## Project Overview

This project explores a medical insurance dataset using Python, pandas, Matplotlib, and Seaborn. The goal is to analyze medical insurance charges and identify patterns related to age, BMI, smoking status, and region.

This project uses exploratory data analysis and data visualization to investigate patterns in medical insurance charges.

## Objectives

- Explore and summarize the dataset.
- Check for missing values and duplicate records.
- Analyze the distribution of medical insurance charges.
- Compare insurance charges between smokers and non-smokers.
- Explore relationships between age, BMI, and insurance charges.
- Communicate findings through data visualizations.

## Dataset

This project uses the **Medical Cost Personal Dataset**, available on Kaggle.

**Dataset source:** https://www.kaggle.com/datasets/mirichoi0218/insurance

The dataset contains information such as age, sex, BMI, number of children, smoking status, region, and medical insurance charges.

The CSV file is not included in this repository. To run the analysis:

1. Download `insurance.csv` from the Kaggle dataset page above.
2. Create a folder named `data` in the project directory.
3. Place `insurance.csv` inside the `data` folder.

Please review the dataset's licence and follow its attribution and usage requirements.

## Tools and Libraries

- Python
- pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Health-Data-Analysis/
├── data/
│   └── insurance.csv          # Download separately; not tracked on GitHub
├── notebooks/
│   └── health_data_analysis.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset and place it at `data/insurance.csv`.
4. Open `notebooks/health_data_analysis.ipynb` in Jupyter Notebook.
5. Run the notebook cells from top to bottom.

## Key Findings

The notebook investigates how insurance charges vary with smoking status, age, BMI, and region. Findings should be based on the actual results and visualizations produced by the analysis.

## Limitations

This analysis identifies patterns and associations in the available dataset. It does not establish that any particular factor causes higher insurance charges, and the findings may not generalize to other populations or healthcare systems.

## Author

Aseda Kofi Boateng

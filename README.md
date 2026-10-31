# Food Waste Management – Data Profiling (EDA)

## Assignment 1: Data Profiling (EDA) Report

This project focuses on identifying and handling data quality issues in a synthetic food waste management dataset. The analysis covers missing values, outliers, duplicates, inconsistent formats, invalid values, and potential PII and bias risks.

The purpose is to evaluate whether the dataset is suitable for food waste monitoring and analysis.

## Group Members

| Name | Matric Number | Role |
|---|---|---|
| FINA ELFIANI BINTI NURFAUZI | A211160 | Scenario, Data Source, Data Loading, Conclusion & GitHub |
| QISTINA BALQIS BINTI ABDUL AZIZ | A211077 | Missing Values Analysis |
| WAN NUR HANAA’ BINTI WAN MUHAMMAD HAMKA | A211708 | Outlier Detection and Handling |
| MAISARAH HASYA SYAZWANA BINTI MOHD HELMI | A211488 | Other Quality Issues, PII and Bias Risks |

## Dataset Information

**Dataset:** AI-Powered Food Waste Management Dataset v1

**Source:** Kaggle

**Dataset URL:** https://www.kaggle.com/datasets/vinay24baghira/ai-powered-food-waste-management-dataset-v1

**Dataset Type:** Synthetic

**Dataset Size:** 8,000 rows and 16 coriginal attributes

**Files:** food_waste_dataset.csv and data_dictionary.csv

The dataset contains simulated food inventory records from supermarkets, restaurants, cafeterias, and cloud kitchens.

## Tools and Libraries

- Python
- Google Colab 
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## How to Run the Notebook

1. Open `Assignment1_Food_Waste_EDA.ipynb` in Google Colab.
2. Ensure that the required Python libraries are available.
3. Run all cells from top to bottom using **Runtime → Run all**.
4. Review the outputs, diagnostic charts, and data quality findings.

The notebook currently loads the CSV dataset from the group's GitHub repository.

## Analysis Sections

1. Scenario
2. Data Source
3. Data Profiling and Issue Handling
   - Missing Values
   - Outliers
   - Other Data Quality Issues
4. Exploratory Diagnostic Charts
5. PII and Bias Risks
6. Conclusion

## Key Findings

- Missing values were identified in five columns and handled without removing records.
- Numerical outliers were detected and retained because they may contain useful information.
- No exact duplicate records or repeated inventory IDs were found.
- Incorrect data types were converted to more suitable formats.
- 104 inconsistent Waste_Level labels were corrected.
- 70 suspicious storage temperature records were flagged for further investigation.
- No direct personally identifiable information was identified.

## Conclusion and Limitations

After data profiling and cleaning, the dataset is more consistent and suitable for exploratory analysis and educational food waste monitoring.

However, the dataset is synthetic and contains limitations such as unbalanced categories, imputed values, and uncertain waste-level thresholds. Further validation using real-world data would be needed before applying the findings to actual business decisions.

## Notes

The dataset is synthetic and intended for educational and research purposes. Findings may not fully represent real-world supermarket operations.

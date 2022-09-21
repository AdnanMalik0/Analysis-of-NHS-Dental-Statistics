# Analysis of NHS Dental Statistics

Analysis of NHS dental statistics in England for 12-month period to 31.03.2019. Also studying the relationship between "Deprivation-index" and "Number of Patients" in CCGs.

## Information on the Data & Analysis

The data was taken from the Official NHS Dental Statistics website https://digital.nhs.uk/data-and-information/publications/statistical/nhs-dental-statistics.

There are five datasets that are considered as the raw-data, and they were downloaded and used to construct the final dataset, which contains all the required features to conduct the analysis, those five datasets are respectively:

1. Dentists’ data:
“NHS Dental Statistics for England 2018-19 Annex3_Workforce.csv”.
2. Patients’ (Jul-Dec 2018): “nhs-dent-stat-eng-jul-dec-18-anx3-ps-prac.csv”.
3. Patients’ (Jan-Jun 2019): “nhs-dent-stat-eng-jan-jun-19-anx3-ps-prac.csv”.
4. CCG (Mapping of CCG codes to CCG names): “nhs-dent-stat-eng-18-19-anx2.xlsx”.
5. IMD (index of deprivation): “File_13__IoD2019_Clinical_Commissioning_GroupCCGSummaries.xlsx”.

Analysis is done in the notebooks, done in two parts:

1. Data_Prep.ipynb = Data is linked and redundant information is discareded. Finally, a processed and cleaned .CSV file is saved for Data-Analysis by the name "processed.csv".
2. Analysis.ipynb = Contains the data-analysis and results

Refer to **"MAIN.pdf"** for the explanation, understanding and interpretation of the results.
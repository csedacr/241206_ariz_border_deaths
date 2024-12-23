# 241206_ariz_border_deaths
# **Description**

This repository contains a dataset, code, and findings that support the preliminary analysis found in the draft "Female Deaths Decreasing in Arizona Borderlands” for the Advanced Data Journalism course at CUNY Grad School of Journalism.

The raw dataset for Arizona is the "Arizona OpenGIS Initiative for Deceased Migrants" and can be obtained from https://www.humaneborders.org/migrant-death-mapping. It is the result of data compiled by the nonprofit Humane Borders and the Pima County Office of the Medical Examiner from 1981 to October 2024.


# **Methodology**

The analysis uses the spreadsheet:

- az_deaths.csv: Raw data from "Arizona OpenGIS Initiative for Deceased Migrants" compiled by Humane Borders and - Pima County Office of the Medical Examiner. Data ranges from 1981 to October 2024.

- The notebook arizona_border_deaths.ipynb contains a filtered version of the "Arizona OpenGIS Initiative for Deceased Migrants" to only show the "ML Number"  "Reporting Date" and "Sex”.
- Notebook also contains “az_female_deaths.jpg" in the output with the number of female remains found by year by sector 

Steps

- To do this you first have to upload the dataset, filter it and create columns for "ML Number" , "Reporting Date" and "Sex"
- Set to date time so the code is read as a date in the graph, then group by 'Reporting Date' column.
- Filter by query to narrow by female
- Save it to a new csv file
- Sort values by ascending and then graph that date on a line graph from 1981 to 2024
- Export it as jpg


# **Running the analysis yourself**
You can run the analysis yourself with the following installed on your computer:
- Python 3
- Pandas library
- Matplotlib library

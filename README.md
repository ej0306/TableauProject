# Covid Visual Analysis Project

## Project Description

This project involved a comprehensive visual analysis of Covid-19 protection efficacy by vaccine type using Tableau. The following datasets were utilized:

1. **Vaccine Efficacy Data**:
   - Dataset: "Covid Protection Efficacy by Vaccine Type.xlsx"
   - Note: This was an image, not a real spreadsheet, requiring manual reading and copying of values.
   - Columns Used:
     - A (Vaccine Type)
     - E, F, K, L, M, N (Efficacy Data)
   - Analysis Focus: Ancestral (Original) and Omicron variants, with Delta optionally included for detailed insights.

2. **Country Vaccine Data**:
   - Dataset: "vaccination-data-WHO-12-28-2022-NO-DETAILS for-vaccinetype-date.xlsx"
   - Columns Used:
     - A (Country)
     - C (WHO_Region)
     - E (DATE_UPDATED)
     - L (Vaccine_Used)
     - N (Count of Types of Vaccines)

3. **Vaccination and Population Data**:
   - Dataset: "owid-covid-data-ALL-COUNTRIES.xlsx"
   - Columns Used:
     - B (Continent)
     - C (Country - labeled as location)
     - D (Date)
     - F (People Vaccinated)
     - L (Population)

4. **Efficacy by Country**:
   - Dataset: "Covid Protection Efficacy By Country - Averaged Out.XLSX"
   - Columns G, H, I, J were filled using provided formulae to average the efficacy values for different vaccines for each country.

## Data Completion Steps
- Filled in 192 blank rows in "Covid Protection Efficacy By Country - Averaged Out.XLSX".
- Populated the following columns:
   - **Col K**: Population data from "owid-covid-data-ALL-COUNTRIES.xlsx"
   - **Col L**: People vaccinated data from "owid-covid-data-ALL-COUNTRIES.xlsx"
   - **Col M**: % of people vaccinated using the formula `(L/K)*100`
   - **Col N**: Used formula `(M*G)/100`
   - **Col O**: Used formula `(M*H)/100`
   - **Col P**: Used formula `(M*I)/100`
   - **Col Q**: Used formula `(M*J)/100`

## Visual Analysis
- Created various visuals using Tableau with the breakthrough infection data.
- Developed multiple visuals to demonstrate analytical skills.
- Excluded countries with no data for vaccine types and noted this exclusion in the analysis.

## Important Notes
- Ensured accuracy and consistency when manually copying data.
- Focused primarily on the Ancestral (Original) and Omicron variants.
- Utilized provided formulae for calculating averaged-out efficacy by country.

This project showcases the ability to handle complex data, perform detailed analysis, and present findings effectively using Tableau.

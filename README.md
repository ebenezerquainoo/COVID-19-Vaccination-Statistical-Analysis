# COVID-19 Vaccination Statistical Analysis

## About the Project

I completed this project as my final-year research project for my BSc in Mathematics at the University of Mines and Technology (UMaT), Ghana, in 2023. The project was supervised by Dr. Benjamin Odoi.

The study examined COVID-19 vaccination among UMaT students, with particular interest in whether vaccination rates differed among students in different academic years and in understanding factors associated with vaccination.

## Research Objectives

The main objectives of the study were to:

* Apply the Kruskal-Wallis test to COVID-19 vaccination data across academic-year groups.
* Examine vaccination patterns among UMaT students.
* Provide data-driven insights into students' vaccination behavior, attitudes, and perceptions.

## Data Collection

Data were collected using a structured questionnaire. The questionnaire included questions about:

* Age
* Gender
* Academic year
* COVID-19 vaccination status
* Vaccine type
* Number of doses
* Vaccination information
* Attitudes and perceptions about COVID-19 vaccination

The questionnaire was pilot-tested before the main data collection.

## Original Statistical Analysis

The original analysis included:

* Data preparation
* Ranking of observations
* Descriptive statistics
* Nonparametric statistical analysis
* Kruskal-Wallis hypothesis testing

The Kruskal-Wallis test was used to examine whether vaccination rates differed across academic-year groups.

### Original Research Result

The original 2023 analysis reported:

* **Kruskal-Wallis H:** 3.00
* **Degrees of freedom:** 3
* **p-value:** 0.392
* **Significance level:** 0.05

The study therefore reported no statistically significant difference in vaccination rates among the academic-year groups.

The project also examined vaccination patterns according to characteristics such as gender, vaccine type, dose uptake, booster uptake, vaccine hesitancy, and knowledge about COVID-19 vaccination.

## 2026 Computational Extension

In 2026, I revisited the available survey-response data as part of my preparation for further study in statistics, data science, and computational research.

The available response export contains **101 survey responses** and six variables:

* Timestamp
* Sex/Gender
* Age
* Vaccine Type
* Injection site
* Dose

The computational extension focuses on:

* Data quality assessment
* Data cleaning
* Descriptive statistics
* Exploratory data analysis
* Data visualization
* Statistical analysis

### Important distinction from the original research

The available response export does **not contain the academic-year variable** used in the original 2023 Kruskal-Wallis analysis.

Therefore, this computational extension does **not** claim to reproduce or independently verify the original Kruskal-Wallis result.

Instead, the project separates the original 2023 research analysis from the 2026 computational extension.

## Data Quality and Cleaning

The available response data contain missing and inconsistent values.

Examples include:

* Missing age responses
* Missing gender responses
* Missing vaccine-type responses
* Missing dose responses
* A non-numeric age response (`wo`)

For the computational analysis, valid numeric age responses are used for age-based descriptive analysis. Invalid or missing values are treated as missing rather than being assigned arbitrary values.

The respondent-level dataset is kept private and is **not included in this public repository**.

## Exploratory Data Analysis

The 2026 analysis examines:

* Age distribution
* Gender distribution
* Vaccine-type distribution
* Dose distribution
* Vaccination status
* Missing-data patterns
* Relationships between selected demographic and vaccination variables

The analysis notebook is available in the [`analysis`](analysis/) folder:

[`01_exploratory_data_analysis.ipynb`](analysis/01_exploratory_data_analysis.ipynb)

Selected visualizations are also included in the repository:

* [Age Distribution](age_distribution.png)
* [Gender Distribution](gender_distribution.png)
* [Vaccine Type Distribution](vaccine_type_distribution.png)
* [Dose Distribution](dose_distribution.png)

## Key Findings from the Computational Extension

The available dataset contains **101 responses**.

Among the available responses:

* **60** respondents have valid numeric ages.
* The mean age among valid numeric ages is approximately **21.25 years**.
* The median age is **20.5 years**.
* **57** respondents reported male gender.
* **41** respondents reported female gender.
* **3** gender responses were missing.
* **93** respondents were classified as vaccinated based on their reported vaccine type.
* **2** respondents were classified as not vaccinated.
* **6** responses could not be assigned a vaccination status because vaccine-type information was missing.

Because some categories contain very few observations, inferential results involving those categories should be interpreted cautiously.

## Research Skills Demonstrated

* Quantitative research
* Questionnaire design and data collection
* Data cleaning
* Exploratory data analysis
* Descriptive statistics
* Nonparametric statistics
* Statistical interpretation
* Python-based data analysis
* Data visualization
* Research documentation
* Reproducible analytical workflow

## Research Summary

The original project summary is available here:

[`PROJECT SUMMARY.pdf`](PROJECT%20SUMMARY.pdf)

## Project Structure

```text
COVID-19-Vaccination-Statistical-Analysis/
│
├── README.md
├── PROJECT SUMMARY.pdf
│
├── analysis/
│   └── 01_exploratory_data_analysis.ipynb
│
├── age_distribution.png
├── dose_distribution.png
├── gender_distribution.png
└── vaccine_type_distribution.png
```

## Data Privacy

The respondent-level survey dataset is not included in this public repository.

Only aggregate analytical outputs, documentation, visualizations, and the analysis notebook are intended for public sharing.

## Author

**Ebenezer Quainoo**

BSc Mathematics


University of Mines and Technology (UMaT), Ghana

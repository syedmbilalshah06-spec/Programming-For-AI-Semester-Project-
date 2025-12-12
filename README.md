# COVID-19 Data Analysis Project

A comprehensive data analysis project using Python to analyze global COVID-19 trends, implement risk assessment systems, and generate actionable insights from Johns Hopkins University data.

##  Project Overview

This project analyzes global COVID-19 data to:
- Track pandemic progression from 2020-2023
- Implement rule-based risk assessment for countries
- Generate data visualizations and statistical insights
- Provide actionable recommendations for pandemic response

## Project Structure

COVID-19-Analysis/
├── PAI_Project.ipynb # Main Jupyter Notebook
├── covid19_cleaned_data.csv # Processed dataset
├── covid19_risk_assessment.csv # Risk assessment results
├── covid19_summary_statistics.csv # Country-wise statistics
├── covid19_global_trends.png # Global trends visualization
├── covid19_distributions.png # Statistical distributions
├── covid19_correlation_heatmap.png # Correlation matrix
├── covid19_risk_scores.png # Risk assessment visualization
├── requirements.txt # Python dependencies
└── README.md # This file


##  Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development

##  Data Sources

- **Primary Dataset**: [Johns Hopkins University COVID-19 Repository](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data)
  - Time series data (January 22, 2020 - March 9, 2023)
  - Global confirmed cases, deaths, and recoveries
  - 289 countries/regions with daily updates

## Installation & Setup

1. **Clone the repository**
   git clone https://github.com/yourusername/covid19-analysis.git
   cd covid19-analysis

2. **Install dependencies**
    pip install -r requirements.txt

3. **Run the analysis**
    jupyter notebook PAI_Project.ipynb

## Dependencies (requirements.txt)
  pandas>=1.5.0
  numpy>=1.24.0
  matplotlib>=3.7.0
  seaborn>=0.12.0
  jupyter>=1.0.0

##  Key Features
1. **Data Processing Pipeline**
Automatic data loading from JHU GitHub

Data cleaning and preprocessing

Time-series data transformation

Missing value handling

2. **Exploratory Data Analysis**
Global trend analysis

Country-wise comparisons

Mortality and recovery rate calculations

Statistical correlation analysis

3. **Rule-Based Risk Assessment**
Multi-factor risk scoring system

Four risk categories (Low to Critical)

Country-specific recommendations

Population-adjusted metrics

4. **Data Visualization**
Global pandemic progression charts

Country ranking visualizations

Statistical distribution plots

Correlation heatmaps

## Key Insights
**Global Trends**
Total cases analyzed: [Your Total] million

Peak infection period: [Month Year]

Global mortality rate: [X.XX]%

**Country Analysis**
Highest mortality rate: [Country] ([X.XX]%)

Lowest mortality rate: [Country] ([X.XX]%)

Most affected country: [Country] ([X] million cases)

**Risk Assessment Results**
Critical risk countries: [X]

High risk countries: [X]

Moderate risk countries: [X]

Low risk countries: [X]

## Learning Outcomes
This project demonstrates practical skills in:

Data Analysis: Processing large-scale time-series data

Python Programming: Object-oriented design with classes

Data Visualization: Creating informative charts and graphs

Rule-Based Systems: Implementing decision-making logic

Statistical Analysis: Correlation and trend identification

## How to Use
Complete Analysis: Run all cells in PAI_Project.ipynb

Custom Analysis: Modify the risk assessment parameters

Extend Functionality: Add new data sources or analysis methods

Visualization: Customize chart styles and colors

## Code Structure
python
# Main sections in the notebook:
1. Data Loading & Initial Exploration
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Data Visualizations
5. Rule-Based Risk Evaluator
6. Key Insights & Findings
7. Conclusions & Recommendations

## Limitations & Future Work
**Current Limitations**
Historical data only (ended March 2023)

Limited healthcare infrastructure data

Simplified population estimates

**Future Enhancements**
Real-time data integration

Machine learning predictions

Healthcare capacity modeling

Interactive dashboard development


## Acknowledgments
Johns Hopkins University for providing comprehensive COVID-19 data

Python open-source community for data science libraries

Educational institutions promoting data literacy


Project Link: https://github.com/syedmbilalshah06-spec/Programming-For-AI-Semester-Project-



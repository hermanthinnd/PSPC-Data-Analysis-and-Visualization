# PSPC Real Estate Data Analysis & Visualization Project

## Project Overview

This is a **practice data analysis and visualization project** using publicly available government data from the **Public Services and Procurement Canada (PSPC)** Real Estate Department. The project demonstrates comprehensive data exploration, analysis, and visualization techniques applied to real government datasets.

## Project Purpose

This project serves as a **learning exercise** for:
- Real-world government data analysis
- Multi-dimensional data exploration
- Data visualization techniques
- Exploratory data analysis (EDA)
- Public data interpretation
- Academic research and practice

⚠️ **Academic Purpose Only**: This project is intended for educational and learning purposes. All analyses are for practice and demonstration of data science skills.

## Data Source

**Source**: Public Services and Procurement Canada (PSPC)
**Department**: Real Estate Management Division
**Data Type**: Public government datasets on federal real estate properties
**Dataset Type**: ODATA feeds and property management data

## Project Structure

The project is organized into three main analysis modules:

### 📊 **1. Accessibility Analysis**
**Location**: `Accessibility/` folder

**Objective**: Analyze accessibility features and compliance of federal properties

**Contents**:
- `Access.ipynb` - Jupyter notebook with accessibility analysis
- `acess_score.csv` - Accessibility scoring dataset

**Analysis Includes**:
- Building accessibility ratings
- Accessibility compliance levels
- Distribution of accessible features
- Statistical analysis of accessibility metrics
- Visualizations of accessibility standards across properties

**Key Findings**:
- Identification of properties with high/low accessibility scores
- Accessibility trends across different regions
- Compliance with accessibility standards
- Areas requiring accessibility improvements

---

### 🏢 **2. Building Condition Analysis**
**Location**: `Condition/` folder

**Objective**: Assess and analyze the physical condition of federal buildings

**Contents**:
- `Building_Condition.ipynb` - Jupyter notebook with condition analysis
- `bureauxmodernisesnormes-officemodernizedstandards.csv` - Office modernization standards data
- `immeubleetatadequat-buildingfaircondition.csv` - Building condition status data

**Analysis Includes**:
- Building condition ratings (Fair, Good, Poor, etc.)
- Modernization status of offices
- Building maintenance requirements
- Condition distribution across property portfolio
- Trend analysis over time

**Key Findings**:
- Overall condition assessment of federal properties
- Modernization needs and priorities
- Properties requiring maintenance
- Condition trends and improvements
- Risk assessment based on building condition

---

### 📈 **3. Property Status & Budget Analysis**
**Location**: `Status/` folder

**Objective**: Analyze property status and real estate project budgets

**Contents**:
- `Status.ipynb` - Jupyter notebook with status and budget analysis
- `projimmobiliersbudget-realpropertyprojbudget-2024-2025.csv` - 2024-2025 budget data

**Parent Dataset Files**:
- `projimmobiliersbudget-realpropertyprojbudget-2021-2022.csv` - 2021-2022 budgets
- `projimmobiliersbudget-realpropertyprojbudget-2022-2023.csv` - 2022-2023 budgets
- `projimmobiliersbudget-realpropertyprojbudget-2023-2024.csv` - 2023-2024 budgets
- `Properties_Available_For_Sale.csv` - Properties in sale inventory

**Analysis Includes**:
- Real estate project budget tracking
- Year-over-year budget comparisons
- Property status classifications
- Budget allocation analysis
- Properties available for sale
- Financial trends in real estate portfolio

**Key Findings**:
- Budget trends from 2021-2025
- Major real estate projects
- Property disposal and sales activities
- Budget utilization patterns
- Cost analysis across different property types

---

## Tools & Technologies

- **Python 3.x**
- **Jupyter Notebook** - For interactive analysis
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **NumPy** - Numerical computations
- **Plotly** - Interactive visualizations (optional)

## Getting Started

### 1. Install Dependencies
```bash
pip install pandas numpy matplotlib jupyter
```

### 2. Navigate to Project
```bash
cd PSPC_Data_Analysis
```

### 3. Run Individual Analyses
```bash
# Accessibility Analysis
jupyter notebook Accessibility/Access.ipynb

# Building Condition Analysis
jupyter notebook Condition/Building_Condition.ipynb

# Status & Budget Analysis
jupyter notebook Status/Status.ipynb
```

## Data Files Description

| File Name | Description | Records |
|-----------|-------------|---------|
| `acess_score.csv` | Accessibility scores for properties | Property accessibility metrics |
| `bureauxmodernisesnormes-officemodernizedstandards.csv` | Office modernization standards | Modernization status data |
| `immeubleetatadequat-buildingfaircondition.csv` | Building condition ratings | Property condition assessments |
| `projimmobiliersbudget-*.csv` | Annual real estate budgets | Project budgets by year |
| `Properties_Available_For_Sale.csv` | Properties in sales inventory | Property disposal data |

## Project Insights

### Accessibility Module Insights
- Comprehensive accessibility audit of federal properties
- Identification of compliance levels
- Recommendations for improvements

### Building Condition Module Insights
- Current state of federal real estate portfolio
- Modernization priorities
- Maintenance forecasting

### Budget & Status Module Insights
- Multi-year budget trends
- Resource allocation patterns
- Portfolio management metrics
- Asset disposal activities

## Key Visualizations

The project includes:
- **Histograms**: Distribution of accessibility scores and condition ratings
- **Bar Charts**: Budget comparisons across years
- **Pie Charts**: Property status distribution
- **Time Series**: Budget trends 2021-2025
- **Heatmaps**: Correlation analysis
- **Box Plots**: Statistical distribution analysis
- **Scatter Plots**: Relationships between variables

## Data Analysis Methodology

```
1. Data Loading & Exploration
   ↓
2. Data Cleaning & Preparation
   ↓
3. Exploratory Data Analysis (EDA)
   ↓
4. Statistical Analysis
   ↓
5. Visualization & Interpretation
   ↓
6. Findings & Summary
```

## Findings Summary

### Accessibility
- Properties classified by accessibility compliance
- Accessibility score distribution across portfolio
- Regional accessibility patterns

### Building Condition
- Condition status breakdown (Fair, Good, Excellent, Poor)
- Modernization queue and priorities
- Maintenance requirements forecast

### Budget & Status
- Budget allocation trends
- Year-over-year growth/decline
- Property disposal rates
- Cost per property metrics

## Limitations & Considerations

1. **Data Accuracy**: Based on PSPC public data; potential reporting delays
2. **Temporal**: Data represents specific time periods; may not reflect current status
3. **Completeness**: Some properties may have incomplete data
4. **Academic Purpose**: This analysis is for learning; professional decision-making requires additional context
5. **Classification**: Accessibility and condition ratings are based on available data definitions

## Recommendations for Further Analysis

- Predictive modeling for maintenance requirements
- Correlation analysis between condition and budget
- Regional performance comparisons
- Cost-benefit analysis of modernization
- Asset optimization recommendations
- Portfolio risk assessment
- Machine learning clustering of properties

## Academic Use

This project is designed for:
- ✅ Educational purposes
- ✅ Learning data analysis techniques
- ✅ Understanding government data
- ✅ Practicing visualization skills
- ✅ Research projects
- ✅ Portfolio demonstration

**Not intended for**:
- ❌ Real estate decision-making
- ❌ Official policy recommendations
- ❌ Commercial use
- ❌ Replacing official reports

## References

- [PSPC Open Data Portal](https://open.canada.ca/)
- [Real Property Services](https://www.tpsgc-pwgsc.gc.ca/)
- pandas Documentation: https://pandas.pydata.org/
- Matplotlib Documentation: https://matplotlib.org/

## Disclaimer

⚠️ **ACADEMIC USE ONLY**

This project is created for educational and academic purposes only. The analyses, findings, and conclusions are based on publicly available government data used for learning purposes. This project:

- Does not constitute official analysis
- Should not be used for policy decisions
- Should not be used for real estate transactions
- Should not be relied upon for official reports
- Is for demonstration of data analysis skills only

All data is publicly available from PSPC. Use responsibly and verify information through official sources.

---

**Project Status**: ✅ Complete  
**Data Type**: Public Government Data  
**Purpose**: Academic & Educational  
**Last Updated**: May 2026

# NEPSE Stock Exchange Analysis
A comprehensive data-driven analysis of 124 companies listed on the Nepal Stock Exchange (NEPSE), processing over 250,000 trading records to evaluate stocks through modern portfolio theory, risk-adjusted performance, and technical momentum indicators.
# Overview
This project performs a comprehensive analysis of the Nepal Stock Exchange (NEPSE), moving beyond simple price tracking to evaluate stocks through multiple analytical lenses:

Modern Portfolio Theory application

Risk-adjusted performance metrics

Technical momentum analysis

Liquidity assessment

Volatility profiling
The dataset includes 258,786 trading records across 124 companies, providing robust statistical validity to the findings.

# Key Features
Data Processing: Automated ingestion and merging of 124 CSV files
 Feature Engineering: Calculated daily returns, price ranges, and trend indicators
 Missing Value Handling: Intelligent imputation for 100% data coverage
 Statistical Analysis: Company-level aggregation with 10+ metrics
 Visualization: Distribution plots and analytical charts
 Actionable Insights: Identified high-value vs high-risk investment opportunities

# Data Processing Pipeline
Data Collection: Merged 124 company-wise CSV files

Cleaning: Handled missing values (0.03% in per_change column)

Transformation:

Converted published_date to datetime

Calculated percentage changes from close prices

Added derived features: daily_return, price_range, trend

Aggregation: Grouped by company for summary statistics

# Top 5 Companies by Average Closing Price
Company	Avg Close (NPR)	Volatility	Total Traded Amount
CIT	2,743.19	2.57%	62.09B NPR
LICN	1,897.91	2.78%	38.99B NPR
NLIC	1,756.72	2.59%	126.06B NPR
SCB	    1,295.11	2.25%	39.72B NPR
CHDC	1,264.19	2.85%	61.43B NPR

# Market Analysis
Price Leaders: CIT, LICN, and NLIC emerge as high-ticket 'Blue Chips'

Liquidity Leaders: NABIL and EBL show highest trade velocity

High-Risk High-Return: CHCL (6.0% volatility) suitable for short-term trading

Stability Options: NABIL and SCB offer consistent long-term performance

# Advanced Analysis

Analysis Type
Risk-Adjusted Returns	
Wealth Growth Analysis	
Portfolio Optimization	
Volatility Analysis	
Momentum Indicators	(RSI, Moving averages)T

# Project Structure
nepse-stock-analysis/
├── NepseDataAnalysis.ipynb          # Main analysis notebook
├── README.md                        # Project documentation
├── requirements.txt                 # Python dependencies
└── data/                           # Dataset 
    └── company-wise/               # 124 CSV files

# Data Processing & Analysis

Pandas: Data manipulation and aggregation

NumPy: Numerical computations

Glob: File pattern matching for data ingestion

# Visualization

Seaborn: Statistical data visualization

Matplotlib: Plotting and chart creation

# Environment

Jupyter Notebook: Interactive development

Python 3.8+: Core programming language
# Aknowledgments
Data Sourced from: (https://github.com/Aabishkar2/nepse-data/tree/main/data/company)

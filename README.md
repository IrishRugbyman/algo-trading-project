# ESILV Algotrading 2025-26 Capstone Project

## Overview

This project implements and refines a cross-asset trend following strategy using daily closing prices of 47 assets across various asset classes. The strategy is based on well-known Commodity Trading Advisors (CTA) and managed futures approaches.

## Project Structure

- **`capstone 2026.ipynb`**: Main Jupyter notebook containing the complete analysis and strategy implementation
- **`assets_data_student.csv`**: Dataset containing daily closing prices of 47 assets
- **`q3_available_assets.png`**: Visualization of available assets
- **`q4_corrmatrix_2018.png`**: Correlation matrix visualization for 2018
- **`q15_correlation_heatmap.png`**: Correlation heatmap analysis

## Key Features

### 1. Exploratory Data Analysis
- Data loading and preprocessing
- Log-returns computation and analysis
- Asset correlation analysis
- Visualization of asset availability and relationships

### 2. Strategy Implementation
- Trend following algorithm development
- Performance optimization
- Risk management considerations

### 3. Validation
- Out-of-sample testing on 2023-2025 data
- Sharpe ratio calculation for period 2010-2025
- Strategy validation and refinement

## Requirements

The project uses the following Python libraries:
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computations
- `matplotlib` - Plotting and visualization
- `seaborn` - Statistical data visualization
- `scipy` - Statistical functions
- `tqdm` - Progress bars

## Data

The dataset (`assets_data_student.csv`) contains daily closing prices for 47 assets across different asset classes. The data is resampled to daily frequency and log-returns are computed for analysis.

## Timeline

- **Out-of-sample data release**: 26/01/2026 (morning)
- **Final submission deadline**: 28/01/2026 (midnight)

## Author

**Quentin LAMBOLEZ-GIUDICELLI**

## Notes

- The strategy code is prepared to be executed with new out-of-sample data without further optimization
- All analysis and visualizations are contained within the main notebook
- The project follows best practices for algorithmic trading strategy development and validation

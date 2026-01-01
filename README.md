# Exploratory Data Analysis with Python

A comprehensive collection of Jupyter notebooks demonstrating exploratory data analysis techniques using Python's data science ecosystem. This repository showcases practical applications of statistical analysis, data visualization, and pattern discovery across diverse datasets.

## Overview

This repository contains hands-on examples of EDA workflows, from initial data inspection through advanced statistical analysis and visualization. Each notebook demonstrates best practices for understanding data structure, identifying patterns, detecting anomalies, and extracting actionable insights.

## Key Features

- Statistical analysis and hypothesis testing
- Data cleaning and preprocessing techniques
- Univariate and multivariate visualization
- Outlier detection and handling
- Correlation analysis and feature relationships
- Distribution analysis and normality testing

## Technologies Used

- Python 3.x
- Pandas for data manipulation
- NumPy for numerical computing
- Matplotlib and Seaborn for visualization
- Scipy for statistical analysis
- Jupyter Notebook for interactive development

## Repository Structure

```
eda-with-python/
├── content/
│   └── sample_data/          # Dataset files used in analysis
│       ├── citi_bike_trip_data.csv
│       ├── HR-Employee-Attrition.csv
├── citibike.ipynb            # Citibike trip data analysis
├── employee_attrition_analysis.ipynb  # HR attrition prediction analysis
├── LICENSE                   # MIT License
└── README.md                 # Project documentation
```

## Projects

### 1. Citibike Trip Analysis (`citibike.ipynb`)

Exploratory analysis of Citibike trip data examining usage patterns, station popularity, trip durations, and temporal trends. This notebook demonstrates geospatial data handling and time series analysis techniques.

**Key analyses:**
- Trip duration distribution and statistics
- Station usage patterns and demand analysis
- Temporal trends (hourly, daily, monthly patterns)
- Geospatial visualization of station locations
- User type segmentation (subscriber vs customer)

**Dataset:** `citi_bike_trip_data.csv`

### 2. Employee Attrition Analysis (`employee_attrition_analysis.ipynb`)

Comprehensive analysis of employee attrition patterns using HR data. This notebook explores factors contributing to employee turnover through statistical methods and visualization techniques.

**Key analyses:**
- Attrition rate calculation and demographic analysis
- Feature correlation with attrition outcomes
- Distribution analysis across categorical variables
- Outlier detection using z-score methodology
- Comparative analysis between retained and departed employees
- Feature importance for attrition prediction

**Dataset:** `HR-Employee-Attrition.csv`

## Getting Started

### Prerequisites

```bash
Python 3.8+
Jupyter Notebook or JupyterLab
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/jojostx/eda-with-python.git
cd eda-with-python
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open any notebook file (`.ipynb`) to explore the analyses.

## Usage

Each notebook is self-contained and includes:
- Data loading and initial inspection
- Data cleaning and preprocessing steps
- Exploratory visualizations
- Statistical analysis
- Key findings and insights

Run cells sequentially to reproduce the analysis. Modify parameters and visualizations to explore different aspects of the data.

## Analysis Techniques Demonstrated

### Data Inspection
- Dataset structure and dimensions
- Data types and memory usage
- Missing value detection and handling
- Duplicate identification

### Statistical Analysis
- Descriptive statistics (mean, median, mode, standard deviation)
- Distribution analysis (skewness, kurtosis)
- Correlation analysis (Pearson, Spearman)
- Outlier detection (z-score, IQR methods)
- Hypothesis testing

### Visualization
- Univariate plots (histograms, density plots, boxplots)
- Bivariate plots (scatter plots, correlation heatmaps)
- Categorical analysis (bar charts, count plots)
- Time series visualization
- Geospatial mapping

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/analysis-name`)
3. Commit your changes (`git commit -m 'Add new analysis'`)
4. Push to the branch (`git push origin feature/analysis-name`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

**Onyedikachi Ikuru** (jojostx)

## Acknowledgments

- Citibike for providing open trip data
- Kaggle for HR dataset availability
- Python data science community for excellent libraries and tools

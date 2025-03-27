# Internet Traffic Performance Analysis Project

## Overview
This project focuses on analyzing Internet traffic performance data from the Federal Communications Commission (FCC) Measuring Broadband America program. The analysis covers both download and upload performance metrics across different protocols (IPv4 and IPv6) and includes predictive modeling of key performance parameters.

## Project Structure
```
.
├── data/
│   ├── raw/                    # Raw data files from FCC
│   └── processed/              # Processed and cleaned datasets
├── notebooks/
│   ├── 01_data_exploration.ipynb    # Initial data exploration
│   ├── 02_performance_analysis.ipynb # Traffic performance analysis
│   ├── 03_comparative_analysis.ipynb # 2021 vs 2023 comparison
│   └── 04_prediction_models.ipynb   # Predictive modeling
├── src/
│   ├── data_processing.py      # Data processing utilities
│   ├── visualization.py        # Visualization functions
│   └── modeling.py            # Prediction model implementations
└── reports/
    └── final_report.ipynb     # Final project report
```

## Data Description

### Datasets
The project uses the following datasets from FCC's Measuring Broadband America program:
1. **2023 February Data** (Primary Dataset)
   - Download speed metrics:
     - `curr_httpgetmt.csv`: IPv4 HTTP GET performance
     - `curr_httpgetmt6.csv`: IPv6 HTTP GET performance
   - Upload speed metrics:
     - `curr_httppostmt.csv`: IPv4 HTTP POST performance
     - `curr_httppostmt6.csv`: IPv6 HTTP POST performance

2. **2021 February Data** (Comparison Dataset)
   - Same structure as 2023 data for comparative analysis

### Key Metrics
- Download/Upload speeds (bytes/sec)
- Fetch times
- Warmup performance
- Success/failure rates
- Thread utilization
- Server performance

## Project Tasks

### 1. Exploratory Data Analysis (EDA)
Following CRISP-DM methodology:
- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment

### 2. Internet Traffic Performance Analysis
- Analysis of download packages
- Analysis of upload packages
- Parameter relationship analysis
- Performance metric correlations

### 3. Comparative Analysis
- Comparison between 2021 and 2023 datasets
- Performance trend analysis
- Protocol-specific comparisons (IPv4 vs IPv6)

### 4. Predictive Modeling
Three different models will be implemented for predicting selected performance parameters:
1. Model 1: [To be determined based on data characteristics]
2. Model 2: [To be determined based on data characteristics]
3. Model 3: [To be determined based on data characteristics]

Each model will include:
- Synthetic characteristics
- Justification for use
- Limitations
- Parameter selection
- Performance metrics

### 5. Documentation and Reporting
- Comprehensive report with:
  - Clear task descriptions
  - Results presentation
  - Visualizations (tables, charts, diagrams)
  - Comparative analysis
  - Conclusions

## Setup Instructions
1. Clone the repository
2. Download the datasets from FCC:
   - 2023 data: https://data.fcc.gov/download/measuring-broadband-america/2023/data-raw-2023-feb.tar.gz
   - 2021 data: https://data.fcc.gov/download/measuring-broadband-america/2021/data-raw-2021-feb.tar.gz
3. Extract the data to the `data/raw` directory
4. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dependencies
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details. 
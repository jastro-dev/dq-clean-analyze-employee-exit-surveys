# Employee Exit Survey Analysis

Analysis of exit surveys from employees at two educational institutions in Queensland, Australia: the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute.

## Key Questions

1. Are employees who worked for a short time leaving due to dissatisfaction compared to longer-tenured employees?
2. How does age correlate with dissatisfaction-based departures?

## Findings

### Service Length Impact
- Dissatisfaction increases with years of service
- Peak dissatisfaction occurs in established employees (7-10 years tenure)
- Veteran employees (11+ years) show slightly lower dissatisfaction than established employees

### Age Demographics  
- Young adults show marginally lower dissatisfaction (35%) compared to middle-aged adults
- Both age groups maintain 35-40% dissatisfaction rates overall

## Methodology

### Data Preparation
- Standardized column names across datasets
- Filtered for resignation-specific departures
- Created categorical variables for service length and age groups
- Combined datasets with institute identifiers

### Analysis Steps
1. Cleaned and standardized data from both institutions
2. Created service categories: New, Experienced, Established, Veteran
3. Developed age categories: Young Adult, Middle-Aged Adult, Senior
4. Generated visualizations for key metrics
5. Analyzed dissatisfaction patterns across demographics

### Tools Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Key Recommendations
Focus retention efforts on employees approaching the 7-10 year tenure mark
Develop targeted satisfaction initiatives for middle-aged employees
Implement early intervention programs for experienced staff members

## Visualizations
Service length vs dissatisfaction bar charts
Age group dissatisfaction comparisons
Statistical breakdowns by institution

## Technologies
Python 3.12
Pandas for data manipulation
Matplotlib/Seaborn for visualization
Jupyter Notebooks for analysis

## Repository Structure
├── main_notebook.ipynb

├── dete_survey.csv

├── tafe_survey.csv

└── README.md
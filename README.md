[![CI/CD](https://github.com/Ramil-cyber/Ramil-Cloud-Hosted-Notebook-Data-Manipulation/actions/workflows/main.yaml/badge.svg)](https://github.com/Ramil-cyber/Ramil-Cloud-Hosted-Notebook-Data-Manipulation/actions/workflows/main.yaml)


# Project title: Cloud-Hosted Notebook: Data Manipulation with World Bank Dataset

This project uses a Jupyter notebook hosted on Google Colab to manipulate and analyze a World Bank dataset, including various economic and environmental indicators. The notebook performs data loading, data validation, and initial exploration steps, making it suitable for data scientists or analysts interested in working with global development data. [Colab Link](https://colab.research.google.com/drive/1_tdJRX3kaiutr3WTh4os-Saq36yA8vq2?usp=sharing)

## Project Overview

This project demonstrates fundamental data manipulation techniques with a dataset from the World Bank. Key tasks include:
- Importing necessary libraries and the dataset.
- Performing initial data validation and exploration.
- Using assertions to confirm dataset integrity and structure.

## Dataset

The dataset used in this project is hosted on GitHub and accessed via the following URL:
- [World Bank Dataset](https://raw.githubusercontent.com/Ramil-cyber/Ramil-Cloud-Hosted-Notebook-Data-Manipulation/refs/heads/main/data/world_bank_dataset.csv)

### Dataset Columns

The dataset contains the following columns:
- `Country` - Name of the country
- `Year` - Year of observation
- `GDP (USD)` - Gross Domestic Product in USD
- `Population` - Population count
- `Life Expectancy` - Average life expectancy at birth
- `Unemployment Rate (%)` - Unemployment rate as a percentage
- `CO2 Emissions (metric tons per capita)` - CO2 emissions per capita
- `Access to Electricity (%)` - Percentage of population with access to electricity

## Getting Started

### Prerequisites

Ensure you have the following Python packages installed:
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`

You can install these packages using:
```bash
make install
```

### Running the Notebook

1. Open the notebook in [Google Colab](https://colab.research.google.com/github/Ramil-cyber/Ramil-Cloud-Hosted-Notebook-Data-Manipulation/blob/main/Ramil_IDS_706_Cloud_Hosted_Notebook_Data_Manipulation.ipynb) for cloud-based execution.
2. Run each cell sequentially to load data, validate its structure, and perform initial analysis.


### Testing, Linting , Format

Testing based on the tag named test_cell. In order to test other cell add tag 'test_cell'
```bash
make test_file
```

Linting
```bash
make lint
```

Format
```bash
make format
```


### Notebook Structure

1. **Library Imports** - Imports required libraries such as `numpy`, `pandas`, `seaborn`, and `matplotlib`.
2. **Data Load and Overview** - Loads the dataset from GitHub and gives an initial overview.
3. **Data Validation** - Ensures that the dataset structure matches the expected format and that it contains the necessary columns and rows.

### Data Validation

The notebook includes several assertions to confirm:
- Presence of required columns.
- Dataset dimensions (200 rows and 8 columns).

# Flight Price Analysis

This project conducts an in-depth Exploratory Data Analysis (EDA) and feature engineering on the flight price dataset contained in "flight_price.xlsx". The objective is to explore factors influencing flight prices and prepare the dataset for future modeling efforts, though this project focuses solely on the EDA and feature engineering aspects.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributing](#contributing)

## Overview

The project delves into various aspects of flight pricing, utilizing statistical and visual analysis techniques to uncover patterns and insights. By transforming data and creating new features, the dataset is optimized for any subsequent predictive modeling, although this specific project does not extend into model development.

## Features

- **Exploratory Data Analysis (EDA)**: Implements statistical tests and visualizations to understand the distribution, variability, and correlation of features related to flight prices.
- **Feature Engineering**: Enhances the dataset through rigorous feature transformations and the creation of new variables that could potentially improve the efficacy of future predictive models.

## Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flight-price-analysis.git
   cd flight-price-analysis
```
2. **Create a Python virtual environment:**
``` bash 
python -m venv env
source env/bin/activate  # Use `env\Scripts\activate` on Windows

```
3. **Install the required dependencies:**

``` bash
pip install -r requirements.txt
```
## Usage
To start exploring the EDA and feature engineering:

``` bash
jupyter notebook notebook.ipynb
```
Navigate through the notebook to see the analysis and transformations applied to the flight price dataset.

## Project Structure
-`notebook.ipynb`: The Jupyter notebook containing all EDA and feature engineering processes.
-`flight_price.xlsx`: The dataset file used in the analysis.
-`requirements.txt`: Specifies all the Python packages that the project depends on.

## Dependencies
-`numpy`
-`pandas`
-`matplotlib`
-`seaborn`
These packages are required to run the project and are listed in the requirements.txt file.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contributing
Contributions to further enhance the analysis or improve the feature engineering are welcome. Please feel free to fork the repository, make improvements, and submit a pull request.
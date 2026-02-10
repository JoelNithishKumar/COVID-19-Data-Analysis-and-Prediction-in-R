# COVID-19 Data Analysis and Prediction in R

## Project Overview

This project focuses on analyzing and predicting COVID-19 death cases using R. The analysis was conducted from November 2023 to December 2023. The primary goals of the project were to improve the quality of the COVID-19 dataset through data cleaning, visualize relationships within the data, and develop accurate predictive models.

## Key Features

- **Data Cleaning**: Applied various data cleaning techniques to reduce noise and improve the overall quality of the dataset.
- **Data Visualization**: Generated over 5 diagrams to identify and visualize key relationships within the data.
- **Predictive Modeling**: Developed multiple regression models to predict the number of death cases, achieving an accuracy rate of 92%.

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Data Cleaning](#data-cleaning)
- [Data Visualization](#data-visualization)
- [Predictive Modeling](#predictive-modeling)
- [Installation and Usage](#installation-and-usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Data Cleaning

The COVID-19 dataset initially contained several inconsistencies and missing values. To enhance the data quality:

- Missing values were handled using imputation techniques.
- Outliers were detected and treated.
- Data was normalized to ensure consistency across various metrics.

These steps significantly reduced noise in the dataset, making it more reliable for further analysis.

## Data Visualization

Data visualization played a crucial role in understanding the trends and relationships within the COVID-19 dataset. The following diagrams were created:

1. **Scatter Plot**: To observe the relationship between confirmed cases and deaths.
2. **Line Chart**: Showing the trend of confirmed cases and deaths over time.
3. **Bar Chart**: Comparing death cases across different regions.
4. **Heatmap**: Displaying the correlation between various features in the dataset.
5. **Box Plot**: To detect and visualize outliers in the data.

These visualizations helped in formulating hypotheses and guided the development of predictive models.

## Predictive Modeling

The core of this project is the development of regression models to predict COVID-19 death cases. The models were evaluated based on their accuracy, with the final model achieving a 92% accuracy rate. The steps involved in model development include:

- Feature selection and engineering.
- Splitting the data into training and testing sets.
- Training multiple regression models and selecting the best-performing model.
- Evaluating the model's performance using various metrics.

## Installation and Usage

To replicate this project, follow the steps below:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/COVID19-Data-Analysis-Prediction.git
    ```
2. **Install Required Packages**:
    Ensure you have R and RStudio installed. Then, install the necessary R packages using:
    ```R
    install.packages(c("ggplot2", "dplyr", "caret", "randomForest"))
    ```
3. **Run the Analysis**:
    Open the `FinalProject.Rmd` file in RStudio and knit it to produce the results.

## Project Structure

```bash
COVID19-Data-Analysis-Prediction/
│
├── data/
│   └── covid19_data.csv        # Raw dataset used for analysis
│
├── analysis/
│   ├── data_cleaning.R         # Script for data cleaning
│   ├── data_visualization.R    # Script for data visualization
│   └── modeling.R              # Script for predictive modeling
│
├── results/
│   └── predictions.csv         # Final predictions of the model
│
└── FinalProject.Rmd            # R Markdown file for the entire project
```


## Results

The final predictive model achieved a 92% accuracy rate in predicting COVID-19 death cases. The insights from the visualizations and the model can be used to understand the factors influencing death rates and to make data-driven decisions.

## Contributors

- **Joel Nithish Kumar M** - [LinkedIn](www.linkedin.com/in/joel-nithish-kumar-m-714a75174)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

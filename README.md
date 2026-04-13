# Skilled Birth Attendance Model

## Project Overview
This project aims to develop a predictive model for skilled birth attendance using the Kenya Demographic and Health Survey (DHS) 2022 data. Skilled birth attendance is pivotal for improving maternal and child health outcomes, and this model seeks to identify factors influencing attendance at skilled births.

## Dataset

- **Source**: Kenya Demographic and Health Survey (DHS) 2022 - Individual Recode (IR) file
- **File**: KEIR8CFL.DTA
- **Sample**: Women of reproductive age (15-49 years) in Kenya
- 
### Variables Used

**Target Variable:**

- `m15_1`: Place of delivery (most recent birth)

**Skilled Attendant Indicators:**

- Doctor, nurse, midwife, or auxiliary midwife assistance

**Features:**

- Demographic: Age, education level, region, residence type (urban/rural)
- Socioeconomic: Wealth index, parity (total children ever born)
- Healthcare Access: Antenatal care visits, distance to health facility
- Media Exposure: Newspaper, radio, television, internet usage

## Project Structure

- `Untitled-1.ipynb` - Main analysis and model development notebook
- `README.md` - Project documentation

## Objectives
- To understand the trends and factors affecting skilled birth attendance in Kenya.
- To develop a predictive model that can be used to forecast attendance rates based on various input parameters.
- To provide insights and recommendations that could help improve skilled birth attendance in underserved areas.

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the DHS data for analysis.
2. **Exploratory Data Analysis (EDA)**: Analyzing the data to identify trends and correlations.
3. **Model Development**: Using statistical and machine learning techniques to develop the predictive model.
4. **Validation**: Ensuring the model’s accuracy and reliability using validation data sets.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn for visualization


## Usage

 1. Open `sanga.ipynb` in Jupyter Notebook or JupyterLab
 2. Ensure the DHS data file is in the project directory
 3. Run cells sequentially to:
    - Extract and load the dataset
    - Explore data distributions and patterns
    - Preprocess and engineer features
    - Train and evaluate the prediction model
    - Visualize results and model performance
  
## Author

Kelvin Kipkosgei

# ClimateWins: Machine Learning for Climate Change Predictions

## Project Summary
ClimateWins is a European nonprofit focused on analyzing weather data to predict how climate change may evolve over time. Leveraging machine learning techniques—like K-Nearest Neighbors (KNN), Random Forests, and Neural Networks—we aim to:
- Identify and forecast unusual weather patterns.
- Examine how these patterns might shift over the coming decades.
- Provide insights into future climate scenarios to support risk mitigation and policy planning.

## Data Source
- **European Historical Weather Data (ECA&D)**  
  - Timeframe: Late 1800s to 2022  
  - Daily temperature (mean, min, max), wind speed, snowfall, and more  
- **Additional Datasets (from Kaggle and proprietary sources)**  
  - Includes weather-condition images, handwritten digit images (MNIST), and labeled “pleasant vs. unpleasant” day data  
- **Format**: Primarily CSV files and images for deep learning tasks  

## Folders

### 01_Project_Management
Contains briefs, documentation, and planning materials.

### 02_Data
- **Original Data**: Raw historical weather observations and metadata.  
- **Prepared Data**: Cleaned and engineered datasets ready for modeling.

### 03_Scripts
Python scripts and Jupyter notebooks covering data exploration, model training (KNN, CNN, RNN, etc.), and evaluation.

### 04_Analysis
Visualizations, metrics, and comparative results (accuracy, loss, confusion matrices) for the various predictive models.

### 05_Presentation
Summarized findings and recommendations in presentation slides.

## Python Libraries

- **Pandas** & **NumPy**: Data manipulation, analysis, and numerical computations  
- **Matplotlib**, **Seaborn**, & **Plotly**: Statistical and interactive visualizations  
- **OS** & **Calendar**: Handling file paths and date-based calculations  
- **Scikit-learn**: KNN, Decision Trees, Random Forest, and performance metrics  
- **TensorFlow/PyTorch** (or similar): Building CNNs for image classification and RNNs for time-series predictions  
- **Scipy**: Scientific computing and advanced statistical operations  

## Tableau Visualization
Explore additional interactive charts and dashboards in Tableau:  
[ClimateWins Tableau](https://public.tableau.com/app/profile/isaac.contreras/viz/ClimateWins-Inter-Tableau/Story1)

## Disclaimer
All insights are derived from historical datasets and machine learning models, which include inherent uncertainty. These findings should be supplemented with expert analysis and not be the sole basis for critical policy or business decisions.

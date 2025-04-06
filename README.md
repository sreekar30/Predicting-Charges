# PredictingCharges

This project aims to predict individual medical insurance charges using regression techniques based on demographic and health-related features. It involves data analysis, feature engineering, and the application of machine learning models to deliver accurate predictions and insights.

## Project Objective

To build a regression model that can accurately estimate medical insurance charges based on features such as:

- Age
- Gender
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region

## Tools and Technologies

- **Languages:** Python
- **Libraries:**  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  

## 📊 Workflow

1. **Data Exploration & Cleaning**
   - Handled missing values and checked data types
   - Performed summary statistics and initial visualizations

2. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions
   - Used heatmaps and pairplots to understand relationships between variables

3. **Feature Engineering**
   - Encoded categorical variables (e.g., `smoker`, `region`)
   - Normalized/standardized numerical values where necessary

4. **Model Building**
   - Applied Linear Regression as the primary model
   - Split data into training and testing sets
   - Evaluated performance using R² Score and Mean Absolute Error (MAE)

5. **Visualization of Predictions**
   - Plotted predicted vs actual values
   - Highlighted key influential features using regression coefficients

## Results

- Linear Regression model provided strong predictive performance.
- Smoking status and BMI were identified as key predictors of insurance charges.
- Clear and interpretable insights from visualizations and model output.


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PredictingCharges.git
   ```
2. Navigate to the project folder:
   ```bash
   cd PredictingCharges
   ```
3. (Optional) Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook in Jupyter:
   ```bash
   jupyter notebook PredictingCharges.ipynb
   ```


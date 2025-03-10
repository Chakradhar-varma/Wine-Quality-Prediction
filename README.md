# Wine Quality Prediction

## Overview
This project aims to predict the quality of wine using machine learning techniques. The dataset contains various physicochemical properties of wine, which serve as features to build predictive models.

## Dataset
The dataset used in this project contains information about different wines, including attributes such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Dependencies
To run this notebook, you need the following libraries:
- Python (>=3.7)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Install dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Workflow
1. **Data Loading:** Import and inspect the dataset.
2. **Exploratory Data Analysis (EDA):** Visualize distributions and relationships between features.
3. **Data Preprocessing:** Handle missing values, normalize features, and encode categorical variables if needed.
4. **Model Training:** Implement machine learning models such as:
   - Linear Regression
   - Decision Trees
   - Random Forest
   - Support Vector Machine (SVM)
5. **Model Evaluation:** Compare performance using metrics like RMSE, R² score, and accuracy.
6. **Predictions & Insights:** Use the trained model to predict wine quality and derive conclusions.

## Usage
Run the Jupyter Notebook file:
```bash
jupyter notebook Wine_Quality_Prediction.ipynb
```

## Results
The best-performing model provides insights into which features most influence wine quality. The model's accuracy and feature importance are visualized for further analysis.

## Author
Developed as part of a data science project. Contributions and suggestions are welcome!

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit pull requests with improvements.

## License
This project is open-source and available under the MIT License.

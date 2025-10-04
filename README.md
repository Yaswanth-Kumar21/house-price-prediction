# House Price Prediction

**Goal:** Predict house prices using machine learning based on features like size, rooms, age, and location.

**Dataset:** `housing.csv` (features: size_sqft, num_rooms, age, price)

**Project Includes:**
- Data preprocessing & encoding
- Exploratory Data Analysis (plots & heatmaps)
- Model training using scikit-learn
- Model evaluation: MAE, MSE, RMSE, R²
- Saved model: `house_price_model.joblib`

**How to Run:**
```bash
# Clone repo
git clone https://github.com/Yaswanth-Kumar21/house-price-prediction.git

# Create environment
conda env create -f environment.yml
conda activate <env_name>

# Open notebook
jupyter notebook Ml_project.ipynb

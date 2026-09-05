# Ford Car Price Prediction - ML Model

## Models Built
- **Linear Regression:** R² = 0.7366, RMSE = £2,429.73
- **Random Forest:** R² = 0.9337, RMSE = £1,219.28 ✓ BEST

## Dataset
- 17,966 Ford vehicles
- 17 features (year, mileage, tax, MPG, engine size, model, transmission, fuel type)

## Key Features (Importance)
1. Year (most important)
2. Engine size
3. Model type
4. Mileage
5. MPG

## Results
**Random Forest model: 93.4% accurate**
- Predictions off by ~£1,219 on average
- Best model for Ford price prediction

## Technologies
- Python, Scikit-Learn, Pandas, Matplotlib, Seaborn
- Google Colab

## Files
- ford_price_prediction.ipynb - Complete ML code & analysis
- ford_price_model.pkl - Trained Random Forest model
- ford.csv - Dataset (17,966 records)

# Housing-Market-Analyzer

A Machine Learning project that predicts apartment prices in Bucharest using Linear Regression based on real-world housing data.

---

## Project Overview

This project aims to estimate the price of apartments in Bucharest by analyzing various features such as:
- number of rooms
- surface area
- floor and total floors
- location (sector)
- overall score

The model is built using **Linear Regression**, making it simple, interpretable, and aligned with fundamental machine learning concepts.

---

## Dataset

The dataset contains real estate data with the following features:

| Feature | Description |
|--------|------------|
| rooms | Number of rooms |
| area | Surface area (m²) |
| floor | Floor number |
| total_floors | Total floors in the building |
| sector | Bucharest sector (1–6) |
| score | Property rating |
| price | Target variable (apartment price) |

---

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- scikit-learn

---

## Machine Learning Approach

The project follows a standard ML pipeline:

1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering  
4. Train-test split  
5. Feature scaling  
6. Model training using Linear Regression  
7. Model evaluation  

---

## Model Evaluation

The model is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Visualization

The project includes:

- Feature correlation with price
- Actual vs Predicted price scatter plot

---

##  Key Insights

- Apartment surface area has the strongest impact on price  
- The number of rooms also significantly influences price  
- Floor and building height have a smaller effect  

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/bucharest-house-price-prediction.git
cd bucharest-house-price-prediction
```

2. Install the dependencies:
```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:
```bash
jupyter notebook
```

4. Open and run:
```bash
analysis.ipynb
```

---

## Project Structure
```bash
bucharest-house-price-prediction/
│
├── data/
│   └── Bucharest_HousePriceDataset.csv
│
├── notebook/
│   └── bucharest_house_price_prediction.ipynb
│
├── README.md
└── requirements.txt
```

## Example Prediction
Predicted price: ~120000

# California Housing Price Prediction using ANN

This project implements an **Artificial Neural Network (ANN)** to predict house prices in California based on the features of the houses. The dataset used is the **California Housing dataset** from `scikit-learn`.

---

## 🏠 Dataset

- **Source:** `sklearn.datasets.fetch_california_housing`
- **Number of features:** 8 numeric features
- **Target:** Median house value in units of 100,000 USD
- **Features include:**
  - MedInc: median income in block
  - HouseAge: median house age
  - AveRooms: average number of rooms
  - AveBedrms: average number of bedrooms
  - Population: block population
  - AveOccup: average occupancy
  - Latitude: house block latitude
  - Longitude: house block longitude

---

## 🧠 Model Architecture

- **Input layer:** 8 neurons (corresponding to 8 features)
- **Hidden layer 1:** 64 neurons, ReLU activation
- **Hidden layer 2:** 32 neurons, ReLU activation
- **Output layer:** 1 neuron, linear activation (regression output)

**Loss function:** Mean Squared Error (MSE)  
**Metric:** Mean Absolute Error (MAE)

---

## 📈 Model Performance

- **Test MSE:** 0.276  
- **Example prediction:**
   - Actual:0.477, predicted: 0.331

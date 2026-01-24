# House Price Prediction: Ensemble Methods vs Deep Learning

**Course:** Generative AI and Data Science Pathway - Intermediate Level  
**Module:** Module 1 - Advanced Machine Learning Techniques  
**Student:** Obasi-Uzoma Blessing  
**Date:** January 2026

---

##  Project Objective

This project compares the predictive performance of traditional ensemble methods (Bagging and Boosting) against modern deep learning approaches (Multi-Layer Perceptron) for house price prediction.

##  Dataset

- **Source:** [House Price Prediction Challenge - Kaggle](https://www.kaggle.com/datasets/anmolkumar/house-price-prediction-challenge)
- **Size:** 29,451 training samples
- **Features:** 12 variables including location, size, amenities
- **Target:** House prices in Lacs (Indian currency)

##  Technologies Used

- **Python 3.10+**
- **Libraries:**
  - scikit-learn (Machine Learning)
  - pandas & numpy (Data Processing)
  - matplotlib & seaborn (Visualization)
  - kagglehub (Dataset Download)

##  Models Implemented

### 1. Ensemble Methods
- **Random Forest (Bagging):** R² Score: 0.7436
- **Gradient Boosting (Boosting):** R² Score: 0.7774  Best

### 2. Deep Learning
- **Multi-Layer Perceptron:** R² Score: 0.5656
  - Architecture: 2 hidden layers (64, 32 neurons)
  - Activation: ReLU
  - Optimizer: Adam

##  Key Findings

1. **Gradient Boosting** achieved the best performance with lowest RMSE (348.29)
2. **Ensemble methods** outperformed deep learning on this tabular dataset
3. **Top predictive features:** Square footage, Longitude, Latitude
4. **Neural networks** showed promise but require further optimization

##  How to Run

### Option 1: Google Colab (Recommended for Quick View)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Code-blize/house-price-prediction-ml/blob/main/Obasi_Uzoma%20B.%20Module%201.ipynb).

### Option 2: Local Setup
```bash
# Clone repository
git clone https://github.com/obasi/house-price-prediction-ml.git
cd house-price-prediction-ml

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Obasi-Uzoma B. Module_1.ipynb
```

## 📊 Results Visualization

### Model Performance Comparison
![Model Comparison](<img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/5877f51a-fad4-4153-b853-a9cae878de48" />
)

### Feature Importance Analysis
![Feature Importance](<img width="903" height="790" alt="download" src="https://github.com/user-attachments/assets/794d3edb-c92e-4885-83f7-56dfb86934d3" />
)

##  Conclusion

This project successfully demonstrates:
- Implementation of multiple advanced ML paradigms
- Comparative analysis of ensemble vs deep learning approaches
- Practical application on real-world regression task
- Professional data science workflow

**Key Takeaway:** For tabular data, ensemble methods (particularly Gradient Boosting) often outperform deep learning, confirming industry best practices.

##  Future Improvements

- [ ] Implement hyperparameter optimization (GridSearchCV)
- [ ] Add cross-validation for robust evaluation
- [ ] Explore XGBoost and LightGBM
- [ ] Feature engineering for interaction terms
- [ ] Deploy model as web application

##  License

This project is part of academic coursework. Feel free to reference with proper attribution.

##  Acknowledgments

- Dataset: Anmol Kumar (Kaggle)
- Course: Generative AI and Data Science Pathway
- Institution: Flexisaf Edusoft

---

**Contact:** On my profile

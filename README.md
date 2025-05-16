# Big Mart Sales Prediction

This project predicts product sales at Big Mart outlets using regression models. It demonstrates the end-to-end application of data preprocessing, exploratory data analysis, feature engineering, and machine learning using Python.

---

## 📦 Dataset

- [Big Mart Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/akashdeepkuila/big-mart-sales?select=Train-Set.csv)

---

## 📊 Project Workflow

1. **Data Preprocessing**
   - Handled missing values in `Item_Weight` and `Outlet_Size`
   - Normalized inconsistent labels (e.g., "low fat", "LF", etc.)

2. **Exploratory Data Analysis (EDA)**
   - Visualized sales by item type, outlet type, and location
   - Examined distributions and correlations

3. **Feature Engineering**
   - Created new features:
     - `Outlet_Years`: Time since establishment
     - `Item_Visibility_Avg`: Adjusted for 0 values

4. **Model Building**
   - Models trained:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor

5. **Evaluation**
   - Metrics used:
     - R² Score
     - Root Mean Squared Error (RMSE)

---

## 🛠️ Technologies Used

- Python
- pandas, NumPy
- seaborn, matplotlib
- scikit-learn

---

## 📈 Results

The Random Forest model gave the best performance on the validation set, demonstrating its ability to capture complex patterns in retail sales data.

---

## 🙌 Acknowledgments

Thanks to [Kaggle](https://www.kaggle.com/) for providing the dataset and the data science community for constant support and inspiration.

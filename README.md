# lab-6-Linear-Regression

## 📂 Dataset

The dataset used is **Ecommerce Customers.csv**

### Features:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership

### Target:

* Yearly Amount Spent

---

## ⚙️ Steps Performed

### 1. Load Data

The dataset was loaded into a pandas DataFrame using `read_csv()`.

### 2. Explore Data

* Used `head()` to view first rows
* Used `info()` to check data types
* Used `describe()` to see statistics

### 3. Data Cleaning

* Removed non-numeric column:

  * Avatar (text data not useful for regression)

### 4. Feature Selection

Selected important features:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership

Target variable:

* Yearly Amount Spent

---

### 5. Train-Test Split

The data was split into:

* 70% training
* 30% testing

---

### 6. Model Training

Used **Linear Regression** from sklearn:

* Trained the model using training data

---

### 7. Model Evaluation

#### Coefficients Interpretation:

* Each coefficient shows how much the yearly spending changes when the feature increases by 1 unit.

#### Metrics:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)

---

### 8. Visualization

#### Scatter Plot:

* Shows actual vs predicted values
* Strong linear relationship → model performs well

#### Residual Plot:

* Errors are normally distributed → good model fit

---

## 📈 Results

* The model shows a strong relationship between features and yearly spending
* Predictions are close to actual values
* Errors are relatively small


---

## 💻 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn



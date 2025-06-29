# 🏠 California House Price Prediction

A Machine Learning project to predict housing prices in California using the California Housing Dataset.
The model uses regression techniques to learn from historical data and predict median house values.

---

## 📌 Project Overview

This project aims to:

* Understand the data distribution of California housing.
* Perform data cleaning and feature engineering.
* Build regression models to predict housing prices.
* Evaluate model performance using appropriate metrics.
* Deploy the final model for real-time predictions (optional).

---

## 📊 Dataset

* **Name:** California Housing Dataset
* **Source:** [Scikit-Learn Datasets](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
* **Features:**

  * `MedInc`: Median income in block
  * `HouseAge`: Median house age
  * `AveRooms`: Average rooms per household
  * `AveBedrms`: Average bedrooms per household
  * `Population`: Block population
  * `AveOccup`: Average house occupancy
  * `Latitude`, `Longitude`: Geographical coordinates
* **Target:** `Median House Value` (in \$100,000s)

---

## 🛠️ Tech Stack

* Python 🐍
* NumPy, Pandas, Matplotlib, Seaborn 📊
* Scikit-learn ⚙️
* Jupyter Notebook 📒

---

## 📈 Model Workflow

```
[Load Dataset] → [EDA & Cleaning] → [Feature Engineering] → [Model Training] → [Evaluation] → [Prediction]
```

---

## 📦 Project Structure

```
california-house-price/
│
├── data/                 # Dataset files (optional)
├── notebooks/            # Jupyter Notebooks
├── models/               # Trained models (joblib/pickle)
├── src/                  # Python scripts (if modular)
├── README.md             # Project overview
├── requirements.txt      # Dependencies
└── main.ipynb            # Main notebook
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/california-house-price.git
cd california-house-price
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `main.ipynb` to explore and run the project step-by-step.

---

## 📊 Model Performance

| Model             | RMSE | R² Score |
| ----------------- | ---- | -------- |
| Linear Regression | 0.72 | 0.61     |
| Decision Tree     | 0.56 | 0.78     |
| Random Forest     | 0.49 | 0.85     |

---

## 📌 Future Improvements

* Hyperparameter tuning with GridSearchCV
* Use of pipelines & feature selection
* Deployment with Flask or Streamlit
* Add support for user input via UI

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙇‍♂️ Author

Made with ❤️ by **Alok Tripathi**
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)

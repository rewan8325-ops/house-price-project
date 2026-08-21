Markdown
# 🏡 House Price Prediction Project

An end-to-end Machine Learning project to predict house prices using data cleaning, exploratory data analysis (EDA), model evaluation, and deployment setup.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Joblib, Matplotlib, Seaborn
- **API Backend:** FastAPI
- **Frontend:** React

---

## 📂 Project Structure

```text
house-price-project/
│
├── notebooks/
│   └── house_price_assignment_modified.ipynb   # Complete ML Pipeline & Analysis
│
├── models/
│   └── house_price.pkl                         # Trained ML Model
│
├── .gitignore                                  # Ignored files (data, logs, venv)
└── README.md                                   # Project Documentation
 Dataset & Download Instructions
The raw dataset used for training contains properties features for price estimation.

To use the dataset, download the CSV file and place it in the root directory.

Note: The raw .csv file is excluded from GitHub tracking via .gitignore to keep the repository lightweight.

 Model Metrics
Multiple algorithms were evaluated to find the best performing model. The selected model evaluation metrics:

MAE (Mean Absolute Error): Evaluated in Notebook

RMSE (Root Mean Squared Error): Evaluated in Notebook

R² Score: Evaluated in Notebook

 Setup & Execution
Running the Notebook
Open Google Colab or Jupyter Notebook.

Load notebooks/house_price_assignment_modified.ipynb.

Execute all cells from top to bottom.

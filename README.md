# 🌸 Iris Flower Classification

A Machine Learning project that classifies Iris flowers into three species—**Setosa**, **Versicolor**, and **Virginica**—using their physical measurements.

## 📌 Project Overview

This project demonstrates the complete Machine Learning workflow:

- Data Loading
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Model Training
- Model Evaluation
- Prediction on New Data

The model predicts the species of an Iris flower based on:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 📂 Project Structure

```
├── Iris_Flower_Classification.ipynb   # Jupyter Notebook
├── Iris.csv                           # Dataset
├── README.md                          # Project Documentation
```

---

## 📊 Dataset

The dataset contains **150 flower samples** divided into three classes.

| Species | Samples |
|---------|---------|
| Setosa | 50 |
| Versicolor | 50 |
| Virginica | 50 |

### Features

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target

- Species

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Machine Learning Workflow

### 1. Import Libraries

Import all required Python libraries.

### 2. Load Dataset

Read the Iris dataset using Pandas.

### 3. Data Exploration

- View dataset
- Check missing values
- Data information
- Statistical summary

### 4. Data Visualization

- Pair Plot
- Heatmap
- Feature Distribution

### 5. Data Preprocessing

- Split Features and Target
- Train-Test Split
- Feature Scaling using StandardScaler

### 6. Model Training

Train a Machine Learning classification model.

### 7. Model Evaluation

Evaluate the model using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### 8. Prediction

Predict the species of new flower samples.

---

## 📈 Results

The trained model achieves high classification accuracy on the Iris dataset.

Evaluation metrics include:

- Accuracy Score
- Precision
- Recall
- F1-Score

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/iris-flower-classification.git
```

### Open project

```bash
cd iris-flower-classification
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Iris_Flower_Classification.ipynb
```

Run all cells.

---

## 📷 Sample Prediction

```python
sample = [[5.1, 3.5, 1.4, 0.2]]

prediction = model.predict(sample)

print(prediction)
```

Output

```
Setosa
```

---

## 📚 Learning Outcomes

This project demonstrates:

- Data preprocessing
- Feature engineering
- Data visualization
- Feature scaling
- Machine Learning model training
- Model evaluation
- Making predictions

---

## 🚀 Future Improvements

- Deploy using Flask or Streamlit
- Build a web interface
- Hyperparameter tuning
- Compare multiple ML algorithms
- Save and load trained model with Pickle

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Varun Sharma**

**INTERN ID-CITS5710**

If you found this project helpful, don't forget to ⭐ the repository!

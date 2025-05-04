# 🚢 Titanic Survival Prediction Project

This project applies multiple machine learning algorithms to predict passenger survival on the Titanic. It includes exploratory data analysis (EDA), data preprocessing, model training, evaluation, and visualization.

---

## 📁 Project Structure

```
├── Data/
│   ├── original/              → Contains the original dataset (`train.csv`)
│   ├── preprocessed/          → Cleaned and split features: `X.csv`, `X_test.csv`, `Y.csv`, `Y_test.csv`
│   ├── Results/               → Prediction CSVs from all models + accuracy comparison

├── Logistic_Regression/       → Model script, report image, predictions
├── Decision_Tree/
├── Random_Forest/
├── Naive_Bayes/
├── Support_Vector_Machine/
├── K_Nearest_Neighbors/

├── model_accuracy_summary.csv     → Table comparing all model accuracies
├── model_accuracy_comparison.png → Bar chart comparing model performance

📄 your_code.ipynb                 → Main notebook that runs all models
📄 report.pdf                      → Written report answering all project questions
```

---

## 🧪 How to Run

1. Open `your_code.ipynb` in **Jupyter Notebook** or **VS Code**.
2. Run all cells in sequence.
3. Check the `Data/Results/` folder for model predictions.
4. Visit each model’s folder for detailed outputs, confusion matrices, and heatmaps.

---

## 📊 Algorithms Used

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Naive Bayes  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

---

## 🥇 Best Performing Model

**Random Forest** achieved the highest accuracy thanks to its ensemble nature and ability to model non-linear feature interactions.

---

## 📌 Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyterlab or notebook

Install all requirements via:

```bash
pip install -r requirements.txt
```

*(If not present, generate using `pip freeze > requirements.txt`)*

---

## 👤 Author

**Alhassan Abdulmonam**

---

## 📄 License

This project is open-source and available under the MIT License.

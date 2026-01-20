# Feature-encoding
This project demonstrates feature encoding and scaling using the Adult Income Dataset. The goal is to preprocess raw data into a machine‑learning‑ready format by handling categorical and numerical features appropriately.



# Task 4: Feature Encoding & Scaling

## 📌 Overview
This project is part of the AI & ML Internship (Ministry of MSME, Govt. of India).  
The objective is to preprocess the **Adult Income Dataset** by encoding categorical features and scaling numerical features, ensuring the dataset is ready for machine learning models.

---

## 🛠 Tools Used
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Google Colab (for execution)
- GitHub (for submission)

---

## 📂 Dataset
- **Adult Income Dataset** (UCI Repository / Kaggle version)
- Contains demographic and income-related attributes.

---

## 🔎 Steps Performed
1. **Data Loading**  
   Imported dataset into Pandas DataFrame.

2. **Feature Identification**  
   - Numerical: `age`, `fnlwgt`, `educational-num`, `capital-gain`, `capital-loss`, `hours-per-week`  
   - Categorical: `workclass`, `education`, `marital-status`, `occupation`, `relationship`, `race`, `gender`, `native-country`

3. **Encoding**  
   - Label Encoding for `education` (ordered categories).  
   - One-Hot Encoding for unordered categorical features.

4. **Scaling**  
   - Applied `StandardScaler` to numerical features.  
   - Verified distributions before and after scaling.

5. **Visualization**  
   - Plotted histograms to compare feature distributions.

6. **Saving Output**  
   - Exported preprocessed dataset as `adult_preprocessed.csv`.

---

## 📊 Results
- Dataset transformed into ML-ready format.  
- All categorical features encoded.  
- Numerical features standardized.  
- Clear demonstration of scaling impact on feature distributions.

---

## 📌 Submission
- Notebook: `task4.ipynb`  
- Processed Dataset: `adult_preprocessed.csv`  
- README.md (this file)  

# Sampling Techniques on Imbalanced Dataset

##  Assignment Overview
This project focuses on understanding the impact of different **sampling techniques** on **imbalanced datasets** and how these techniques affect the performance of various **machine learning models**.

The dataset used is a highly imbalanced **credit card dataset**, where the goal is to balance the data, apply multiple sampling strategies, and evaluate model accuracy.

---

##  Objectives
- Handle class imbalance using different sampling techniques  
- Create balanced samples from the dataset  
- Apply multiple ML models on each sample  
- Compare model performance across sampling methods  
- Identify the best sampling technique for each model  

---

##  Dataset
- **Source:** Credit Card Dataset  
- **Link:**  
  https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv  

---

##  Tasks Performed
1. Loaded and analyzed the imbalanced dataset  
2. Converted the dataset into a balanced class dataset  
3. Created **five different samples**  
4. Applied **five sampling techniques**:
   - Sampling1  
   - Sampling2  
   - Sampling3  
   - Sampling4  
   - Sampling5  

5. Trained **five machine learning models**:
   - M1  
   - M2  
   - M3  
   - M4  
   - M5  

6. Evaluated accuracy for each (Sampling, Model) pair  
7. Compared results to find the best sampling technique per model  

---

##  Accuracy Results

| Model | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|------|-----------|-----------|-----------|-----------|-----------|
| M1 | 50.10 | 52.24 | 63.18 | 69.23 | 70.12 |
| M2 | 59.25 | 65.27 | 68.72 | 28.36 | 30.25 |
| M3 | 90.45 | 72.41 | 32.17 | 42.58 | 41.85 |
| M4 | 78.25 | 56.24 | 47.23 | 33.44 | 40.12 |
| M5 | 81.25 | 12.85 | 57.36 | 32.25 | 52.74 |

---
##  Key Observations
- Different models respond differently to sampling techniques  
- No single sampling method is best for all models  
- Proper sampling significantly improves model accuracy on imbalanced data  

---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Imbalanced-learn  

---

##  Repository Structure
├── Creditcard_data.csv
├── sampling.ipynb
├── README.md


---

##  Conclusion
This project demonstrates the importance of selecting appropriate sampling techniques when dealing with imbalanced datasets. The choice of sampling strategy can greatly influence the performance of machine learning models.

---

## Author
**Mukul Ghai**

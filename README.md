# 🌊 WaterMetal Analyzer – Heavy Metal Risk Assessment

WaterMetal Analyzer is an end-to-end environmental analytics system designed to assess heavy metal contamination in water and sediment samples.  
It transforms raw laboratory data into actionable ecological risk insights using scientifically accepted methods.

---

## 🎯 Problem Statement

Environmental heavy metal datasets are complex and difficult to interpret without expert knowledge.  
Manual analysis of contamination, pollution sources, and ecological risk is time-consuming and error-prone.

This project automates the entire workflow:
- Data ingestion
- Risk computation
- Pattern discovery
- Hotspot detection
- Report generation

---

## 🧠 Methodology & Models Used

### ✔ Unsupervised Machine Learning
- **Principal Component Analysis (PCA)**  
  Used to reduce dimensionality and identify dominant pollution patterns.

### ✔ Risk-Based Classification
- **Potential Ecological Risk Index (PERI)**  
  Combines metal concentration, toxicity, and background values to classify ecological risk.

### ✔ Statistical Analysis
- Pearson Correlation for metal co-occurrence and source identification.

---

## 🧩 System Workflow

1. Upload Excel / CSV dataset
2. Data verification & preprocessing
3. PERI computation
4. PCA-based pattern extraction
5. Hotspot detection
6. Visualization (charts & graphs)
7. Automated report generation
8. Download & export (PDF, Word, Excel)

---

## 🖥️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python  
- **Libraries:**  
  - Pandas, NumPy  
  - Scikit-learn  
  - Matplotlib  
  - python-docx  
  - reportlab  
- **AI (Optional):** OpenAI API for natural language explanation

---

## 📊 Features

- Upload Excel / CSV datasets
- Ecological risk scoring (PERI)
- Pollution pattern analysis (PCA)
- Hotspot identification
- Metal-wise risk contribution
- AI-based explanation of results
- Multi-format report export (PDF, Word, Excel)

---

## 🚀 How to Run the Project

```bash
# Activate virtual environment
.venv\Scripts\activate

# Run the application
streamlit run app.py

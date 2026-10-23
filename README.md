# 📊 Egyptian High School Students Name Analysis (920,000+ Records)

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=flat)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An in-depth demographic, statistical, and linguistic analysis of over **920,000 Egyptian final-year high school students (Thanaweya Amma)**. This project investigates name distributions, naming conventions, gender-based trends, paternal lineage patterns, and unique name frequencies across Egypt.

---

## 📌 Project Overview

Understanding naming trends offers valuable cultural and sociodemographic insights. Using Python and high-performance data manipulation libraries, this repository analyzes:
- **Total Population**: Over 920,000 individual student records.
- **Top Overall Names**: The most common first names across Egypt with exact frequency counts and percentages.
- **Gender-Specific Trends**: Breakdown of the top 10 most popular male names and top 10 female names.
- **Combined Comparisons**: Side-by-side frequency analysis of the top 20 male and female names.
- **Paternal Name Lineage**: Analysis of the most frequent father names (`arabic_name3`).
- **Unique Names Identification**: Isolation and export of rare names appearing only once in the entire dataset.

---

## 📈 Visualizations & Key Findings

### 1. Top 10 Names Overall
Frequency distribution and overall population percentage of Egypt's most popular student names.

![Top 10 Overall](Top%20ten%20overall.png)

---

### 2. Top 20 Male & Female Names Comparison
Direct side-by-side volume comparison of the most prominent male and female names.

![Top 20 Males and Females](top%20twenty%20males%20and%20females.png)

---

### 3. Top 10 Male Names
Detailed frequency count and proportion of top male names (*e.g., محمد, أحمد, محمود, عمر, علي, عبدالرحمن, زياد, يوسف, مصطفى, عبدالله*).

![Top 10 Male Names](top%20ten%20males.png)

---

### 4. Top 10 Female Names
Detailed frequency count and proportion of top female names (*e.g., مريم, فاطمة, ندى, منة, شهد, بسملة, ملك, جنى, سلمى, حبيبة*).

![Top 10 Female Names](top%20ten%20females.png)

---

### 5. Top 10 Father Names
Distribution of paternal names, reflecting naming conventions across generations in Egyptian families.

![Top 10 Father Names](top%20ten%20fathers%20names.png)

---

## 📁 Repository Structure

```text
├── Name_Analysis.ipynb                  # Jupyter Notebook with full EDA, cleaning, and visualizations
├── New Microsoft Excel Worksheet.xlsx   # Main dataset (920k+ student records)
├── Unique Names.xlsx                    # Exported list of rare/single-occurrence names
├── Top ten overall.png                  # Chart: Top 10 names overall
├── top ten males.png                    # Chart: Top 10 male names
├── top ten females.png                  # Chart: Top 10 female names
├── top twenty males and females.png     # Chart: Combined top 20 names
├── top ten fathers names.png            # Chart: Top 10 father names
├── .gitignore                           # Git ignore rules for Python / Jupyter
└── README.md                            # Project documentation
```

---

## 🛠️ Technology Stack & Libraries

- **Language:** Python 3
- **Data Manipulation:** [Pandas](https://pandas.pydata.org/)
- **Data Visualization:** [Matplotlib](https://matplotlib.org/)
- **Arabic Text Rendering:**
  - [`arabic-reshaper`](https://github.com/mpcabd/python-arabic-reshaper): Correctly handles Arabic ligature shaping.
  - [`python-bidi`](https://github.com/MeirKriheli/python-bidi): Formats bidirectional text (Right-to-Left) for Matplotlib graphs.
- **Spreadsheet Processing:** [OpenPyXL](https://openpyxl.readthedocs.io/)

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/moatasimyakoub92-dot/Name-Analysis.git
   cd Name-Analysis
   ```

2. **Install required dependencies:**
   ```bash
   pip install pandas matplotlib arabic_reshaper python-bidi openpyxl
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook Name_Analysis.ipynb
   ```

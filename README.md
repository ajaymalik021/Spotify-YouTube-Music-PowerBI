# Spotify & YouTube Music Dataset Cleaning and Preparation  

This project focuses on cleaning and preparing a music dataset containing information from Spotify and YouTube Music. The goal is to transform the dataset into a clean, structured, and analysis-ready format by addressing missing values, inconsistencies, and irrelevant data.  

---
Dataset Link - https://drive.google.com/file/d/1qanyuwEzkwEJ73vDJHk4ZlWE0JUG7udb/view
---
## 📋 **Objectives**  

### **1. Identify and Handle Missing Values**  
- Examine the dataset for missing values in all columns.  
- Handle missing values in `Views` and `Likes` by filling with averages, default values, or removing them based on context.  

---

### **2. Fix Irregularities in Merged Columns**  
- Split `Spotify_Info` and `Youtube_Info` columns into their original components.  
- Remove unnecessary delimiters, prefixes, and suffixes.  

---

### **3. Correct Case Sensitivity and Naming Conventions**  
- Standardize column names to lowercase with underscores for consistency.  
- Ensure uniform formatting for entries in `Artist` and `Track` columns.  

---

### **4. Remove or Handle Irrelevant Columns**  
- Identify and remove columns with little or no analytical value.  
- Clean irrelevant or random entries within relevant columns.  

---

### **5. Handle Inconsistent Data Types**  
- Convert text-formatted numeric columns (e.g., `Danceability`, `Energy`) to numeric format.  
- Handle anomalies and non-numeric values during the conversion process.  

---

### **6. Address and Fix Invalid Data Entries**  
- Replace invalid entries in the `Views` column (e.g., "invalid_data").  
- Ensure all entries in the `Album` column are correctly labeled and free of irrelevant data.  

---

### **7. Check for and Remove Duplicate Rows**  
- Identify and remove duplicate rows to maintain dataset uniqueness and accuracy.  

---

### **8. Reorder and Rename Columns for Clarity**  
- Reorder columns logically to improve readability and usability.  
- Rename columns where necessary for clarity.  

---

## 🛠 **Tools and Techniques**  
- **Tools Used:**  
  - Microsoft Excel  
  - Python (Pandas, NumPy)  
- **Techniques:**  
  - Data Cleaning  
  - Data Standardization  
  - Handling Missing Values  
  - Advanced Data Manipulation  

---

## 📊 **Outcome**  
- A fully cleaned and structured dataset ready for analysis.  
- Improved data consistency and usability for deriving insights into music trends and audience behavior.  

---

## 🚀 **Getting Started**  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/username/spotify-youtube-music-cleaning.git

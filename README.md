Here's a polished and visually appealing version of your README with team member credits added at the top, improved formatting, and better visual hierarchy throughout:

---

# 🧠 Enterprise Software Products Dataset Project


![Project Screenshot](https://github.com/user-attachments/assets/f4ced77c-1fe6-4772-971d-6f2bd462ddd9)

---

## 📌 Project Overview

This project develops an NLP-based classification model to categorize enterprise software products into predefined categories and subcategories based on their descriptions. The dataset, curated by enterprise technology experts, enables improved taxonomy classification and deeper insights into enterprise software products.

---

### 👥 Team Members

* **Viswa Kotra**
* **Vera Dureke**
* **Nancy Chen**
* **Julia Ding**
* **Saman Fatima**

---

## 🎯 Objectives and Goals

* **Main Objective**: Build robust NLP models to categorize software products accurately.
* **Project Goals**:

  * Boost classification accuracy using advanced training techniques.
  * Fine-tune transformer models for more nuanced results.
  * Ensure scalability to handle large, diverse product datasets.

---

## 🔍 Methodology

### 1. **Data Understanding and Preparation**

* Cleaned data by removing duplicates and filling missing values.
* Balanced category distribution to handle underrepresented classes.

### 2. **Exploratory Data Analysis (EDA)**

* Analyzed product category distribution and description lengths.
* Extracted key n-grams and performed TF-IDF keyword analysis.

### 3. **Feature Engineering**

* Tokenized and vectorized descriptions.
* Applied SMOTE to mitigate class imbalance.

### 4. **Model Development**

* Trained XGBoost, multishot learning, and fine-tuned transformer models (e.g., BERT).
* Performed hyperparameter tuning for each model.

### 5. **Evaluation**

* Compared models using metrics like accuracy, precision, recall, and F1-score.

### 6. **Deployment**

* Prepared models for deployment via APIs or cloud services.

---

## 📊 Results and Key Findings

* **Best Model**: Multishot learning reached \~60% accuracy.
* **Insights**:

  * Balanced datasets improved BERT performance.
  * TF-IDF revealed strong differentiators between categories.

---

## 📈 Visualizations (EDA)

* **Product Distribution**: Bar charts of category/subcategory frequencies.
* **Description Length**: Histograms revealing variability.
* **Word Analysis**: Word clouds and top n-gram frequency charts.

---

## 🚀 Next Steps

* Investigate domain-specific transformer models (e.g., RoBERTa).
* Incorporate additional external data sources.
* Deploy final model to production with scalable infrastructure.

---

# 📦 Data Card: Enterprise Software Products Dataset

## 📘 Dataset Description

This dataset contains 1,495 enterprise software products, each categorized into a two-level taxonomy: `category` and `sub-category`. All entries include natural language descriptions, structured for training NLP classification models.

---

## 🧾 Data Files and Structure

### 🔹 `products.csv`

* `product_name`: Name of the software product.
* `vendor_name`: Vendor’s legal name.
* `taxonomy_category`: High-level category.
* `taxonomy_sub_category`: Specific sub-category.
* `product_description`: A high-level overview of product functionality.

### 🔹 `categories.csv`

* `name`: Category name.
* `definition`: One-line definition of the category.

### 🔹 `sub-categories.csv`

* `parent`: The parent category.
* `name`: Sub-category name.
* `definition`: One-line definition of the sub-category.

---

## 🏗️ Dataset Creation & Curation

### ✅ Purpose

Originally compiled by enterprise architects to monitor vendor software used or evaluated within a Fortune 500 company.

### 🧑‍💼 Language Producers

Descriptions authored by enterprise technology experts or extracted from vendor marketing materials.

### 🏷️ Annotation Process

Taxonomy classification and labeling curated manually by internal enterprise technology teams.

---

## ⚖️ Ethical and Practical Considerations

### 🌍 Social Impact

Supports tools that auto-classify enterprise software and reveal product overlaps or redundancy in IT stacks.

### ⚠️ Biases

* Data reflects a single US-based enterprise; geographic and linguistic biases may exist.
* Not all classifications are definitive “ground truth.”

### ❗ Limitations

* Vendor names may not reflect commonly known names.
* Text descriptions and classifications vary in clarity and consistency.
* Some products may not clearly fit into a single taxonomy path.

---

Let me know if you'd like a visual badge section (e.g., built with 🛠️ Python, Transformers, etc.) or tech stack icons added at the top.

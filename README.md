# 🧹 Data Cleaning Workflow

This project follows a professional data cleaning pipeline before performing Exploratory Data Analysis (EDA) and Machine Learning.

## Workflow

1. Load Dataset
2. Initial Inspection
3. Missing Value Handling
4. Duplicate Detection & Removal
5. Wrong Format Detection
6. Inconsistent Label Correction
7. Outlier Detection & Handling
8. Noisy Data Filtering
9. Data Type Consistency Check
10. Schema Validation
11. Data Range Validation
12. Target Class Imbalance Check
13. Save Clean Dataset

---

## Cleaning Steps

### 1. Missing Value Handling
- Detect missing values
- Calculate missing percentage
- Impute missing values using Mean, Median, Mode, or domain-specific values

### 2. Duplicate Detection
- Identify duplicate records
- Remove duplicate rows if necessary

### 3. Wrong Format Detection
- Verify data types
- Convert incorrect formats to appropriate data types

### 4. Inconsistent Labels
- Remove extra spaces
- Standardize text (lowercase/uppercase)
- Correct spelling inconsistencies

### 5. Outlier Detection
- Detect outliers using Boxplots and the IQR method
- Remove or cap outliers only when justified

### 6. Noisy Data Filtering
- Remove impossible or invalid values
- Apply domain-specific validation rules

### 7. Data Type Consistency
- Ensure each column has the correct data type

### 8. Schema Validation
- Verify required columns exist
- Check for unexpected or missing columns

### 9. Data Range Validation
- Validate numeric values based on business rules

### 10. Class Imbalance Check
- Analyze target variable distribution
- Apply balancing techniques (SMOTE, Oversampling, Undersampling) if required

---

## Next Steps

After data cleaning:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning
- Model Evaluation

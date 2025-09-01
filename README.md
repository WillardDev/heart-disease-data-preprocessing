# Heart Disease Data Preprocessing

A comprehensive data preprocessing pipeline for the UCI Heart Disease dataset, featuring exploratory data analysis, missing data imputation, outlier detection, and feature engineering for machine learning applications.

## 📋 Project Overview

This project demonstrates best practices in medical data preprocessing through systematic analysis and preparation of the UCI Riverside Heart Disease dataset. The pipeline transforms raw clinical data into a clean, analysis-ready dataset suitable for various machine learning tasks.

## 🏥 Dataset Information

- **Source**: UCI Machine Learning Repository - Heart Disease Dataset
- **Size**: 282 observations, 16 variables (15 features + 1 target)
- **Domain**: Cardiovascular medicine
- **Target**: Heart disease severity (0-4 scale) with binary classification option

### Features Include:
- **Demographics**: Age, sex
- **Clinical Measurements**: Blood pressure, cholesterol, maximum heart rate
- **Lifestyle Factors**: Smoking history (cigarettes per day, years smoking)
- **Medical History**: Diabetes, family history of heart disease
- **Diagnostic Tests**: Chest pain type, ECG results, exercise-induced angina, thallium stress test

## 🔍 Key Features

### Comprehensive Exploratory Data Analysis
- Statistical summaries and distributions
- Missing data pattern analysis
- Correlation analysis with heatmaps
- Outlier detection using IQR method
- Target variable distribution analysis

### Robust Data Preprocessing
- **Missing Data Handling**: Sophisticated imputation strategy with missing indicators
- **Outlier Management**: Retention with flagging approach for medical validity
- **Feature Engineering**: Risk scores, categorical binning, and derived variables
- **Data Quality Assurance**: Complete validation and consistency checks

### Medical Domain Expertise
- Clinically-informed decision making
- Preservation of medical interpretability
- Evidence-based imputation strategies
- Risk factor validation

## 📁 Repository Structure

```
heart-disease-data-preprocessing/
├── Assignment_Week1.ipynb          # Main Jupyter notebook
├── heart.disease.data.csv         # Original dataset
├── Attributes.csv                 # Feature documentation
├── heart_disease_processed.csv    # Clean, processed dataset
├── README.md                      # This file
└── requirements.txt               # Python dependencies
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/heart-disease-data-preprocessing.git
cd heart-disease-data-preprocessing
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook Assignment_Week1.ipynb
```

## 📊 Processing Pipeline

### 1. Data Loading and Exploration
- Initial data inspection and profiling
- Statistical summaries and data types
- Unique value analysis for categorical variables

### 2. Missing Data Analysis
- Identification of -9 as missing data indicator
- Missing pattern analysis across variables
- Strategic imputation with information preservation

### 3. Outlier Detection and Treatment
- IQR-based outlier identification
- Medical validity assessment
- Flagging strategy for retention

### 4. Feature Engineering
- Binary target variable creation
- Risk score development
- Categorical binning (age groups, cholesterol levels, blood pressure categories)
- Missing data indicators

### 5. Quality Assurance
- Final data validation
- Consistency checks
- Summary statistics verification

## 🧪 Results

The preprocessing pipeline delivers:
- **Zero missing values** through strategic imputation
- **29 features** from original 16 variables
- **282 complete cases** for analysis
- **Preserved medical interpretability** throughout process
- **Ready-to-use dataset** for machine learning applications

### Final Feature Set:
- 15 original clinical features (cleaned and imputed)
- 4 missing data indicators
- 4 outlier detection flags
- 4 engineered features
- 2 target variable options (multi-class and binary)

## 🎯 Use Cases

This processed dataset is suitable for:
- **Binary Classification**: Disease presence prediction
- **Multi-class Classification**: Disease severity assessment
- **Risk Stratification**: Patient risk scoring
- **Feature Selection**: Variable importance studies
- **Model Development**: Baseline for ML algorithms

## 🛠️ Dependencies

```txt
pandas >= 1.3.0
numpy >= 1.21.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
scipy >= 1.7.0
jupyter >= 1.0.0
```

## 📈 Key Insights

- **High missing rates** (>90%) in smoking-related variables handled through domain knowledge
- **Medical outliers retained** due to clinical significance
- **Balanced target distribution** suitable for classification tasks
- **Strong feature correlations** with target variable identified
- **Comprehensive feature set** enables multiple modeling approaches

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Areas for Contribution:
- Additional feature engineering techniques
- Alternative imputation strategies
- Advanced outlier detection methods
- Model implementation examples
- Visualization enhancements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- UCI Machine Learning Repository for providing the dataset
- Cleveland Clinic Foundation for original data collection
- Medical professionals who contributed domain expertise

## 📚 References

1. Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. University of California, Irvine, School of Information and Computer Sciences.
2. Heart Disease Dataset: http://archive.ics.uci.edu/ml/datasets/heart+Disease

## 📞 Contact

For questions or suggestions, please open an issue or contact [your-email@example.com].

---

⭐ **Star this repository if you found it helpful!** ⭐

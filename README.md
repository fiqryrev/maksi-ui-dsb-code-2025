# Data Science for Business - MAKSI FEB UI 2025

Welcome to the official repository for the Data Science for Business practicum course at Program Studi Magister Akuntansi (MAKSI), Fakultas Ekonomi dan Bisnis, Universitas Indonesia.

## 🎯 Course Overview

This repository contains all practicum materials, datasets, and notebooks for hands-on learning of data science applications in business contexts. The course bridges the gap between theoretical knowledge and practical implementation, focusing on real-world business problems in accounting and finance.

**Lecturer**: Yudhistira Dharma Putra  
**Adjunct Co-Lecturer**: Fiqry Revadiansyah  
**Academic Year**: 2025

## 📚 Repository Structure

```
maksi-ui-dsb-2025/
├── syllabus/                    # Course outline and schedule
├── modules/                     # 6 practicum sessions
│   ├── week-02-business-problems-data-solutions/
│   ├── week-04-neural-networks-basics/
│   ├── week-06-regression-timeseries-forecasting/
│   ├── week-09-clustering-segmentation/
│   ├── week-10-dimensionality-anomaly-detection/
│   └── week-12-nlp-financial-text/
├── assignments/                 # Session assignments
├── projects/                    # Midterm and final projects
├── resources/                   # Additional learning materials
└── setup/                       # Environment setup files
```

## 🚀 Getting Started

### Prerequisites
- Python 3.9 or higher
- Git
- Jupyter Lab/Notebook
- 8GB RAM minimum (16GB recommended)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/maksi-ui-dsb-code-2025.git
cd maksi-ui-dsb-code-2025
```

2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r setup/requirements.txt
```

4. **Launch Jupyter Lab**
```bash
jupyter lab
```

## 📖 Learning Modules (6 Practicum Sessions)

### Week 2: Business Problems → Data Solutions
- Translating accounting/finance problems into ML tasks
- Feature engineering from financial statements
- Problem definition with Pandas
- **Reading**: DSB Chapter 2

### Week 4: Neural Networks Basics
- Building feedforward artificial neural networks
- Predicting invoice payment patterns
- Model evaluation and accuracy metrics
- **Reading**: MLDS Chapter 3

### Week 6: Regression & Time-Series Forecasting
- Multiple regression and ARIMA models
- Revenue and cash flow forecasting with Prophet
- MAE/RMSE evaluation
- **Reading**: MLDS Chapter 5

### Week 9: Clustering & Segmentation
- K-means, hierarchical clustering, DBSCAN
- Client and supplier segmentation
- Cluster visualization techniques
- **Reading**: MLDS Chapter 7

### Week 10: Dimensionality Reduction & Anomaly Detection
- PCA for ESG disclosure analysis
- Isolation forests for fraud detection
- Suspicious transaction identification
- **Reading**: MLDS Chapter 8

### Week 12: NLP for Financial Text
- Sentiment analysis of MD&A sections
- ESG disclosure summarization
- Financial text preprocessing
- **Reading**: MLDS Chapter 10

## 💻 Working with Notebooks

Each module contains:
- **notebooks/**: Interactive Jupyter notebooks for practicum
- **data/**: Datasets for hands-on exercises
- **solutions/**: Solution notebooks (released after class)

### Running a Notebook
1. Navigate to the module folder
2. Open the notebook file (`.ipynb`)
3. Run cells sequentially using `Shift + Enter`

## 📝 Assignments

Assignments are due every second Monday at 23:59 WIB. Each assignment folder contains:
- Problem statement (README.md)
- Starter code notebook
- Required datasets
- Submission guidelines

## 🎯 Projects

### Midterm Project (Week 8)
- Individual project on data analysis
- Real business case study
- Presentation required

### Final Project (Week 16)
- Team project (4 members)
- End-to-end data science solution
- Business presentation format

## 📊 Datasets

All datasets are business-focused and include:
- Financial statements data
- Customer transaction records
- Market analysis data
- Risk assessment metrics

## 🛠️ Troubleshooting

### Common Issues

**Import errors**: Ensure all packages are installed
```bash
pip install -r setup/requirements.txt
```

**Kernel crashes**: Restart kernel and clear outputs
```
Kernel → Restart & Clear Output
```

**Data file not found**: Check you're in the correct directory
```python
import os
print(os.getcwd())
```

## 📚 Additional Resources

- [Course Syllabus](syllabus/course-outline.md)
- [Weekly Schedule](syllabus/schedule.md)
- [Python Cheat Sheet](resources/cheatsheets/)
- [Recommended Readings](resources/readings/)

## 📧 Contact & Support

- **Course Forum**: [Canvas/LMS Link]
- **Email**: datasc-maksi@feb.ui.ac.id
- **Office Hours**: Tuesday 14:00-16:00 WIB (Online)

## 🏆 Grading

| Component | Weight |
|-----------|--------|
| Assignments | 30% |
| Midterm Project | 25% |
| Final Project | 35% |
| Class Participation | 10% |

## 📜 Academic Integrity

All submitted work must be original. Plagiarism detection tools are employed. Collaboration is encouraged for learning but individual submissions must reflect personal understanding.

## 🙏 Acknowledgments

Special thanks to:
- MAKSI FEB UI for supporting practical data science education
- All contributing instructors and teaching assistants
- Open-source community for tools and datasets

---

**Last Updated**: August 2025  
**Version**: 1.0.0
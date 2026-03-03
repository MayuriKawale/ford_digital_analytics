# Ford Digital Experience & Conversion Intelligence

A data science project analyzing web session behavior to predict conversion likelihood, 
drawing on techniques used by Ford Motor Company's digital analytics team.

## Project Overview
This project uses the Google Analytics public dataset as a proxy for automotive 
e-commerce web traffic. The goal is to predict whether a web session will result 
in a conversion (purchase), and to identify the key behavioral drivers of conversion.

## Tech Stack
- Python 3.13.12
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost
- NLTK, Keras, TensorFlow
- SciPy, Statsmodels, PyMC
- FastAPI, Docker
- Microsoft SQL Server (SSMS)
- GitHub Actions (CI/CD)

## Techniques
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning (Classification)
- Natural Language Processing
- A/B & Multivariate Testing
- Bayesian Statistical Analysis
- Model Deployment & MLOps

## Project Structure
```
ford-digital-analytics/
│
├── notebooks/        ← Jupyter notebooks
├── data/             ← Raw and cleaned datasets (not committed)
├── src/              ← Python scripts and modules
├── tests/            ← pytest files
└── requirements.txt  ← Python dependencies
```

## Setup Instructions

### Prerequisites
- Python 3.13.12 installed
- Git installed
- Git Bash or terminal

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/MayuriKawale/ford-digital-analytics.git
cd ford-digital-analytics
```

**2. Create and activate virtual environment**
```bash
python -m venv venv
source venv/Scripts/activate  # Git Bash on Windows
# or
venv\Scripts\activate  # Windows CMD
# or
source venv/bin/activate  # Mac/Linux
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Download the dataset**
- Go to [Google Analytics Customer Revenue Prediction](https://www.kaggle.com/competitions/ga-customer-revenue-prediction/data) on Kaggle
- Download `train.csv`
- Place it in the `data/` folder

**5. Launch JupyterLab**
```bash
jupyter lab
```

## Project Phases
- [x] Phase 1 - Python & Data Wrangling (In Progress)
- [ ] Phase 2 - SQL for Web Analytics
- [ ] Phase 3 - Conversion Prediction with ML
- [ ] Phase 4 - NLP on Customer Voice Data
- [ ] Phase 5 - A/B Testing & Bayesian Analysis
- [ ] Phase 6 - Model Deployment & MLOps
- [ ] Phase 7 - Storytelling & Portfolio Packaging

## Dataset
This project uses the [Google Merchandise Store dataset](https://www.kaggle.com/competitions/ga-customer-revenue-prediction/data) 
from Kaggle as a proxy for automotive e-commerce web analytics data.
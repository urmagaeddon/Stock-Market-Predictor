📄 INSTALL.md

 🔧 Installation Guide

Requirements
- Python 3.8+
- pip (Python package manager)

Steps
1. Clone the repository:
   
   git clone https://github.com/yourusername/stockpredictorinator.git
   cd stockpredictorinator
Create a virtual environment (optional but recommended):


python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Install dependencies:

pip install -r requirements.txt
Troubleshooting
yfinance errors → Update with pip install yfinance --upgrade

Matplotlib issues on Mac → Run pip install --upgrade matplotlib

If you encounter scikit-learn version issues, use:

pip install scikit-learn==1.3.0

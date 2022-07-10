# EDHEC_Hedgefund-Stock-Price-Analysis

### Script Dependencies and Infor: 
- Config.ipynb (contains all relevant library imports and assumptions made) -> does not have any notebook dependency to run
- Clean.ipynb (contains two clean function for each dataset) -> depends on Config.ipynb
- Hedge_funds_analysis.ipynb (contains EDA for EDHEC hedge fund dataset) -> depends on Config.ipynb & Clean.ipynb
- Price_analysis.ipynb (contains EDA for price dataset) -> depends on Config.ipynb & Clean.ipynb
- Presentation.ipynb (contains all EDA performed on both datasets) -> depends on Config.ipynb, Clean.ipynb, Hedge_funds_analysis.ipynb, Price_analysis.ipynb

### Steps to run notebook
1) Clone github repository using the following command in your notebook/command line: git clone https://github.com/Michwynn/EDHEC_Hedgefund-Stock-Price-Analysis
2) Run Config.ipynb
3) Run Clean.ipynb
4) Run Hedge_funds_analysis.ipynb
5) Run Price_analysis.ipynb
6) Run and view Presentation.ipynb

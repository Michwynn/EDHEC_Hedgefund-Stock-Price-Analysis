# EDHEC_Hedgefund-Stock-Price-Analysis

### Script Dependencies and Infor: 
- Config.ipynb (contains all relevant library imports and assumptions made) -> does not have any notebook dependency to run
- Clean.ipynb (contains two clean function for each dataset) -> depends on Config.ipynb
- Hedge_funds_analysis.ipynb (contains EDA for EDHEC hedge fund dataset) -> depends on Config.ipynb & Clean.ipynb
- Price_analysis.ipynb (contains EDA for price dataset) -> depends on Config.ipynb & Clean.ipynb
- Presentation.ipynb (contains all EDA performed on both datasets) -> depends on Config.ipynb, Clean.ipynb, Hedge_funds_analysis.ipynb, Price_analysis.ipynb

### Steps to run notebook
1) Clone github repository using the following command 
   git clone https://github.com/Michwynn/EDHEC_Hedgefund-Stock-Price-Analysis

2) Run following notebooks as described in the sequence below:
  - Config.ipynb
  - Clean.ipynb
  - Hedge_funds_analysis.ipynb
  - Price_analysis.ipynb
  - Presentation.ipynb

3) View Presentation.ipynb for analysis and visualisations.

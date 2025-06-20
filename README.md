## Child-Mind-Institute-problematic-Internet-Use

This repository contains a machine learning solution for predicting problematic internet use severity in children and adolescents.

### Problem Statement

The objective is to predict the Severity Impairment Index (SII) on a 4-point ordinal scale:
- 0: None  
- 1: Mild
- 2: Moderate  
- 3: Severe

### Model Architecture
Implemented an ensemble approach using VotingRegressor with four complementary models:
- **XGBoost Regressor** - Gradient boosting with robust missing data handling
- **LightGBM Regressor** - Efficient gradient boosting framework
- **CatBoost Regressor** - Categorical feature optimization
- **TabNet** - Deep learning architecture for tabular data

### Evaluation Framework
- Quadratic weighted kappa optimization for threshold determination
- Final performance: **0.513 QWK**

### Repository Structure

- main.ipynb - Complete solution implementation
- requirements.txt - Python package dependencies

### Setup and Execution

bash   
- pip install -r requirements.txt
- jupyter notebook main.ipynb

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
For questions or collaboration opportunities, please open an issue or contact lakshmiprasanna.lp07@gmail.com.

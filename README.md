## Environment Setup

#### Create a virtual environment
python3 -m venv hot_leads_predictor_env

#### Activate the virtual environment
source hot_leads_predictor_env\bin\activate

pip install pandas numpy scipy plotly matplotlib ipykernel jupyterlab

#### Add Virtual Environment as a Jupyter Kernel to run on Jupyter lab: (Optional)
python -m ipykernel install --user --name=hot_leads_predictor_env


## Model Used - Logistic Regression

### Performance Metrics

Input Features -

Categorical features selected based on correlation after null value imputation - ['what_matters_most_to_you_in_choosing_a_course', 'tags']

Numerical features selected based on moderate to strong correlation - ['total_visits', 'total_time_spent_on_website', 'page_views_per_visit']

Precision - 0.82

Recall - 0.92

F1 Score - 0.82

AUC Score - 0.875 (Indicates high Predictive Power)


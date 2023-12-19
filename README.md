#### Environment Setup

# Create a virtual environment
python3 -m venv hot_leads_predictor_env

# Activate the virtual environment
source hot_leads_predictor_env\bin\activate

pip install pandas numpy scipy plotly matplotlib ipykernel jupyterlab

# Add Virtual Environment as a Jupyter Kernel to run on Jupyter lab: (Optional)
python -m ipykernel install --user --name=hot_leads_predictor_env

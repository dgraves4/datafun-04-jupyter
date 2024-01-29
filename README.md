## datafun-04-jupyter
This project demonstrates the use of Jupyter notebooks to generate data stories. The project includes a project virtual environment with popular libraries for data analytics including pandas, matplotlib, and seaborn, and introduces a common process for starting exploratory data analysis projects.
# Enironment Setup
py -m venv .venv #Create virtual environment
source .venv/Scripts/activate #Activate virtual environment (git bash terminal)
py -m pip install jupyterlab pandas matplotlib seaborn 
py -m pip freeze > requirements.txt
# Project Setup Guide


```bash
# Cloning the repository
git clone https://github.com/fairdataihub/dmpchef.git

# Open the folder in VS Code
code .

# Create a new Conda environment with Python 3.10
conda create -p <env_name> python=3.10 -y

# Activate the environment (use full path to the environment)
conda activate <path_of_the_env>

# Install dependencies from requirements.txt
pip install -r requirements.txt

# Run it
uvicorn app:app --reload


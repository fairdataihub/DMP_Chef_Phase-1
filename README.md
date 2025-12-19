# Clone the repository
git clone https://github.com/fairdataihub/dmpchef.git
cd dmpchef

# Open in VS Code
code .

# Create and activate a Conda env (Python 3.10)
conda create -n dmpchef python=3.10 -y
conda activate dmpchef

# Install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt

# Install the package (choose one)
python setup.py install
# or: pip install -e .

# Run the app
uvicorn app:app --reload

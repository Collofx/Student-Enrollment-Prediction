
### **.gitignore**

This `.gitignore` file ensures that unnecessary or sensitive files (like the trained model, datasets, or Python bytecode files) are not included in the repository.

```gitignore
# Python
*.pyc
*.pyo
__pycache__/

# Jupyter Notebook Checkpoints
.ipynb_checkpoints

# Model files
student_enrollment_model.pkl

# Dataset files
student_data.csv

# Virtual environment
venv/
.env/

# Editor files
.vscode/
.idea/

# Logs
*.log

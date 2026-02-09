# Environment Setup Guide

## Prerequisites
- Python 3.8 or higher
- Git
- pip (Python package manager)

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/davidbrok/Thesis-SST-Effect-on-fishery.git
cd Thesis-SST-Effect-on-fishery
```

### 2. Create a Virtual Environment (Recommended)
```bash
# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Verify Installation
```bash
python -c "import numpy, pandas, scipy; print('All packages installed successfully!')"
```

## Using Jupyter Notebooks
```bash
jupyter notebook
```

## Working on Multiple Devices

### First Time Setup on New Device
1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies from requirements.txt
4. You're ready to work!

### Syncing Changes Across Devices
```bash
# Before starting work
git pull origin main

# After making changes
git add .
git commit -m "Your descriptive message"
git push origin main
```

## Troubleshooting

**Issue**: Module not found error
- **Solution**: Ensure virtual environment is activated and all dependencies are installed

**Issue**: Git authentication error
- **Solution**: Set up SSH keys on your device or use personal access tokens

## Additional Resources
- [Python Virtual Environments](https://docs.python.org/3/tutorial/venv.html)
- [Git Documentation](https://git-scm.com/doc)
- [Jupyter Notebook Guide](https://jupyter-notebook.readthedocs.io/)
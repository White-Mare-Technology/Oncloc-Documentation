# Oncloc-Documentation
## Setting Up and Running MkDocs Documentation

Follow these steps to set up and run the documentation using the Material for MkDocs theme:

```bash
# Navigate to Your Project Directory
cd path/to/your/cloned/mkdocs/project

# Set Up a Virtual Environment
## Install virtualenv if not already installed
pip install virtualenv
## Create a virtual environment named 'venv'
virtualenv venv

# Activate the Virtual Environment
## On Windows
venv\Scripts\activate
## On macOS and Linux
source venv/bin/activate

# Install MkDocs and Material Theme
pip install mkdocs-material

# Install Dependencies (Optional)
## Install additional dependencies if listed in requirements.txt
pip install -r requirements.txt  # Replace with your requirements file name if different

# Run MkDocs Serve
mkdocs serve

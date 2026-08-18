# Automated Lesion Detection in Medical Images using Deep Learning

## Setup for Windows & Nvidia GPU

### Prerequisites
- Download Git
- Python version 3.12+
- Download and install Visual Studio (VS) Code or other relevant Editor that supports running Jupyter Notebook
- Download and install Anaconda or other relevant virtual environment

### Steps
- Create a virtual environment
- Run "pip install -r requirements.txt" in virtual environment to install the dependencies required
- Unzip so the file structure is as shown with folders static and templates, best_model.pt, requirements.txt and ipynb.
- Run ipynb script in VS Code and if prompted, install ipynb kernel.

#### Execution Note
- The dataset will be automatically downloaded, if tar file not present, and will be automatically extracted, if "data" folder not present
- The model training will be ran if no .pt model file exists or will skip training if present
- Slices for train, test and val as well as spacing files will be automatically prepared if not present within "data" folder
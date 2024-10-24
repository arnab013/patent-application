## Installation

Follow these steps to set up the project locally:

## 1. Clone the repository

First, clone the GitHub repository to your local machine:

### bash
git clone https://github.com/arnab013/patent-application.git
cd patent-application

## 2. Create and activate a virtual environment (Optional but recommended)
Creating a virtual environment helps to keep dependencies isolated from other projects.

On macOS/Linux:

### bash
python3 -m venv venv
source venv/bin/activate

On Windows:

### bash
Copy code
python -m venv venv
venv\Scripts\activate

Once activated, your terminal prompt should indicate you're in the virtual environment.

## 3. Install dependencies
Install the required Python libraries listed in requirements.txt by running the following command:

### bash
pip install -r requirements.txt
This will install all the necessary dependencies, including:

  fpdf
  pandas
  sentence-transformers
  scikit-learn
  numpy
  tensorflow
  matplotlib
  torch
  joblib
  ipywidgets

## 4. Additional Setup for Jupyter (if applicable)
If you plan to use the project in a Jupyter notebook environment, ensure you have Jupyter installed:

### bash
pip install notebook
Then you can start Jupyter by running:

### bash
jupyter notebook
## 5. Running the application
To run the application locally, execute the main script:

### bash
python main_script.py
This will launch the interface where you can submit patent applications and generate IPC predictions and search reports.

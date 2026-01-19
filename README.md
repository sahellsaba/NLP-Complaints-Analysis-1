# NLP Complaints Analysis


## Dataset

The dataset is too large to be stored directly in this repository.

You can download the dataset from the official Consumer Financial Protection Bureau website:  
https://www.consumerfinance.gov/data-research/consumer-complaints/#get-the-data


After downloading, extract the CSV file and update the file path in the code
to point to the local location of the dataset.

---

## Installation

To set up the environment, it is recommended to use a virtual environment
to avoid dependency conflicts.

### Step 1: Create a Conda virtual environment

conda create -n nlp_env

### Step 2: Activate the environment
conda activate nlp_env

### Step 3: Install required packages

Make sure you are inside the project directory and run:

pip install -r requirements.txt

### Step 4: Download required spaCy language models
python -m spacy download en_core_web_sm

python -m spacy download en_core_web_md

After installing the necessary dependencies, the code can be executed using the final.ipynb in a virtual environment.

After installing the necessary dependencies, the code can be executed using the final.ipynb in a virtual environment.

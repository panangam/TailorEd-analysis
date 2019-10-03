# TailorEd Analysis Modules

This repository stores the codes used in data analysis in TailorEd project. Further Jupyter notebooks, data, and Python (and perhaps R) scripts should be stored here. 

Currently, only prototypes for reading data and basic analysis exist.

## Usage

Install dependencies in the local environment using `pip install -r requirements.txt`. Using a virual environment (virtualenv, venv, etc.) is always a good idea.

Not much functionality has been implemented. Contributors should start by looking at the prototype Jupyter notebooks to see basic data import.

## Directories

- `data`: for storing all real world data, including data from IR and output from CCID neural network
- `mock_up_data`: for storing mocked up data used for prototyping. Real data format may differ, but hopefully the approximated format should contain the same information.

## Jupyter notebooks

- `prototype_1.ipynb`: Shows basics on how to import different types of data, filter them, and relate them to each other. 
- `prototype_2.ipynb`: Shows how to read data from CCID. **However, the current multi-sheets format is extremely inconvenient, so hopefully the format will change, making this file obsolete. Repeat, I want this file to be obsolete. More info inside.**


# DML_Vancouver

## Description
DML_Vancouver is a project that aims to estimate the effect of transit stations on commercial break and enter crimes in Vancouer city using Double Machine Learning Framework.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/M-AzizSrairi/DML_Vancouver.git
    ```
2. Navigate to the project directory:
    ```bash
    cd DML_Vancouver
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
### Data Preparation
1. Run `census_data_extraction.ipynb` to extract and prepare census data.
2. Run `counts_prep.ipynb` to prepare counts data.
3. Run `merged_dataprep.ipynb` to merge datasets.

### Model Implementations in DML Framework and Evaluations
1. Open `DML_FINAL_5_MODELS.ipynb` and follow the instructions to train the models.

### Prediction
1. Run `prediction.ipynb` to make predictions based on the trained models.

### Visualization
1. Run `visualizations.ipynb` to generate visualizations of the data.

## Repository Structure
- `Data/`: Contains raw data files.
- `Data_wrangler/`: Scripts for data preprocessing.
- `DML_FINAL_5_MODELS.ipynb`: Main notebook for training models.
- `prediction.ipynb`: Notebook for making predictions.
- `visualizations.ipynb`: Notebook for visualizing data.
 

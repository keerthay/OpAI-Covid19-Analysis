# COVID-19 Data Analysis Project

## Introduction

This project focuses on analyzing COVID-19 data to uncover trends, make predictions, and provide insights into the pandemic's progression. Utilizing Python in a Google Colab environment, the project leverages MLflow for efficient tracking of experiments, ensuring reproducibility and streamlined analysis.

## Installation

Instructions for setting up the project environment:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/keerthay/OpAI-Covid19-Analysis/
   ```

2. **Open Google Colab**:
   - Navigate to [Google Colab](https://colab.research.google.com/).
   - Upload the Jupyter notebook from the cloned repository.

3. **Install Dependencies**:
   - Run the following in the first cell of the notebook to install required packages:
     ```python
     !pip install -r requirements.txt
     ```

## Usage

How to run and use the project:

1. **MLflow Setup**:
   - Follow the steps in the notebook to initialize MLflow for tracking experiments.

2. **Running Analysis**:
   - Execute the cells in the notebook sequentially to perform data extraction, cleaning, analysis, and visualization.

3. **Viewing MLflow Results**:
   - For local logging, download the `mlruns` directory as explained in the notebook.
   - For MLflow UI, run `mlflow ui --backend-store-uri file:///path/to/mlruns` on your local machine.

## Team

Hossein Khoshhal (hkhoshha)
Keerthi Jayaram (keerthij)
Sathiya Chakravarthy (sathiyac)
Sivashakti Komaragiri (skomarag)
Tejo Vinay Potti (tpotti)

---

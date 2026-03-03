This dataset is designed for dynamic pricing optimization. It provides valuable retail data to model and simulate how adjusting product prices impacts sales volume, revenue, and customer purchasing patterns over time. The primary objective is to find the optimal pricing strategy that maximizes total revenue while staying competitive in a dynamic market. This repository includes scripts for data processing, generating the dataset, and evaluating pricing models.

Below is an overview of the dataset's components and structure:

**1. Data Sources (Simulated)**

* **`data/raw/Retail Price Optimization.csv`:** This is the primary input file, containing the raw historical retail data used as a basis for the optimization models. The data was likely derived or simulated based on realistic retail scenarios.
* **`Retail_Price_Optimization_Test.csv`:** A specifically generated test dataset containing variations of features designed to test the robustness and generalization of the dynamic pricing models.

**2. Data Processing Scripts**

* **`generate_test_csv.py`:** A Python script responsible for generating the `Retail_Price_Optimization_Test.csv` file from the processed data. It ensures consistency in the testing methodology.

**3. Application and Modeling**

* **`app.py`:** This script is the core application or model interface. It likely contains the logic for building, training, and running the dynamic pricing optimization models on the provided datasets.
* **`notebook/Dpatter_Task_Colab.ipynb`:** A Jupyter Notebook, potentially intended for use in Google Colab, that provides an interactive environment for exploring the data, running the models, and analyzing the results. It likely contains detailed explanations, visualizations, and the step-by-step process of the optimization task.

**4. Processed Data**

* **`data/processed/cleaned_features_df.csv`:** The result of data processing and feature engineering. This file contains the refined, cleaned data ready to be ingested by the pricing models.

**5. Environment and Setup**

* **`requirements.txt`:** Lists the necessary Python packages and dependencies required to run the scripts and notebook in this repository.
* **`.gitignore`:** Specifies intentionally untracked files that Git should ignore, such as temporary files, build outputs, or local environment configurations.

# MSB1015-SV

# Visualization of Alzheimer’s Indicators within Healthy Aging

## 1. Project Overview

This project visualizes multidimensional Alzheimer’s risk indicators from the USA's Behavioral Risk Factor Surveillance System (BRFSS). The goal is to provide clear visualizations that reveal spatial and demographic patterns not easily seen in traditional statistical summaries.

**Research Question:**

> How can multidimensional Alzheimer’s risk indicators be visualized interactively to reveal spatial and demographic patterns that are not apparent in traditional statistical summaries?

The analysis covers **7 domains and 39 indicators** including:

* Caregiving
* Mental Health
* Screenings and Vaccines
* Overall Health
* Cognitive Decline
* Nutrition / Physical Activity / Obesity
* Smoking and Alcohol Use

Data is sourced from the **Centers for Disease Control and Prevention (CDC)**.

---

## 2. Datasets

This project uses **two datasets from Kaggle**:

1. [Aging and Memory: Alzheimer’s Statistics](https://www.kaggle.com/datasets/amitvkulkarni/aging-and-memory-alzheimers-statistics) - File: Dataset 1 Alzheimers (with 's'!)
2. [Alzheimer’s Disease and Healthy Aging Data](https://www.kaggle.com/datasets/daniilkrasnoproshin/alzheimers-disease-and-healthy-aging-data) - File: Dataset 2 StratifiedAlzheimers (with 's'!)

**Important:**

* The repository does **not include a `data/` folder** or `requirements.txt`.
* After downloading the datasets, you will need to **manually set the directory/file paths in the notebooks** before running them.
* For example, if your CSV is saved in `C:/Users/YourName/Downloads/`, you need to update the path in your code:

```python
Alzheimers = pd.read_csv("C:/Users/YourName/Downloads/dataset1.csv")
```

* I recommend keeping the datasets in the same folder as the notebook.

> Note: This is not the most convenient setup i know, but the other way (with .gitignore and data/ folder) didn't work for me

---

## 3. Usage

1. Download the datasets from Kaggle.
2. Open the notebooks (`.ipynb` files) (with 's'! ) in Jupyter or VSCode.
3. Adjust the file paths in the notebook code to point to the location where you saved the datasets.
4. Run the notebooks sequentially to generate exploration and visualizations

---

## 4. Notes

* If the file path is incorrect or the dataset is missing, the notebooks will raise an error prompting you to update the path.
* Code with app.py could have a error in these lines:

```python
# === 9. Run the app ===
if __name__ == "__main__":
    app.run(debug=True, port=8052)
```

Then, you change port = 8052, to another port, for example 8056 or 8057.

## 5. Thank you!

Sanne Vergouwen
2025




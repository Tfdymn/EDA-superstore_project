# Superstore Sales & Profit — Exploratory Data Analysis

## About the Project

This project is an Exploratory Data Analysis (EDA) of the Superstore dataset.

The main goal of this project is to understand the sales and profit of the store and find useful patterns in the data.

I explored the data using Python, Pandas, Matplotlib and Seaborn.

## Dataset

The project uses the **Superstore Sales Dataset** from Kaggle.

The dataset contains information about:

* Orders
* Customers
* Products
* Sales
* Quantity
* Discount
* Profit
* Category
* Sub-Category
* Segment
* Region
* Shipping
* Order dates

## What I Did

### 1. Data Understanding

* Checked the shape of the dataset
* Checked columns and data types
* Looked for missing values
* Checked duplicate records
* Explored categorical and numerical columns

### 2. Data Analysis

I investigated questions such as:

* Which region has the highest sales and profit?
* Which category and sub-category perform better?
* Which customer segment contributes the most profit?
* How does discount relate to profit?
* How are sales and profit related?
* How does profit change over the years?
* Which areas of the business appear to perform poorly?

### 3. Visualization

I used different types of charts to understand the data:

* Bar plots
* Histograms
* Box plots
* Scatter plots

### 4. Correlation Analysis

I checked the relationships between numerical variables such as:

* Sales and Profit
* Discount and Profit
* Quantity and Profit

## Key Findings

Some of the important findings from the analysis are:

* Sales and Profit have a moderate positive relationship.
* Discount and Profit have a weak negative relationship.
* Quantity and Profit have a very weak relationship.
* Profit differs between categories, sub-categories, regions and customer segments.
* Furniture has the lowest average profit among the three categories.
* Overall profit shows an increasing trend across the years.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

```text
EDA-superstore_project/
│
├── data/
│   └── Sample - Superstore.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

## How to Run

Clone the repository and install the required packages:

```bash
pip install -r requirements.txt
```

Then start Jupyter Notebook:

```bash
jupyter notebook
```

Open `EDA.ipynb` and run the notebook cells.

## Conclusion

This project helped me practice the complete basic EDA workflow:

**Understand → Clean → Analyze → Visualize → Find Relationships → Interpret**

The main focus of this project was not only writing Python code, but also understanding what the data is telling me and explaining the findings in simple language.
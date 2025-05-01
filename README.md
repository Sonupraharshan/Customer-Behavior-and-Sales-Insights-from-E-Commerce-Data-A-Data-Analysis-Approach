# E-Commerce Logistics and Product Insights: An Exploratory Data Analysis

This project presents an exploratory data analysis (EDA) of an e-commerce dataset, aimed at uncovering operational trends related to product characteristics, shipment logistics, and delivery performance. Visualizations and insights are generated using Python and key data analysis libraries.

## 📊 Project Overview

The dataset contains information about product cost, weight, importance, shipment mode, warehouse location, and whether the order was delivered on time. This project investigates:

- Distribution of product weights and costs
- Influence of shipment mode and product importance
- Delivery performance trends across warehouses

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation
- **Matplotlib** and **Seaborn** – data visualization

## 📁 Dataset

The dataset file used: `E_Commerce.csv`

**Columns include:**
- `Cost_of_the_Product`
- `Weight_in_gms`
- `Product_importance`
- `Mode_of_Shipment`
- `Warehouse_block`
- `Reached.on.Time_Y.N`
- and more...

> Note: The column `ID` was dropped during preprocessing as it is not analytically useful.

## 📈 Key Visualizations

- **Weight Distribution**: Understand how product weights are spread.
- **Product Importance**: Frequency of categories like high, low, and medium.
- **Cost Analysis**: Product cost distribution and relationships.
- **Warehouse & Shipment Modes**: Volume comparisons and trends.
- **Delivery Performance**: On-time delivery statistics.

## 📌 Key Insights

- Certain warehouse blocks consistently handle higher shipment volumes.
- Products with higher importance tend to be more costly and time-sensitive.
- Shipment mode has a visible impact on delivery timeliness.

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/ecommerce-eda.git
   cd ecommerce-eda
2. Install dependencies (preferably in a virtual environment):
   ```bash
   pip install -r requirements.txt
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
4. Open project.ipynb and run the cells sequentially.

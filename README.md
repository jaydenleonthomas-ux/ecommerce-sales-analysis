# E-Commerce Sales Performance & Analytics

## 📊 Project Executive Summary

### 1. Project Objective
The goal of this project was to analyze e-commerce product data using Python to uncover monthly sales trends, evaluate the impact of customer product reviews on sales volume, and identify top-performing product categories.

### 2. Key Insights & Findings
* **Monthly Sales Trends:** Overall business revenue peaks dramatically in **October**, reaching **514,798 units/value**, while hitting its lowest trough in **May** at **487,194**.
* **Product Categories:** **Toys** is the primary driver of business volume, generating **79,836 sales** in Month 1, followed closely by **Books** and **Sports**. Conversely, **Home & Kitchen** is the weakest link, generating only **57,844 sales**.
* **Customer Reviews:** A scatter plot analysis reveals **no correlation** between product review scores and overall sales volume. For instance, products with a poor 1.0 rating averaged roughly 500 sales, while perfect 5.0-star products averaged fewer sales at approximately 442.

### 3. Business Recommendations
* **Inventory Planning:** Allocate more marketing budget and increase inventory stockpiles ahead of the October peak, while running promotional discount campaigns in May to clear slow-moving items.
* **Product Focus:** Prioritize marketing real estate for high-volume items like Toys and Books. Consider investigating or revamping the Home & Kitchen line to address its lower performance.

---

## Tech Stack & Environment
* **Language:** Python 3
* **Libraries:** Pandas (Data Manipulation), Matplotlib (Data Visualization)
* **Environment:** Google Colab / Jupyter Notebooks

---

## Project Structure
* `E_Commerce_Sales.ipynb` / Core Jupyter Notebook executing data loading, cleaning (`.isnull()`), descriptive statistics (`.describe()`), grouping calculations (`.groupby()`), and final figure renderings.
* `README.md` / Project documentation and business executive summary layout.

# movit-stock-analysis
## Overview
This analysis focuses on the stock movement of hair care products across various stores in February 2025. By examining the changes in stock quantities over the month, I aim to identify trends in product availability and movement, which are crucial for effective inventory management and maximizing customer satisfaction.

The dataset contains stock information collected by merchandisers from various stores. Key columns relevant to this analysis include: 
* **DATE REPORTED:** The date and time when the stock was recorded. 
* **PRODUCT DESCRIPTION:** The name and size of the product (e.g., "MOVIT HAIR FOOD 200 GM"). 
* **STOCK LEVEL:** Indicates if the product is "Available" or "Not available".
* **QUANTITY:** The number of units in stock when the product is "Available".
* **CUSTOMER NAME:** The store where the stock was recorded (e.g., "CYLETEMBU"). 
* **REGION:** The geographical region of the store (e.g.,"NYANZA").
### Project structure
**data/** - Contains all the datasets used in the project.
**notebooks/** - Jupyter notebooks used for data analysis and cleaning.
**Presentation/** - Contains the non-technical presentation.
To set up the project locally, follow these steps: <br>
* Clone the repository. <br>
* Install the required Python packages: pip install -r requirements.txt. <br>
* Ensure you have Tableau installed for dashboard visualization. <br>
### Usage
Guide on how to use the project, including running analyses, generating visualizations, or using the dashboard.<br>
* To analyze movit stock analysis, open the relevant Jupyter notebook in the `notebooks/` directory and run the cells. To view the interactive dashboard, open [Tableau public](https://public.tableau.com/app/profile/israel.wasike/viz/movitstockmovementanalysis/Dashboard1)
### Data
Information about the datasets used, including their sources and any preprocessing steps.<br>
The project uses movit sales data for the month February 2025. Data was cleaned using Python, and visualizations were done in Tableau Desktop
### Objectives
The goal is to track how stock quantities change over the days of the month and provide insights into product availability and movement trends.
### Research Questions
1. Which day had the most significant drop or increase in total stock quantity, and what might explain this?
2. Are there any products that were consistently unavailable? If so, which ones?
3. What trends are observed in stock movement over the month (e.g., increasing, decreasing, or stable)?
### Result 
Stock levels in February 2025 fluctuated significantly, with notable drops and refills. The highest stock was recorded at the end of the month, suggesting a general upward trend. Some products were never available, possibly due to supply chain issues or low demand. Additionally, Nairobi led in sales by a significant margin, while Eastern had the lowest. Regular monitoring, better inventory planning, and strategic stock allocation based on regional demand can help maintain steady stock levels and optimize sales performance.
### Contributing
Contributions are welcome! Please fork the repository and submit a pull request with any changes or additions!

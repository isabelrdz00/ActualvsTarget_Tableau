# Actual vs Target 
### Project Overview
This Tableau project is centered around analyzing and visualizing the actual profit versus the target profit for a hypothetical gym product line. The project consists of three interactive visualizations designed to highlight how different states and products performed against their target profits.

## Key Features
- **State-Level Analysis:**
Visualizes the difference between the actual and target profits for each state through a bar chart. This enables quick identification of states that met or missed their profit goals.

- **Geographic Analysis with Map:**
A map colored by the percentage of products that met the target profit in each state. This view allows the user to visually compare how each state performed relative to the target.

- **Product-Level Detail:**
A detailed bar chart showing each product's profit and its corresponding target profit, along with color coding (green for met, gray for did not meet) to quickly identify performance against targets.
![Screenshot 2024-10-08 165558](https://github.com/user-attachments/assets/fdbd1977-002d-4b91-b838-9382d6978bad)


## Tools & Techniques
- **Level of Detail (LOD) Expressions:**
Used to create accurate calculations at the product level, ensuring the correct aggregation of products that met their target profit.

- **Calculated Fields:**
Calculated fields such as Profit vs. Target Profit, Number of Products that Met Target, and Percentage of Products that Met Target were created to enable in-depth analysis and comparison.

- **Interactive Filtering:**
The bar chart and map visualizations act as interactive filters for the dashboard, allowing users to click on a state or bar to filter the product-level detail visualization.

## Visualizations
- **State Bar Chart:**
The bar chart shows the actual profit versus target profit for each state, along with the number of unique products and the percentage of products that met the target profit.

- **Map Visualization:**
Displays the percentage of products that met the target profit for each state, with the intensity of the color indicating the performance. States can be clicked to filter the product-level detail chart.

- **Product-Level Detail Chart:**
Visualizes the profit for each product in a state, using a reference line to represent the target profit. Products that met the target are colored green, and those that did not are gray.

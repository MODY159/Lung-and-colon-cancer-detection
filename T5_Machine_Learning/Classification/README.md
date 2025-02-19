# Restaurant Menu Optimization Dataset

## Overview
This dataset provides insights into restaurant menu optimization, aiming to maximize profitability by analyzing menu item categories, ingredients, prices, and profitability indicators.

## Variables

- **RestaurantID**: Identifier of the restaurant.
- **MenuCategory**: Category of the menu item (Appetizers, Main Course, Desserts, Beverages).
- **MenuItem**: Name of the menu item.
- **Ingredients**: List of ingredients used in the menu item (confidential data included for beverages).
- **Price**: Price of the menu item in dollars (rounded to two decimal places).
- **Profitability**: Target variable indicating menu item profitability (High/Medium/Low).

## Usage

- Analyze factors influencing menu item profitability.
- Optimize pricing strategies based on ingredient costs and menu category.
- Understand customer preferences and purchasing behavior.

## Applications

- Ideal for restaurant management and marketing strategies.
- Useful for menu engineering and data-driven decision-making in the hospitality industry.

## Disclaimer

The profitability of certain menu items may vary significantly across different seasons due to fluctuations in ingredient costs. Additionally, the pricing of some beverages may decrease owing to reductions in production costs. It is important to note that the dataset does not include seasonal or time variables that would provide insights into when these changes occur. Consequently, the observed disparities in prices for identical items may be attributed to these factors.

This disclaimer aims to clarify that any discrepancies in pricing and profitability within the dataset are influenced by dynamic market conditions and cost fluctuations, rather than by inherent inconsistencies or errors in the data analysis process.

## Sample Data

| RestaurantID | MenuCategory | MenuItem               | Ingredients                                    | Price | Profitability |
|--------------|--------------|------------------------|------------------------------------------------|-------|---------------|
| R003         | Beverages    | Soda                   | ['confidential']                               | 2.55  | Low           |
| R001         | Appetizers   | Spinach Artichoke Dip  | ['Tomatoes', 'Basil', 'Garlic', 'Olive Oil']   | 11.12 | Medium        |
| R003         | Desserts     | New York Cheesecake    | ['Chocolate', 'Butter', 'Sugar', 'Eggs']       | 18.66 | High          |


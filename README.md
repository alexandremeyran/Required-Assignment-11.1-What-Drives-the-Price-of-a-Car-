##Executive Summary of Findings

Business Objective
This analysis explores a dataset of 426,000 used cars to uncover what factors most influence vehicle price. The objective is to help you better understand consumer preferences and optimize inventory and pricing strategies.
Methodology for Findings
A few models were considered to understand what drove price, and ultimately one was identified where 75-80% of the price could be explained by the car’s characteristics.
Summary of Findings
•	Vehicle Age is the Strongest Predictor of Price
o	Age alone explains a large share of price variation.
o	Newer vehicles consistently command higher prices.
o	Price depreciates sharply after the first ~6 years, then levels off.
•	Mileage (Odometer) Affects Price — But Interacts with Age
o	Lower mileage increases value, especially for newer vehicles.
o	High mileage reduces value more sharply for vehicles under 10 years old.
•	Manufacturer plays an important role in price and how vehicle value depreciates but not necessarily based on if the car is luxury (or higher priced new) 
o	Brands like Dodge, BMW, Honda, and Nissan saw large drops in vehicle price for cars that were between 11-15 years old, vs their newer versions
o	Brands like Toyota, Chevrolet, GMC, and Ram saw more modest drops in price (between 11-15 year vehicles and newer ones) 
Recommendations for fine-tuning inventory
•	Reduce inventory of cars in that are approaching the 5-7 year age threshold as these depreciate quickly during that time. Do so by either buy newer cars or cars that already have 7 years of age
•	De-prioritize buying relatively new cars (<10years old) if they already have higher mileage.
•	Focus on brands whose price depreciates more modestly as they age (Toyota, Chevrolet, GMC and Ram)

## Notebook
https://github.com/alexandremeyran/Required-Assignment-11.1-What-Drives-the-Price-of-a-Car-/blob/main/Used%20Car%20Prices%20Meyran.ipynb


## Contents

- `notebook.ipynb`: All data cleaning, modeling, and plots
- `vehicles.csv`: Source dataset
- `README.md`: Project summary








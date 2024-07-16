# Avocado Toast Supply Chain Analysis

## Project Overview

In this project, we will investigate the supply chain of ingredients for making avocado toast in the U.K. by analyzing data from the Open Food Facts database. Avocado toast has become a popular breakfast dish in recent years, and understanding the origins of its key ingredients can provide valuable insights into the complexities of modern food supply chains.

The three key ingredients we will focus on are avocados, olive oil, and sourdough bread. Our goal is to determine the most common country of origin for each of these ingredients and store the results in the following variables:

- `top_avocado_origin`
- `top_olive_oil_origin`
- `top_sourdough_origin`

To achieve this, we will:

1. Subset each of the provided DataFrames to include only the relevant columns: 'code', 'lc', 'productnameen', 'quantity', 'servingsize', 'packagingtags', 'brands', 'brandstags', 'categoriestags', 'labelstags', 'countries', 'countriestags', 'origins', 'origins_tags'.
2. Filter the DataFrames to include only rows where the 'categoriestags' column contains one of the relevant tags for each ingredient, as specified in the provided TXT files.
3. Analyze the 'origins_tags' column to determine the most common country of origin for each ingredient.
4. Ensure that the country names stored in the variables contain only letters (A-Z) and spaces, with no hyphens or other characters.

By completing this project, you will gain a deeper understanding of the complex supply chain involved in producing a single dish, such as avocado toast. This knowledge can be valuable for researchers, policymakers, and businesses interested in improving the sustainability and efficiency of food supply chains.

## Data and Methodology

The data for this project is provided in the "data" folder, which contains three pairs of CSV and TXT files for each of the three key ingredients: avocados, olive oil, and sourdough bread.

The CSV files contain extensive information about each food item, including its origin, packaging, and other relevant details. The TXT files provide the category tags of interest for each ingredient, which will be used to filter the DataFrames.

The analysis will be performed using Python and the pandas library for data manipulation and analysis.

## Key Findings

1. **Most Common Country of Origin for Avocados**: `top_avocado_origin`
2. **Most Common Country of Origin for Olive Oil**: `top_olive_oil_origin`
3. **Most Common Country of Origin for Sourdough Bread**: `top_sourdough_origin`

## Conclusion

This project provides valuable insights into the supply chain of ingredients used in making avocado toast, a popular breakfast dish in the U.K. By analyzing the data from the Open Food Facts database, we were able to determine the most common countries of origin for avocados, olive oil, and sourdough bread.

These findings can be useful for researchers, policymakers, and businesses interested in understanding the complexities of modern food supply chains and exploring ways to improve their sustainability and efficiency. Additionally, the skills and techniques developed in this project can be applied to other food-related analyses, opening up opportunities for further exploration and discovery.

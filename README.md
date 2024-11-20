# Globe ($GLBE) Revenue Prediction Model

This model aims to predict the upcoming quarter’s revenue for Globe, a hypothetical concert venue. The model uses historical revenue data along with alternative datasets such as credit card transactions, foot traffic, concert attendance, advertisement data, and tourism statistics. This README provides setup instructions and usage information.

## Requirements

- Python 3.x
- Jupyter Notebook
- Darts library
- pandas library

### Installation

1. Open the file in Jupyter Notebooks
2. Make sure to change the datapath at the top to the directory which contains the sources
3. Run all of the cells in sequence

### Output:

The model will output revenue estimates for the upcoming quarter, comparing MAPE (Mean Absolute Percentage Error) across various approaches. At the bottom, there will be the revenue estimate from the model that had the lowest MAPE. THe model takes multiple minutes to run because it goes through thousands of models.

### Data Sources
This model uses six Excel files provided in the directory:

1. Source00: Globe’s historical revenue (broken down by segment)
2. Source01: Credit card transaction data at Globe
3. Source02: Foot-traffic data near Globe’s venue
4. Source03: Concert details (attendance, occupancy, etc.)
5. Source04: Advertisement data (number of ads run)
6. Source05: Tourism data in Metropolis

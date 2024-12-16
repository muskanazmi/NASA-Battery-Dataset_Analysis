# NASA-Battery-Dataset_Analysis
In the NASA Battery Dataset showing how the following battery paramaters are changing as the battery cell is aging through charge/discharge cycles:  
Battery_impedance  
Re: Estimated electrolyte resistance (Ohms)  
Rct: Estimated charge transfer resistance (Ohms)

This project visualizes the Electrolyte Resistance (Re) and Charge Transfer Resistance (Rct) over charge/discharge cycles for a battery dataset. The dataset is taken from Kaggle and contains data on charge, discharge, and impedance cycles, including key metrics like Re and Rct for each cycle.

In this project, several key steps performed are:
Data Merging: Combines metadata with cycle data to provide comprehensive insights.
Data Cleaning: Handles missing values and ensures data integrity before visualization.
Cycle Filtering: Separates data based on cycle type (charge, discharge, impedance).

Requirements
To run the visualization, ensure you have the following Python libraries installed:

pandas
plotly

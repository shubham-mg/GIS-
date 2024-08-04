# GIS Spatial Analysis Projects

This repository contains two spatial analysis projects that utilize geographic information system (GIS) techniques to visualize and analyze spatial data. The projects included in this folder are:

1. **Global Warming Spatial Data Analysis**
2. **Restaurant Count HeatMap**

## Project 1: Global Warming Spatial Data Analysis

### Overview

This project explores the average monthly temperatures across Indian metro cities using a spatial heat map visualization. The analysis is focused on understanding temperature patterns and variations over the year, which can provide insights into climate trends and the effects of global warming.

### Methodology

- **Data Source**: The dataset includes monthly average temperatures for various metro cities in India, with geographical coordinates for metro city.
- **Visualization**: A heat map with time is used to display the temperature variations over the months. The map is generated using Folium, with a gradient color scheme that ranges from blue (lower temperatures) to red (higher temperatures).

### How to Use

- The notebook `Global_Warming_Spatial_Data_Analysis.ipynb` contains the complete analysis.
- Run the notebook to generate the interactive map, which displays the average monthly temperatures for each city.
- The map includes a time slider to visualize how temperatures change throughout the year.

## Project 2: Restaurant Count HeatMap

### Overview

This project visualizes the density of restaurants across different regions in the USA using a heat map. The analysis provides insights into the spatial distribution of restaurants, which can be valuable for urban planning, business development, and market analysis.

### Methodology

- **Data Source**: The dataset consists of geographical coordinates and the count of restaurants in various locations across the USA.
- **Visualization**: A static heat map is created using Folium, highlighting areas with higher concentrations of restaurants. The map uses a color gradient from blue (lower density) to red (higher density).

### How to Use

- The notebook `Zomato_Spatial_Analysis.ipynb` contains the full analysis.
- Run the notebook to generate the heat map that displays restaurant densities across the USA.
- This map provides a visual representation of where restaurants are more densely located, which can aid in various spatial analyses.

## Requirements

To run these analyses, you will need the following:

- Python 3.x
- Jupyter Notebook
- Folium
- Pandas

Ensure all dependencies are installed before running the notebooks.

## Conclusion

These projects utilize GIS techniques to provide valuable insights into spatial data, illustrating the power of visualizing complex datasets geographically. Feel free to explore the notebooks and adapt the code for your own analyses.

For any questions or contributions, please open an issue or submit a pull request.


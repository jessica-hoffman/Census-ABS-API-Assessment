# Census-ABS-API-Assessment

Revenue per Employee by Industry Sector from 2018-2020

## Introduction

This project analyzes the annual revenue per employee for different industry sectors in the US from 2018 to 2020. Please note that data for the listed year is always collected the prior year (i.e. 2021 data references 2020 and is called in the API as 2020). The data is sourced from the [US Census Bureau](https://www.census.gov/data/developers/data-sets.html) and is available as JSON files in the `data` directory. The main goal of the project is to create visualizations that show the trends in revenue per employee by state, gender, race, veteran status, and highlight any impacts from COVID on different industry sectors.

## Project Structure

The project directory contains the following files and directories:

- `data/`: directory containing the JSON files with the raw data.
- `PandasCensusAPI_Assessment.ipynb`: Jupyter notebook with the code that analyzes and visualizes the data.
- `README.md`: this file.

## Instructions

To run the analysis and create the visualizations, open the `PandasCensusAPI_Assessment.ipynb` notebook in Jupyter and run all the cells. The notebook contains detailed comments explaining the steps of the analysis and how the visualizations are generated.

## Group Members

This project was developed by the following group members:

- Jessica Hoffman (git repo owner): created the API call, analyzed the data and wrote the Jupyter notebook, README file, and final report memo.
- Vanessa Schroeder: helped with the data cleaning and preprocessing, and analyzed the data.
- Alexandra Reilly: helped with the data cleaning and preprocessing, analyzed the data, and wrote the introduction and ETL report.

## References

- US Census Bureau. (2017). Business Dynamics Statistics Annual Series. [https://www.census.gov/data/tables/2017/econ/gus/revenues-per-employee.html](https://www.census.gov/data/tables/2017/econ/gus/revenues-per-employee.html).




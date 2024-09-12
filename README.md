# EDA on Solar Power Generation

This project performs **Exploratory Data Analysis (EDA)** on solar power generation and weather sensor data from a solar power plant. The primary goal is to extract meaningful insights, identify trends, and perform data visualization on the generation and weather data to understand the performance of the solar plant.

## Project Structure

- **Jupyter Notebook**: The analysis is done using a Jupyter Notebook, where data is read, cleaned, and visualized using Python libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn`.

## Data Sources

- **Plant_1_Generation_Data.csv**: This file contains the solar power generation data, including DC/AC power, daily yield, and total yield.
- **Plant_1_Weather_Sensor_Data.csv**: This file contains weather sensor data for the same solar plant, including ambient temperature, module temperature, and irradiation values.

### Key Columns:
- **Generation Data**:
  - `DATE_TIME`: Timestamp of the observation
  - `PLANT_ID`: Plant ID (unique for each solar plant)
  - `SOURCE_KEY`: Identifier for each inverter
  - `DC_POWER`: Direct current power output
  - `AC_POWER`: Alternating current power output
  - `DAILY_YIELD`: Daily energy yield in kWh
  - `TOTAL_YIELD`: Total cumulative energy yield in kWh

- **Weather Data**:
  - `DATE_TIME`: Timestamp of the observation
  - `AMBIENT_TEMPERATURE`: Temperature of the surrounding environment
  - `MODULE_TEMPERATURE`: Temperature of the solar panel module
  - `IRRADIATION`: Solar irradiation level

## Requirements

To run the analysis, the following Python libraries are required:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `jupyter` (to run the notebook)



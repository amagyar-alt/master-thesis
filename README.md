## Data Download Instructions

1. Visit the [IEA Weather for Energy Tracker](https://www.iea.org/data-and-statistics/data-tools/weather-for-energy-tracker)

2. Download the following daily world files (surface-weighted averaging):
   - Wind speed at 100m height
   - Temperature
   - Relative Humidity
   - Cloud Cover
   - Precipitation

3. Place the downloaded CSV files in the `raw/` directory

4. Run the data processing script or notebook to generate `hungary_daily_processed.csv`

## Data Description

| Variable | Description | Unit |
|----------|-------------|------|
| wind100 | Wind speed at 100m height | m/s |
| temperature | Mean daily temperature | °C |
| humidity | Relative humidity | % |
| cloud | Cloud cover fraction | % |
| precipitation | Daily precipitation | mm |

## Citation

If using this data, please cite:

> IEA & CMCC (2023). Weather for Energy Tracker. International Energy Agency. https://www.iea.org/data-and-statistics/data-tools/weather-for-energy-tracker

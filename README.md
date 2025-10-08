# Rainfall Comparison: Seattle vs New York City (2018-2022)

> This project compare the weather between Seattle and New York City from Jan 1 2018 to Dec 31 2022.

--- 

## Project Overview

This project explores and compares daily precipitation data between Seattle and New York, NY.  
The goal is to determine which city receives more rainfall on average and examine seasonal rainfall patterns. 

- **Objective:** Compare rainfall patterns between Seattle and New York.
- **Domain:** Climate, Weather
- **Key Techniques:** Data cleaning, data merging, visualization, comparison of time series

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** 

seattle_rain.csv : https://raw.githubusercontent.com/brian-fischer/DATA-5100/refs/heads/main/weather/seattle_rain.csv

Newyork_rain.csv: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND - 

- **Description:** CSV files containing daily precipitation measurements
- **License:** NOAA and Github

---

## Analysis

- **Notebook:** 'Seattle_weather_project.ipynb'
- **Steps Taken:** 
    1. Load and inspect Seattle and New York City precipitation datasets. 
    2. Clean data: convert date columns, rename precipitation columns, remove duplicates, filter dates, and handle missing values.
    3. Merge datasets into wide and long formats.  
    4. Create derived variables for rainy days and month.  
    5. Calculate and visualize total rainy days for each city.  
    6. Calculate and visualize monthly average precipitation to examine seasonal patterns.  
    7. Interpret results using simple language for general readers.
- **Communication Report**: ["reports/Communication The Results.pdf"]


---

## Results

- Seattle has more rainy days than New York City.  
- Seattle’s rainfall is more seasonal, heavier in winter.  
- New York City’s rainfall is more evenly distributed throughout the year.  
- Visualizations show both the frequency of rain and seasonal patterns for each city.
- Overall, Seattle rains more frequently, but total precipitation amount can vary month to month.

---

## Authors

- Muykhim Ing - [muykhim](https://github.com/muykhim)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Python libraries used: pandas, numpy, matplotlib, seaborn 
- NOAA for weather datasets
- Tutorials and examples from DATA-5100 course materials by Dr. Brian Fischer
# COVID-19 Global Data Tracker 🦠🌍

This project analyzes global COVID-19 trends using publicly available datasets. It focuses on tracking the progression of cases, deaths, and vaccinations, providing visual insights and a summary of key findings.

## 📌 Features

- Loads and merges data from JHU and Our World in Data (OWID)
- Handles missing and inconsistent data
- Generates visualizations for:
  - Total and new cases
  - Deaths
  - Vaccination rates
- Produces an interactive choropleth map of global case distribution
- Outputs a summary report of key insights

## 🚀 How to Use

1. **Open the Jupyter Notebook**  
   Launch `covid_tracker.ipynb` in Jupyter Notebook or any compatible environment.

2. **Run the Code**  
   Follow the prompts to select countries or press Enter to use default selections.

3. **View Results**  
   - Visualizations will be saved as PNG files.  
   - A choropleth map (`cases_map.html`) will open in your browser.  
   - A summary text report will be generated as `covid_insights.md`.

## 📦 Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- plotly

Install required packages using:

```bash
pip install pandas matplotlib seaborn plotly
```

## 📊 Data Sources

- [Johns Hopkins University CSSE COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)
- [Our World in Data COVID-19 Dataset](https://github.com/owid/covid-19-data)

## 📝 License

This project is open-source and free to use for educational and research purposes.

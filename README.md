# forecasting_net_prophet


This Jupyter notebook is Forecasting Mercado Libre shareprice using fbprophet


---

## Technologies

Project uses:

[pystan](https://pystan.readthedocs.io/en/latest/)

[fbprophet](https://facebook.github.io/prophet/)

[hvplot](https://hvplot.holoviz.org/)

[holoviews](https://holoviews.org/)




---

## Installation Guide

Run this program in google colab research and install the required libraries using the code at the beginning of the file


---

## Usage

Utilize Colab to interact with the software program

!["Google Colab Labs Example"](https://www.tutorialspoint.com/google_colab/images/colab_search.jpg)

**Key example code for google colab data upload**
```
# Upload the "google_hourly_search_trends.csv" file into Colab, then store in a Pandas DataFrame
# Set the "Date" column as the Datetime Index.

from google.colab import files
uploaded = files.upload()

df_mercado_trends = pd.read_csv(
    "google_hourly_search_trends.csv",
     index_col="Date", 
    parse_dates=True, 
    infer_datetime_format=True
)

# Review the first and last five rows of the DataFrame
print(df_mercado_trends.head())
print(df_mercado_trends.tail())
```

---

## Contributors

Hugo Kostelni

---

## License

Open Source

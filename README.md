# Currency Exchange Rates Dataset/Description for DataSet

The dataset provides currency exchange rates against the **Euro (EUR)** for various currencies. The exchange rates are denoted in their respective currency units.

## Currencies Included

The dataset contains exchange rates for the following currencies:

- Australian dollar (AUD)
- Bulgarian lev (BGN)
- Brazilian real (BRL)
- Canadian dollar (CAD)
- Swiss franc (CHF)
- Chinese yuan renminbi (CNY)
- Cypriot pound (CYP)
- Czech koruna (CZK)
- Danish krone (DKK)
- Estonian kroon (EEK)
- UK pound sterling (GBP)
- Greek drachma (GRD)
- Hong Kong dollar (HKD)
- Croatian kuna (HRK)
- Hungarian forint (HUF)
- Indonesian rupiah (IDR)
- Israeli shekel (ILS)
- Indian rupee (INR)
- Iceland krona (ISK)
- Japanese yen (JPY)
- Korean won (KRW)
- Lithuanian litas (LTL)
- Latvian lats (LVL)
- Maltese lira (MTL)
- Mexican peso (MXN)
- Malaysian ringgit (MYR)
- Norwegian krone (NOK)
- New Zealand dollar (NZD)
- Philippine peso (PHP)
- Polish zloty (PLN)
- Romanian leu (RON)
- Russian rouble (RUB)
- Swedish krona (SEK)
- Singapore dollar (SGD)
- Slovenian tolar (SIT)
- Slovak koruna (SKK)
- Thai baht (THB)
- Turkish lira (TRY)
- US dollar (USD)
- South African rand (ZAR)

## Data Format

The dataset is in tabular format, with two columns:

- **Period/Unit**: Represents the date of the recorded exchange rates.
- The subsequent columns represent the exchange rates against the Euro for each currency mentioned above.


# Description of project

# Data Analysis Project: Euro to US Dollar Exchange Rate

This data analysis project explores the historical **Euro to US Dollar (EUR-USD) exchange rates** and examines how major global events and presidential terms may have influenced the currency's value over time. The analysis is conducted using **Python's Pandas, Matplotlib, and Seaborn** libraries.

## Data Loading and Preprocessing

The analysis begins by loading the dataset containing daily historical exchange rates from a CSV file named **'euro-daily-hist_1999_2022.csv'**. The dataset includes exchange rates for the Euro against various currencies, but the focus is on the Euro to US Dollar rates.

Several data preprocessing steps are performed, including:

- **Renaming columns** for readability, especially changing **'[US dollar ]'** to **'US_dollar'**.
- Converting the **'Time'** column to a datetime format for easier manipulation.
- **Sorting** the data by time to ensure a chronological order.
- **Removing rows** with missing or invalid exchange rate values **("-")** from the **'US_dollar'** column.
- Computing a **rolling mean** of the Euro-USD exchange rate over a 30-day window.

## Visualizing Exchange Rate Trends

The first visualizations show the Euro to US Dollar exchange rate trends over time. A **line plot** is used to display the daily exchange rates. Subsequent plots show the **rolling mean** of the exchange rate over different rolling windows (7, 30, 50, 100, and 365 days). The rolling mean helps smooth out short-term fluctuations and reveals long-term trends.

## Major Global Events and Exchange Rates

The analysis includes annotations for major global events that may have impacted the Euro-USD exchange rate. Each event is marked on the line plot to highlight its occurrence in relation to the exchange rate. Additionally, the line plot's stroke is colored differently for each event's time period, providing a visual indication of when the events occurred.

## Exchange Rate Changes During US Presidential Terms

The analysis further explores exchange rate changes during specific US presidential terms. It isolates the exchange rates for the periods corresponding to the presidencies of **George W. Bush, Barack Obama, Donald Trump, and Joe Biden**. Each presidency's data is plotted separately, showing the rolling mean of the Euro-USD exchange rate during that term.

## Observations and Conclusions

The data analysis provides insights into the historical trends of the Euro to US Dollar exchange rate and its potential relationships with significant global events and US presidential terms. The visualizations highlight periods of volatility, stability, and possible correlations with geopolitical events and leadership changes.

It's important to note that while this analysis can provide valuable insights, exchange rates are influenced by various complex factors, and **correlation does not imply causation**. Further research and economic analysis would be necessary to establish definitive conclusions about the factors affecting the Euro-USD exchange rate.

Please note that the code provided here is a part of the data analysis process and should be executed in a Python environment with the necessary libraries installed to reproduce the visualizations and results.

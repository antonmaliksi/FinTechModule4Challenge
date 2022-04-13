# Risk Return Analysis

This application is used to generatate quantitative analytic data of four funds and the S&P 500. Note that this can be used with other funds and markets, as well.

---

## Technologies

Python and the following packages were used: Pandas, Numpy, Pathlib, and MatplotLib.

---
---

## Installation Guide

To begin using the notebook in Jupyter Labs:

### Part 1
1. Open "crypto_arbitrage.ipynb".
2. Look for the following:
    ```python
    whale_df = pd.read_csv(
        Path("Resources/whale_navs.csv"),
        index_col = "Timestamp",
        parse_dates = True,
        infer_datetime_format = True
    )
    ```
3. Ensure that "Path()" has the correct .csv file you are utilizing for data manipulation.
4. If correct .csv file is unavailable, transfer the .csv file into the "Resources" folder located within this parent folder.
5. Replace "whale_df" and "whale_navs.csv" with the correct Exchange and .csv file name. NOTE: Make sure to add ".csv" to the file name.
6. In Step 3, change "whale_df" to the appropriate dataframe you have just created.

### Part 2
1. Observe the red-colored text within quotations throught the notebook.
2. Replace "Soros", "Paulson", "Tiger", "Hathaway" or "S&P 500" with the appropriate funds or markets.
3. Run the notebook.

---

## Documentation
Please reference the following screenshots for guidance with any changes within the code:

Original .csv              |  Demonstration .csv
:-------------------------:|:-------------------------:
![Alt text](url)           |  ![Alt text](url)

Original Step 3            |  Demonstration Step 3
:-------------------------:|:-------------------------:
![Alt text](url)           |  ![Alt text](url)

Original Red Text          |  Demonstration Red Text
:-------------------------:|:-------------------------:
![Alt text](url)           |  ![Alt text](url)

Original Red Text 2        |  Demonstration Red Text 2
:-------------------------:|:-------------------------:
![Alt text](url)           |  ![Alt text](url)


## Contributors
All work was completed by Junior Quantitative Analyst Anton Maliksi.

---

## License
No licenses were used for this notebook.
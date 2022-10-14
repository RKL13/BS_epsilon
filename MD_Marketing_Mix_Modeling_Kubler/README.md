# Marketing Modeling Mix -- Kubler's Tuto on Medium.com

[Link to the tuto Pt.1](https://medium.com/towards-data-science/introduction-to-marketing-mix-modeling-in-python-d0dd81f4e794)

[Link to the Dataset](https://github.com/Garve/datasets/blob/4576d323bf2b66c906d5130d686245ad205505cf/mmm.csv)

### Tuto's Synopsis 🎥

This Marketing Mix Modeling aims to understand the impact of each Ads media channel investment on sales.

In part 1, a simple additive model (linear regression) is implemented so one can use the coefficients to apprehend the unique contribution of each Ads media channel on Sales.

### Coding Virtuosity 💃

- In the read_csv, parse_date is used to give Datetime types

- TimeSeriesSplit() is used for cross-validation when working with a time series

- .mul() is used but with a whole series: each column will apply to each other respective column, which is beautiful

- .assign() assigns a new column to a pandas DataFrame

- plt.stackplot helps for area charts

- 🏅A special mention to Part 1, Cell 29, which is an exquisite manipulation 🏅

- OptunaSearchCV() allows a fine tuning in between GridSearchCV() and RandomSearchCV()

- convolve2d is used to modelize the Carry Over Effect of an advertising
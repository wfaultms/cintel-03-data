# Application Data

Like most professional analysts, we'll use data from a variety of sources. We'll keep data in the **data** folder to keep our 
repository organized.

## Data Sources

One of the best ways to get user-friendly data is to access the datasets from the Python packages we use to analyze data.
[Seaborn](https://seaborn.pydata.org/) is a popular Python package for data visualization. It includes several [datasets](https://github.com/mwaskom/seaborn-data). Each dataset can be returned as a Pandas DataFrame, a powerful data structure for working with Excel-type data (in rows and columns).

## Gather Data

1. Review the list of Seaborn datasets linked above.
1. Our example uses penguins.
1. Add code to app_data.py that will return the iris dataset as well.

## Run app_data.py

When viewing the repo folder in VS Code, click Terminal / New Terminal to open a terminal window.
It will open in the root project folder, i.e., cintel-03-data.


🚀 Rocket Tip: GitHub has an [awesome-public-datasets repo](https://github.com/awesomedata/awesome-public-datasets) listing many public datasets.


🚀 Rocket Tip: Consider organizing your data into a 'data' folder. Joining folder paths is not easy - Windows uses backslash, Mac uses forward slash. When working with paths, use `pathlib` from the Python standard library. The joinpath() method is a platform-independent way to join folder paths.
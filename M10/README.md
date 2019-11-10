In [this](https://github.com/yuleidner/Katz_Data_Analytics/blob/master/M10/M10%20PROJECT.ipynb) Notebook, I will ingest NYC's open dataset on Car Crashes, and perform some data aggregation.


* Data: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95

I made use of the following functions:

pd.to_datetime()
groupby()
agg(['count', 'mean', 'std'])
sum()
index()
pd.Grouper(freq="Y")
pd.DataFrame
plt.plot

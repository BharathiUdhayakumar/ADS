# ADS_phase1
#Covid vaccine analysis project phase 1
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import linear regression
from sklearn.model_selection import train_test_split

data_rea((ding=pd.read_csv("country_vaccinations_by_manufacturer.csv")
print(data_reading)
print(data_reading.shape())
print(data_reading.describe())
print(data_reading.valuecounts())

data_reading=pd.series(np.arange(1,51))
print(data_reading.head(6))
data_reading=pd.series(np.arange(1,51))
print(data_reading.tail(6))

data_reading=pandas.get_dummies(file_data,columns=["vaccine"])
print("data_reading")

y = list(data_reading.population)
plt.boxplot(y)
plt.show()
plt.scatter(data_reading["location"],data_reading["total_vaccinations"])
plt.xlaabel(location)
plt.xlabel(total_vaccinations)
plt.show()
vacc_amount = vacc_amount.sort_values('total_vaccinations_per_hundred', ascending=False)

plt.figure(figsize=(9, 12))
sns.bar(vacc_amount.index, vacc_amount.total_vaccinations_per_hundred, color = 'r')

plt.ylabel('Number of vaccinated people per hundred')
plt.xlabel('Countries')
plt.show()

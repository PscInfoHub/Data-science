# Data-science
This is Learning Repository
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
dataset=pd.read_csv(r"C:\Users\User\Desktop\data\iris.csv")
dataset.head(3)
dataset["species"].unique()
sns.pairplot(data=dataset,hue="species")
plt.show()

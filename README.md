# Breast-Cancer-in-ML
Developed a ML model using Logistics regression to diagnose Breast cancer Wisconsin diagnosis dataset achieved accurate classification upto 97%
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
data = pd.read_csv("data.csv")
print (data.head)

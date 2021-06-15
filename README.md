# Matplotlib Ex1---arange()
import matplotlib.pyplot as plt
import numpy as np

X = np.arange(0 , 361 , 90)
Y = np.sin(X)

plt.plot(X , Y  , ls = ':' , lw = '3' , c = 'r')

# Perovskite-Device-Doctor
Identification of the Dominant Recombination Process for Perovskite Solar Cells Based on Machine Learning.

# Installation:

To run the Jupyter Notebook, please install the following:
Anaconda (https://www.anaconda.com/distribution/), which already consists of Jupyter Notebook, NumPy, pandas, matplotlib, seaborn, pickle, scikit-learn,joblib.  
Jupyter Notebook (https://jupyter.org/install.html)  
There are several packages and/or libraries that need to be installed to run the notebook:

NumPy (https://docs.scipy.org/doc/numpy/user/install.html)  
Pandas (https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)  
Matplotlib (https://matplotlib.org/users/installing.html)  
Seaborn (https://seaborn.pydata.org/installing.html)  
Pickle (https://docs.python.org/3/library/pickle.html)  
Scikit-learn (https://scikit-learn.org/stable/install.html)  
Joblib (https://joblib.readthedocs.io/en/latest/installing.html)  
Graphviz (https://pypi.org/project/graphviz/)  

# Data
Note that the dataset saved in the .csv files dataset1 to 5 consist of over 10<sup>5</sup> simulated perovskite solar cells with their performance (V<sub>OC</sub>,J<sub>SC</sub> and FF) at (0.1,0.18,032,0.56,1) sun illuminations as well as the ideality factor (n).  
This dataset was built using drift-diffusion simulation using open-source code SIMsalabim.  
(https://github.com/kostergroup/SIMsalabim)

# Running

After installing all the necessary packages run the Jupyter Notebook by running all cells.

# Available ML algorithms

The default Jupyter Notebook contains the results for Decision Tree classifier (scikit-learn) and Random Forest Classifier (scikit-learn).
However, the code is built such as other types of classifiers can also be used easily.
# Author

Vincent M. Le Corre

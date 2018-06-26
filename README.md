![Python](https://img.shields.io/badge/python-3.x-orange.svg)
![MIT](https://img.shields.io/github/license/mashape/apistatus.svg)
![Type](https://img.shields.io/badge/Machine-Learning-red.svg) ![Type](https://img.shields.io/badge/Type-Spervised-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-yellowgreen.svg)

### Install

This project requires **Python 3.1** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Scikit-Learn](http://scikit-learn.org/stable/)
- [Matplotlib](http://matplotlib.org/users/installing.html/)
- [Seaborn](https://seaborn.pydata.org/installing.html/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.
### Run

In a terminal or command window, navigate to the top-level project directory `iris-dataset/` (that contains this README) and run one of the following commands:

```bash
ipython iris_SVM.ipynb
```  
or
```bash
jupyter notebook irisAnalysis_kNN.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The dataset used in this project is included as `iris.csv`. This dataset is a freely available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/). This dataset has the following attributes:

**Features**
1.  `Features`: SepalLengthCm , SepalWidthCm, PetalLengthCm, PetalWidthCm

**Target Variable**

4. `Target`: Species

### Outcome

We basically used 3 types of classifiers to predict the outcome of the IRIS types.

**kNN**
The accuracy score turned out to be 1 . This might be due to the less number of data in the datasets since in the real life situations the datasets we deal with has data over 100000 entries.

**SVM**
The accuracy of SVM classifier turned out to be

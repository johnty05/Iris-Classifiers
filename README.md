### Install

This project requires **Python 2.7** and the following Python libraries installed:

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

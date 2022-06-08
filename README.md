# BigDataClass-ACE-Sem-II-2021-2022
This repository contains the teaching material for the BigBioDataClass-ACE Semester-2 Year: 2021-2022

# Resources and books to read.

The choice is up to the student on how they are going to learn, whether by reading books or by downloading codes that are pre-built so they can work along as they grow.

# How to use this material
- Please install anaconda from this [link](https://www.anaconda.com/products/distribution)
- Please install git on your machine using this [link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Get a github account: in order to clone this material to your machine please get a github account.

# Cloning the repository to your local machine
- To clone this information to your local machine please use this command on your terminal.

```
git clone https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

```
- Launch anaconda navigator and go to the folder where you downloaded the repository and get started.


---

# Articles to read

- [Article on how to learn data science quickly.](https://towardsdatascience.com/use-these-tools-to-learn-data-science-faster-8f3bb22371ba)
- [Algorithms You Should Know](https://medium.com/codex/11-ml-algorithms-you-should-know-in-2021-8fecbd3a2a1a)
- [Build Your First Model](https://python.plainenglish.io/create-your-first-machine-learning-module-with-python-a3e2ba39312a)
- [Skew Tutorial](https://pub.towardsai.net/skewness-and-kurtosis-explanation-in-detail-along-with-cheat-sheet-4ad2373169a8)
- [Analytics Vidhya Skew ReadUp](https://www.analyticsvidhya.com/blog/2020/07/what-is-skewness-statistics/)
- [This article speaks about Bagging, Boosting and Stacking](https://towardsdatascience.com/ensemble-methods-bagging-boosting-and-stacking-c9214a10a205)

- [Bagging and Boosting Articles](https://towardsdatascience.com/ensemble-learning-bagging-boosting-3098079e5422)

- [Overfitting and Underfitting](https://medium.com/greyatom/what-is-underfitting-and-overfitting-in-machine-learning-and-how-to-deal-with-it-6803a989c76)

- [More Overfitting and Underfitting](https://towardsdatascience.com/what-are-overfitting-and-underfitting-in-machine-learning-a96b30864690)

---

## Python Data Science Handbook

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)

This repository contains the entire [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do), in the form of (free!) Jupyter notebooks.

![cover image](notebooks/figures/PDSH-cover.png)

## How to Use this Book

- Read the book in its entirety online at https://jakevdp.github.io/PythonDataScienceHandbook/

- Run the code using the Jupyter notebooks available in this repository's [notebooks](notebooks) directory.

- Launch a live notebook server with these notebooks using [binder](https://beta.mybinder.org/): [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)

- Buy the printed book through [O'Reilly Media](http://shop.oreilly.com/product/0636920034919.do)

## About

The book was written and tested with Python 3.5, though other Python versions (including Python 2.7) should work in nearly all cases.

The book introduces the core libraries essential for working with data in Python: particularly [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org), and related packages.
Familiarity with Python as a language is assumed; if you need a quick introduction to the language itself, see the free companion project,
[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython): it's a fast-paced introduction to the Python language aimed at researchers and scientists.

See [Index.ipynb](http://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb) for an index of the notebooks available to accompany the text.

## Software

The code in the book was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.

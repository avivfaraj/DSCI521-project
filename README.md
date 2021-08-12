# Heart Disease Analysis

### by: Aviv Farag, Hope Birdsong, Joshua Geller and Willie Hood

---

## Table of Contents
 * [Abstract](#abstract-)
 * [Python Packages](#python-packages-)
 * [Setup and running the code](#setup-and-running-the-code)
 * [Acknowledgements](#acknowledgements)
 

---

## Abstract: 
This research presents a data analytics approach and breakdown of the dataset containing heart disease patient symptoms. 
Our analysis explores heart disease among a population of males and females between 29 and 77 years of age using risk factors that determine its prevalence.
We used popular python libraries to demonstrate our data interpretation and exploration.
We were able to plot various forms of the dataset to show which symptoms were most important to the audience.
We were able to leverage tensorflow and other python machine learning packages to overall precision of the dataset. 

---

## Python Packages:
1. pandas <br>
 `import pandas as pd`
1. numpy <br>
`import numpy as np`
1. matplotlib.pyplot <br>
`import matplotlib.pyplot as plt`

1. sklearn.metric:
	1. f1_score
	2. precision_score
	3. recall_score
1. sklearn.linear_model: LogisticRegression
1. sklearn.model_selection: train_test_split
1. sklearn.pipline: Pipline <br>
```
from sklearn.metrics import f1_score, precision_score, recall_score
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.pipeline import Pipeline 
```

---

## Setup and running the code:
Open the jupyter notebook and ensure to run the first cell containing the git clone of the repo, if that cell is unavailable clone the repo using the following command:<br>
In jupyter notebook:<br>
	`!git clone https://github.com/avivfaraj/DSCI521-project.git`
	
Or in the terminal:<br>
	`git clone https://github.com/avivfaraj/DSCI521-project.git`
	
After cloning the repo, run each cell in one at a time in the order that they are presented. You can run the whole notebook in a single step by clicking on the menu Cell -> Run All.<br>

The first two sections are packages and functions which are required for the code to run. Make sure to run those two sections before running the program. 

---

## Acknowledgements

[UCI Heart Disease Data Set](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

**Creators:**

Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

**Donor:**
David W. Aha (aha '@' ics.uci.edu) (714) 856-8779


# Titanic: Machine Learning from Disaster
# Supervised Learning
## Project: Predict survival on Titanic

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend to install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The Titanic passenger survival data consist of approximately 1,300 data points with 11 features.

**Features**
- `PassengerId`: ID of passenger
- `Pclass`: Passenger's  Class
- `Age`: Passenger's Age
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard
- `Name`: Passenger's name
- `Sex`: Passenger's sex
- `Ticket`: Ticket number
- `Fare`: Passenger's Fare in GBP
- `Cabin`: Cabin
- `Embarked`: Port of embarkation

**Target Variable**
- `survived`: survival (0 -> not survive, 1-> survive)
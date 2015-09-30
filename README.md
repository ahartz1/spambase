# Classifying spam

## Description

Use the Spambase dataset to classify spam. This data is already parsed down from email to features.

## Objectives

### Learning Objectives

After completing this assignment, you should understand:

* Simple Bayesian analysis
* The importance of separating training and test data

### Performance Objectives

After completing this assignment, you should be able to:

* Create a Bayesian classifier
* Train your classifier
* Test your classifier

## Normal Mode

Go to the UCI Machine Learning repository and [download the Spambase dataset](https://archive.ics.uci.edu/ml/datasets/Spambase). Make sure you [read the documentation for the data](https://archive.ics.uci.edu/ml/machine-learning-databases/spambase/spambase.DOCUMENTATION). This explains what the attributes are in the data file.

Subsample the data set so 60% is training data and 40% is test data. You can subsample however you like, including splitting the original file. Just make sure that you have a representative data set. (The original is about 60% not-spam and 40% spam.)

Then write code to classify the data into spam and not-spam, training with your training data and testing on your test data.

<!-- ## Hard Mode

In addition to the normal mode requirements, try reducing or changing your features in order to get better results.

Find another source of spam/not-spam data, break it down into features, and perform the same exercise as above. How well does your algorithm perform on the new data? -->

## To View This Notebook
Just click on the `spambase.ipynb` file above.

## To Run This Notebook
### System Requirements / Installation

* You will need to have **python&nbsp;3** installed on your machine. See [python's site](https://www.python.org/) for details.

* Clone this repo onto your machine.

* Go to the UCI Machine Learning repository and [download the Spambase dataset](https://archive.ics.uci.edu/ml/datasets/Spambase).

* You will need to make sure that you have a virtual environment running in the folder that you intend to work from. [See this site for details if you're not familiar.](http://docs.python-guide.org/en/latest/dev/virtualenvs/) **Complete this step before attempting the below.**

* In your command-line program (such as Terminal on Mac&nbsp;OS&nbsp;X), navigate into the newly created repo. By default, this will be called `spambase`. Install the requirements file by runnning **`pip install -r requirements.txt`**.

### Opening the Notebook
* Using a command-line program, navigate to the folder containing the downloaded file and run the following line: **`ipython notebook spambase.ipynb`**

* **Note:** This will open in a browser window and take over the command-line program's window until you close out of IPython Notebook. If you have closed your browser window, but your command line is still running the notebook, kill the process by pressing `Ctrl+C` or quitting the program entirely.

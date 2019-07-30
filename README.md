## Spam Delection

### Description

This project uses the Naive Bayes Machine Learning algorithm to create a model that can classify dataset SMS messages as spam or not spam, based on the training we give to the model. It is important to have some level of intuition as to what a spammy text message might look like.

#### What are spammy messages?
Usually they have words like 'free', 'win', 'winner', 'cash', 'prize', or similar words in them, as these texts are designed to catch your eye and tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!

Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. We will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.

This projecs uses the sklearn implementation of the Naive Bayes and also discuss approaches to build Naive Baye from scratch.


### Install

This project requires **Python 3.7** and the following Python libraries installed:


- [Jupyter Notebook (IPython) 4.10.0](https://ipython.org/)
- [NumPy 1.16.4](http://www.numpy.org/)
- [Pandas 0.24.2](http://pandas.pydata.org/)
- [matplotlib 2.2.4](http://matplotlib.org/)
- [scikit-learn 0.19.2](http://scikit-learn.org/stable/)

### Code

Template code is provided in the `spam-detection.ipynb` notebook file.

### Run

In a terminal or command window, navigate to the top-level project directory `spam-detection/` (that contains this README) and run one of the following commands:

```bash
ipython notebook spam-detection.ipynb
```  
or
```bash
jupyter notebook spam-detection.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

This project uses a [dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) from the UCI Machine Learning repository which has a very good collection of datasets for experimental research purposes. The direct data link is [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00228/).


 **Here's a preview of the data:** 
 
![SMS](images/dqnb.png "SMS")

The columns in the data set are currently not named and as you can see, there are 2 columns. 

The first column takes two values, 'ham' which signifies that the message is not spam, and 'spam' which signifies that the message is spam. 

The second column is the text content of the SMS message that is being classified.

# Spam Mail Detection:

## Table of Content

- [Demo](#demo)
- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation](#installation)
- [Directory Tree](#directory-tree)
- [Technologies Used](#technologies-used)
- [Team](#team)
- [Credits](#credits)


## Overview

This is an simple NLP project in which the model is able to predict the incoming mail whether it is spam or not spam(ham). As we seen in gmail automatically the mail is classified and stored in spam or inbox so this project is prototype.

## Technical Aspect

This project is divided into two part:

1. Training a machine learning model.
2. Building and hosting a Flask web app on Heroku.
3. Used WordLammitizer and Stopwords.
4. We can also perform Hyperparammeter tunning but using NaiveBayes the accuracy is all other parameter are having high rate

## Installation

The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

```bash
pip install -r requirements.txt
```

```
├── static
│   ├── style.css
├── templates
│   ├── home.html
|   ├── result.html
├── requirements.txt
├── Procfile
├── README.md
├── SMSSpamCollection.csv
├── app.py
├── nlp model.pkl
├── nlts.txt
├── transform.pkl
├── SpamClassifier.ipynb
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" width=200>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org)

 [<img target="_blank" src="https://openjsf.org/wp-content/uploads/sites/84/2019/10/jquery-logo-vertical_large_square.png" width=100>](https://jquery.com/)

                                              

## Credits

- [Dataset Download](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

## Copyright
Sanjoy Biswas

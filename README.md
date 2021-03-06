# Spam-Classifier-NLP

## Overview
This is a flask app that predicts whether a text message is "Spam" or not spam("Ham").

## Project Description:
Text pre-processing was performed by removing stop words from the data and Stemming was performed. Bag of Words was used to convert the words into vectors. Multinomial Naïve Bayes was used for model building after testing with other classification algorithms. Model was evaluated using accuracy score, confusion metrics and classification report.
Model gave an accuracy of 98.5% on the test data and the number of False positives and False negatives were also very less. We can say that the model performed really well.

## Installation
The Code is written in Python 3.7.3 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

##### 1. First create a virtual environment by using this command:
```bash
conda create -n myenv python=3.7
```
##### 2. Activate the environment using the below command:
```bash
conda activate myenv
```
##### 3. Then install all the packages by using the following command
```bash
pip install -r requirements.txt
```
##### 4. Then, in cmd or Anaconda prompt write the following code:
```bash
python app.py
```
##### Make sure to change the directory to the root folder.  

## Deployment on GCP
Login or sign up in order to create virtual app and many more things. Free tier account on Google console provides $300 credit for one year. For application deployment download the Google SDK installer.

## Frontend using HTML,CSS and Backend using Flask

https://spamclassifier-sm.el.r.appspot.com

![image](https://user-images.githubusercontent.com/75041273/122086151-0fd82c00-ce21-11eb-8370-ac4d45349b59.png)

![image](https://user-images.githubusercontent.com/75041273/122086823-b290aa80-ce21-11eb-8967-287581df5a94.png)

![image](https://user-images.githubusercontent.com/75041273/122086858-bf150300-ce21-11eb-8815-49e582e75114.png)

![image](https://user-images.githubusercontent.com/75041273/122086896-ca682e80-ce21-11eb-947c-195d87a36381.png)

Currently app disabled,since GCP is chargeable.

![Screenshot (10)](https://user-images.githubusercontent.com/75041273/122088696-9db51680-ce23-11eb-90e7-b829a3315bed.png)

## Technology Stack

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/)  [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/)


## Further Changes to be Done

- [ ] Deploying the Web Application on Cloud.
     - [ ] AWS EC2 Instance
     - [ ] Azure
     - [ ] Heroku


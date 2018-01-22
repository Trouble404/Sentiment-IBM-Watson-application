# Sentiment-IBM-Watson-application
Natual language understanding api **v-2017-02-27**
# Gneral guide
## step 1: input the text that you want to check
![image](https://github.com/Trouble404/Sentiment-IBM-Watson-application/blob/master/readme_add_pic/check.PNG)
## step 2: check the result
![image](https://github.com/Trouble404/Sentiment-IBM-Watson-application/blob/master/readme_add_pic/result.PNG)
---

## Introduction
* [IBM Watson Natural Language Classifier](https://www.ibm.com/watson/services/natural-language-classifier/)   

## Preparation

[IBM Watson Natural Language Classifier](https://www.ibm.com/watson/services/natural-language-classifier/)   

* VERSION
* USERNAME
* PASSWORD

### 1 Apply IBM accout
The step to obtain key used in semantic analysis:
*  Open [main page](https://console.bluemix.net/) of IBM Cloud and register a new account
*  Log in with registered account and find **Natural Language Understanding** in the dashboard.
*  The sentimental service can be applied in [here](https://console.bluemix.net/catalog/services/natural-language-understanding/)
*  The username and password can be obtained by following the instruction now.

### 2 Dependencies installing
After setting up all the configurations, the first thing is to install all the dependencies. For Python, we used **Pip** to manage all the backend dependencies. For JavaScript, we used **Npm/Yarn** to do the frontend denpendencies management.
1. Clone the repository
```bash
git clone https://github.com/Trouble404/Sentiment-IBM-Watson-application.git
```
2. Install all the dependencies. 
Before you install the python dependencies, you might to create a virtual enviorment first.  
```bash
pip install virtualenv env
virtualenv env
source env/bin/activate
pip install -r -requirements.txt
```
After all the python dependencies installed, you should be able to run the **app.py**
```bash
python app.py
```

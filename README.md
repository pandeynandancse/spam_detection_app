# Spam Detection Application


## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Installation](#installation)
  * [Run](#run)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)
  * [Credits](#credits)


## Demo
Link: [https://spam-detector-ml-app.herokuapp.com/](https://spam-detector-ml-app.herokuapp.com/)

[![](https://i.imgur.com/z3LLN7V.png)](https://indian-currency-prediction.herokuapp.com/)



## Overview
This is a simple spam detection application developed using sklearn. The trained model (`model/model.h5`) takes string of message as an input and predicts the class of message as spam or not spam.



## Directory Tree 
```
├── model
|    ├── nlp_model.pkl
|    ├── transform.pkl
├── static
|    ├── style.css
├── templates
|    ├── home.html
|    ├── result.html
├── LICENSE
├── Procfile
├── README.md
├── app.py
├── requirements.txt

```


in procfile :
app:app means app.py file : app variable of flask




two files are important for heroku : procfile and requirements.txt

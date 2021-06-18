# Athletes Image Classification

## Table of Content

* Demo
* Overview
* Technical Aspect
* Installation
* Directory Tree
* Technologies Used

## Demo
Link: <http://ec2-3-16-124-131.us-east-2.compute.amazonaws.com/>

[![web1](https://user-images.githubusercontent.com/84587490/122577321-b449b080-d063-11eb-9ee7-a8ead7156f4b.JPG)](http://ec2-3-16-124-131.us-east-2.compute.amazonaws.com/)

## Overview

This is a simple athletes image classification Flask app. The trained model takes an image as an input and classifes sports personalities. I restrict classification to only 5 people.

  1. Henrikh Mkhitaryan (captain of the Armenian national football team)
  2. Maria Sharapova (winner of five Grand Slam titles)
  3. Arthur Abraham (IBF middleweight champion from 2005 to 2009)
  4. Serena Williams (won more Grand Slam singles titles (23) than any other woman or man)
  5. Cristiano Ronaldo (won 5 Ballon d'Or, first player to ever win the Golden Boot in England, Spain and Italy)

## Data
The image dataset has been collected using fatkun chrome extension. It has 6941 observations.

## Technical Aspect
This project is divided into two part:

   1. Training a model using Support Vector Machine.
   2. Building and hosting a Flask web app on AWS.

## Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

## Directory Tree
<pre>
├── UI 
│   ├── images
│   ├── app.css
│   ├── app.html
│   ├── app.js
│   ├── dropzone.min.css
│   ├── dropzone.min.js
├── images_dataset
│   ├── Arthur_Abraham
│   ├── Cristiano_Ronaldo
│   ├── Henrikh_Mkhitaryan
│   ├── Maria_Sharapova
│   ├── Serena_Williams
├── model
│   ├── dataset
|   ├── opencv
|       ├── haarcascades   
|   ├── test_images
├── opencv
|   ├── haarcascades
├── server
|   ├── artifacts
|       ├── class_dictionary.json
|       ├── saved_model.pkl
|   ├── opencv
|       ├── haarcascades
|   ├── test_images
|   ├── __init__.py
|   ├── b64.txt
|   ├── server.py
|   ├── util.py
|   ├── wavelet.py
├── Athletes _Image_Classification.ipynb 
├── README.md
└── requirements.txt
</pre>

## Technologies Used

  1. Numpy and OpenCV for data cleaning
  2. Matplotlib & Seaborn for data visualization
  3. Sklearn for model building
  4. Jupyter notebook, visual studio code and pycharm as IDE
  5. Python flask for http server
  6. HTML/CSS/Javascript for UI
  
[![python](https://camo.githubusercontent.com/3cdf9577401a2c7dceac655bbd37fb2f3ee273a457bf1f2169c602fb80ca56f8/68747470733a2f2f666f7274686562616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667)](https://www.python.org/)  

[![sklearn](https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png)](https://scikit-learn.org/stable/)
[![flask](https://user-images.githubusercontent.com/84587490/119322349-9cfaeb80-bc8e-11eb-8b87-c8f7b27e3b2f.png)](https://flask.palletsprojects.com/en/2.0.x/)
[![cOpenCV](https://user-images.githubusercontent.com/84587490/122578843-574efa00-d065-11eb-8de5-4511aba3a076.png)](https://opencv.org/)
[![AWS](https://user-images.githubusercontent.com/84587490/122578693-2d95d300-d065-11eb-846b-6baf2be99eb1.png)](https://aws.amazon.com/?nc2=h_lg)







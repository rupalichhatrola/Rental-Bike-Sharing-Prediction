# Rental Bike Sharing Predicton
This is a  project to elaborate how Machine Learning Models are deployed in production using Flask API

Prerequisites

**Prerequisites**
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.


**Project Structure**

This project has four major parts :


app.py - This contains Flask APIs that receive air foil details through GUI or API calls, computes the precited value based on our model and returns it.


templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted Bike Sharing regression.

**Running the project**

Ensure that you are in the project home directory. Create the machine learning model by running below command -



This would create a serialized version of our model into a file model.pkl



1. Run app.py using below command to start Flask API

2. python app.py

3. By default, flask will run on port 5000.



Navigate to URL http://localhost:5000

You should be able to view the homepage as below :alt text



Enter valid numerical values in all  input boxes and hit Predict.



If everything goes well, you should be able to see the predicted vaule on the HTML page! alt text

# Technologies and IDEs Used.

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img src="https://upload.wikimedia.org/wikipedia/en/a/a9/Heroku_logo.png" width="180" height="73">](https://en.wikipedia.org/wiki/Heroku) [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/120px-HTML5_logo_and_wordmark.svg.png" width="100" height="100">](https://en.wikipedia.org/wiki/HTML) [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/120px-CSS3_logo_and_wordmark.svg.png" width="75" height="100">](https://en.wikipedia.org/wiki/CSS)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/300px-Pandas_logo.svg.png" width="180">](https://en.wikipedia.org/wiki/Pandas_(software)) [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/220px-NumPy_logo_2020.svg.png" width="180">](https://en.wikipedia.org/wiki/NumPy) [<img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/56/Matplotlib_logo.svg/300px-Matplotlib_logo.svg.png" width="180" height="80">](https://en.wikipedia.org/wiki/Matplotlib) [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/220px-Scikit_learn_logo_small.svg.png">](https://en.wikipedia.org/wiki/Scikit-learn)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/250px-Jupyter_logo.svg.png" width="88" height="100">](https://en.wikipedia.org/wiki/Project_Jupyter) &nbsp; &nbsp; [<img src="https://upload.wikimedia.org/wikipedia/en/thumb/d/d2/Sublime_Text_3_logo.png/150px-Sublime_Text_3_logo.png" width="100" height="100">](https://en.wikipedia.org/wiki/Sublime_Text) &nbsp; &nbsp; [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a1/PyCharm_Logo.svg/64px-PyCharm_Logo.svg.png" width="100" height="100">](https://en.wikipedia.org/wiki/PyCharm)











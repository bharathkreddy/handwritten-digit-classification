<a href="https://www.bharathkreddy.com"><img align="left" src="https://i.imgur.com/axjt3Qe.png" alt="WWW.BHARARTHKREDDY.COM" title="www.bharathkreddy.com"></a>
# [www.bharathkreddy.com](https://www.bharathkreddy.com)


## Digit Recognizer
Simple Flask App to recongize Handwrtten Digits.
I have used Heroku with Gunicorn server.

The model is a simple CNN architecture. It is converted to ONNX format for easy inference using opencv.
The model is in ONNX format. 

## Check out the app.
# [Launch Application](https://bharathkreddy.herokuapp.com/)


## Running locally.

Clone the repo

``` git clone https://github.com/bharathkreddy/handwritten-digit-classification.git ```

Install the requirements.

``` pip install -r requirements.txt ```

And you are done. You can now use the entire codebase.

While developing use the flask server

``` python ./web_app.py ```

While deploying locally please use waitress by running

``` python ./serve_waitress.py ```






from flask import Flask, jsonify, request
from flask_httpauth import HTTPBasicAuth
from model import DBconn
import sys, flask


app = Flask(__name__)

@app.route('/')
def category():

    return "hello world"


if __name__ == '__main__':
    app.run (debug=True)

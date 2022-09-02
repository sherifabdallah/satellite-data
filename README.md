

# Satellite-image-based surface reconstruction in `MicMac`

## Goal 

In this tutorial we will introduce you to satellite image processing in MicMac. The goal of the exercise is to compute the surface and generate an orthohoto given a set of *modern* satellite images and their RPC geolocalisations. After setting-up MicMac and downloading the dataset, the pipeline is as follows:
  1. Tie-points extraction
  2. RPC-bundle adjustement
  3. Surface computation
  
## Table of Content
- [Geekshub](#geekshub)
  * [Tools](#tools)
  * [How to run](#how-to-run)
  * [Author](#author)

## Tools
1. Python
2. Micmac
3. Opencv
4. Matplotlib
5. Notebooks
6. Numpy


## How to run
* Enter the directory where the script is located then type the following to the console
```sh
$ git clone https://github.com/sherif-abdallah/satellite-data satellite-data
```
* Install Python 3.8 venv, pip and compiler

```sh
$ sudo apt-get install python3.8 python3.8-venv python3-venv
```

* Create a virtual environment to install dependencies in and activate it:

```sh
$ python3.8 -m venv venv
$ source venv/bin/activate
```

* Then install the dependencies:

```sh
(venv)$ cd satellite-data
(venv)$ python -m pip install --upgrade pip
(venv)$ python -m pip install numpy open opencv-python matplotlib notebook
```
Note the `(venv)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.


* Finally open  the Jupyter Notebook Script
```sh
(venv)$ python -m notebook notebook.ipynb
```
* And navigate to `http://127.0.0.1:8888`.

## Author
[Sherif Abdullah](https://github.com/sherif-abdallah)

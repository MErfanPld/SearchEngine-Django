# SearchEngine
Search Engine source code written in python (django), javascript, css and html.

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/MErfanPld/SearchEngine.git
$ cd "dir"
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv -p python3 venv 
$ source venv/bin/activate
```

Then install the dependencies:

```sh
(venv)$ pip install -r requirements.txt
```
Note the `(venv)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.

Once `pip` has finished downloading the dependencies:
```sh
(venv)$ cd "dir"
(venv)$ python manage.py runserver
```

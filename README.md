# Instructions

## Install Python & Pipenv

### Mac

```bash
brew install python
pip install --user pipenv
```

### Linux (Ubuntu)

```bash
sudo apt-get install python
pip install --user pipenv
```

## Clone the repository

```bash
git clone mygithub:thebubbafeet/AI.git
```

## Setup Virtual environment

```bash
pipenv shell
#or
python3 -m venv venv
```

## Use requirements file to freeze & install dependencies

```bash
# To capture (freeze) dependencies already installed locally
pip freeze > requirements.txt

#Then you can use the following to install the exact same on another computer
pip install -r requirements.txt
```

## Install dependencies

```bash
pipenv install -r requirements.txt
#or
pip install -r requirements.txt

#These are all the same. The -m is the module (not needed)
python3 -m pip install tensorflow
#or
pip install tensorflow
#or
pip3 install tensorflow
```

## Run

```bash
export FLASK_APP=app
flask run
```

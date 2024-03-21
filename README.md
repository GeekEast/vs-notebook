# Jupyter Notebook


## Install
check your python version, it should be higher than `3.10`
```sh
python --version
```
if not, please install via
```sh
brew install python@3.10
```

### Use virtualenv
use virtualenv as env manager for python, and run the following commands to init env and install dependencies.
```sh
pip install virtualenv
npm run venv:init
```

### Check if successfully setup
```sh
source .venv/bin/activate
npm run venv:which & npm run lint
```

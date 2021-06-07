# Vision Step by step installation

## Reference install
```
This is a step by step guide to install vision on your local system.

- Install python
- install python virtual environment
- install vision
```

### Install Python on Windows or Mac
Vision is tested with python 3.6.8, therfore use it.
- Download  <a href="https://www.python.org/downloads/release/python-368/" target="_blank">`python 3.6.8 download page`</a> 
- install python 3.6.8
- Check if the version is 3.6.8 : python --version (depending on your installation it could be python3 --version)

### install python virtual environment macOS (tested on macOS Mojave 10.14.1 Macbook Air 8 GB RAM)
- REMARK: replace python with python3 if needed.
- check if 'python --version' shows the correct python version 3.6.8 
- python -m venv vision
- cd vision
- source bin/activate
- pip3 install nemonet
- brew install graphviz (install <a href="https://brew.sh" target="_blank">`brew`</a>)

### install python virtual environment windows (tested on windows 10)
- REMARK: replace python with python3 if needed.
- check if 'python --version' shows the correct python version 3.6.8 or later
- python -m venv vision
- cd vision
- Scripts\activate
- pip3 install nemonet
- don't forget to (install <a href="https://graphviz.org" target="_blank">`graphviz`</a>) 

### install python virtual environment Linux (tested on Ubuntu 20.04 LTS)
- REMARK: replace python with python3 if needed.
- check if 'python --version' shows the correct python version 3.6.8
- sudo apt-get install python3-venv
- python -m venv vision
- cd vision
- source bin/activate
- pip3 install nemonet (ignore the error messages if listing "RROR: Failed building wheel for...")
- sudo apt-get install python3-tk python3-dev
- sudo apt install graphviz
- sudo apt-get install scrot

### install Chrome and chromedriver
set the location of the chromedriver in the path

### clone the visiontestfiles
- <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git" target="_blank">`Getting Started - Installing Git`</a>
- git clone https://github.com/janrum/visiontestfiles.git


### execute the sample
in terminal of command box type en enter : vision selenium-dev .This should open your chrome browser and get the website and search for 'vision'.






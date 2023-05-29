# CoffeeFetch
## A lightweight system information grabber written in Python

## Introduction
CoffeeFetch is a system information grabber for Unix systems that fetches your system information and displays it to the screen. This is a lightweight package and is built to be run on systems without the use of a Window Manager or Desktop Enviornment and is displayed directly in in TTY. It will attempt to grab you CPU model, CPU frequency, current RAM consumption, current disk usage, Operating System, CPU architecture, IP Address, hostname, and OS version.

## Installation
It is required to use Python 3.7 or greater for this package. 

Firstly, clone this repository:
```
git clone https://github.com/TeaPixl/CoffeeFetch/
cd CoffeeFetch
```
Then, install the required Python modules
```
pip install -r requirements.txt
```
Build and install the .whl file
> Change the X version you have
```
python3 -m build
cd dist/
pip install coffeefetch-X.X.X-py3-none-any.whl
```
OR

```
pip install coffeefetch
```

## Usage
To use CoffeeFetch, simply type into your terminal:
```
python3 -m coffeefetch
```

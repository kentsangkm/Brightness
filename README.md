# Brightness Controller

This is version 3 of Brightness Controller, ported to Python 3 and PySide 2. It supports an arbitrary number of displays!

If you like this, do not forget to give us a Star!  [![GitHub stars](https://img.shields.io/github/stars/lordamit/brightness.svg?style=flat-square)](https://github.com/lordamit/brightness/stargazers) People already did!

![](img/BrightnessController.gif)

## Installation via PPA

Thanks to package maintainer @apandada1, we have PPA repository For Ubuntu and likewise users:

```bash
sudo add-apt-repository ppa:apandada1/brightness-controller
sudo apt update
sudo apt install brightness-controller
```

## Manual Installation
First, install PySide2.

```bash
sudo apt install python3-pyside2.qtcore python3-pyside2.qtgui python3-pyside2.qtwidgets python3-pyside2.qtnetwork
```
Somtimes it is not enough to install and integrate PySide2, so you might also try installing PySide2 using pip3.

```bash
pip3 install PySide2
```

Next, download the latest zip file from [here](https://github.com/lordamit/Brightness/archive/master.zip).

Extract it and open a terminal. Change directory to the `Brightness` folder. Next type this command:

```bash
python3 src/init.py
```

Achean also created a detailed tutorial on how to install it in Debian based on his experience. You can find it [here](https://github.com/LordAmit/Brightness/issues/98#event-1218811468).

## Features

The following features are implemented:

1. Brightness Control
1. Saving color profile
1. Loading color profile


We are working on the following features:

1. Auto-loading of color and brightness settings
2. Checking for update

It should be mentioned that through color profile Red, Green and Blue color ratios are changed in the screen.

## Dependencies
There are several dependencies:

1. python3-pyside2.qtcore, python3-pyside2.qtgui, python3-pyside2.qtwidgets, python3-pyside2.qtnetwork
2. xrandr support in your system
3. python3

## Bugs

Please test v3. Reporting bugs is appreciated.

## Can I have just brightness sliders - For Four displays?
We got you covered! Try version 1.2.8/simpler version of Brightness Controller.
![](img/brightness-controller-1.png)

To install, simply do this:

```bash
sudo add-apt-repository ppa:apandada1/brightness-controller
sudo apt-get update
sudo apt-get install brightness-controller-simple
```
Further details are available [here](http://lordamit.github.io/Brightness/)

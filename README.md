**POSE** : behavioral tracking using Python and OpenCV
=======================================

**POSE** (**P**ython **O**pen **S**ource **E**thology) is a Python package for tracking the behavior of individual animals. 
The tracker uses OpenCV to automatically extract the location of an animal in a video with adaptive background subtraction. 
It provides a high-level Python API for the analysis of animal behavior and locomotion.

![alt text][screenshot]

[screenshot]: https://github.com/jgraving/pose/blob/master/images/screenshot.png

**Figure 1.** The current frame (left) is subtracted from the background model (middle) to produce a foreground mask (right), which is then used to track the position of the animal over time (left). 

Tutorial
------------

[Click here](https://github.com/jgraving/pose/blob/master/example/pose_tracker_example.ipynb) for an example of how to use POSE 

Installation
------------

Install the development version:
```bash
pip install git+https://www.github.com/jgraving/pose.git
```

Install the latest stable release:
```bash
pip install https://github.com/jgraving/pose/archive/0.1.1.zip
```

Citing
----------
If you use this software for academic research, please consider citing it using this zenodo DOI: 

[![DOI](https://zenodo.org/badge/24020/jgraving/pose.svg)](https://zenodo.org/badge/latestdoi/24020/jgraving/pose)


Dependencies
------------

- [![PyPI](https://img.shields.io/pypi/pyversions/Django.svg?maxAge=2592000?style=flat-square)](http://www.python.org)

- [numpy](http://www.numpy.org/)

- [scipy](http://www.scipy.org/)

- [matplotlib](http://matplotlib.org/)

- [OpenCV 3.1+](http://opencv.org/)

Development
-------------
[https://github.com/jgraving/pose](https://github.com/jgraving/pose)

Please [submit any bugs](https://github.com/jgraving/pose/issues/new) you encounter to the GitHub issue tracker

License
------------
[![PyPI](https://img.shields.io/pypi/l/Django.svg?maxAge=2592000?style=flat-square)](https://github.com/jgraving/pose/blob/master/LICENSE)

Released under a [BSD (3-clause) license](https://github.com/jgraving/pose/blob/master/LICENSE)

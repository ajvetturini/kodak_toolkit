# kodak toolkit
This is a Python-based toolkit for creating simple 2D and 3D plots using Plotly as the backend. Specifically, this kodak toolkit can be used alongside the kodak viewer ([link](https://ajvetturini.github.io/kodak/)) to visualize plots via a user-interface (UI) application.

This package is in **very** active development and it should be expected for code to change quite frequently. A stable build will be released in the near future as more plot types are added. Below is a list of currently supported plot types in this package.

# Features
I am working on adding the Example scripts to this readme, but if you are interested in using kodak now please see the Examples folder. Here are the current supported features of the kodak toolkit:

- A Vite-React enabled UI to editing figures / getting the size correct
- Interactable plotting elements 
- Uses a ".plots" (json) file which can easily be shared amongst collaborators to view figures
- Easy export to SVG / PNG for publications

# How to install
Since this toolkit is in an early build, it is not currently available on PyPi / pip. Therefore, to install (or update) the package, please run the following commands.
1) Create a new virtual environment in anaconda (_recommended_)  
2) Open the terminal and run the following commands in order (you can just copy and paste the whole line. Please note the period on the 3rd bullet)
   - git clone https://github.com/ajvetturini/kodak_toolkit.git
   - cd kodak_toolkit
   - pip install -e .

This should install the kodak_toolkit to your environment which you can then import into a Python file via: \
**from kodak.kodak_creator import KodakPlots**

# Requirements
- Python 3.9
- NumPy
- Plotly

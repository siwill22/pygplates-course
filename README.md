# pygplates-course

This repository contains jupyter notebooks with exercises for the GPlates/pygplates USyd honours course, 2017. 

pygplates is a python library that allows scripting access to the plate tectonic reconstruction functionality of GPlates. The objective is to learn about quantitative spatiotemporal data analysis within a series of problems that involve pygplates, introducing some concepts related to: 
- data analysis in python (array manipulation, writing loops and functions, plotting, accessing data from the web)
- analysing plate tectonic reconstructions themselves, and using plate reconstructions to analyse other 

#
## Background Material
Some basis knowledge of both python and GPlates is beneficial. Useful resources for background are:

### For Python
Two exellent resources for scientists using python for data science can be found here:

https://github.com/jakevdp/WhirlwindTourOfPython

https://github.com/jakevdp/PythonDataScienceHandbook

### For GPlates
The GPlates tutorials can be found at this link:

https://sites.google.com/site/gplatestutorials/

[Note that it is recommended to have access to GPlates at the same time as going through these exercises - it can be much easier to figure out what a pygplates script is doing if you can see how the input data files behave in GPlates] 

### For pygplates
The detailed documentation for pygplates can be accessed here:

https://www.gplates.org/docs/pygplates/

While a set of practical pygplates tutorials are available here:

https://github.com/GPlates/pygplates-tutorials

Many of the code snippets in these tutorials will be directly useful in the exercises for this course

  
#
## pygplates quick start

To use this course material, you need to have access to a computer with a number of python modules installed, including pygplates but also a number of plotting and numerical computation modules, as well as the modules that enable jupyter notebooks to run. The methods to get set up are:

##### Using kitematic [recommended]:
kitematic allows you to use a virtual machine prepared by someone else (and therefore with all the python dependencies already installed and working together) on your own machine, rather than installing these individual bits and pieces directly. 

An overview of how this solution works:
https://github.com/badlands-model/pyBadlands/wiki/Kitematic

For this course, follow these instructions but instead of running the 'pybadlands' container, instead search for 'pygplates-course' in the kitematic search window, and select the one container that should appear.

##### Anaconda/Canopy
Both Anaconda and Canopy are python distributions that can be installed directly on your machine, and includes by default many of the required python modules that we will use (numpy, matplotlib, pandas), but NOT all of them - and in particular, not pygplates.

If you follow this route, then after installing either of these general python distributions, you'll also have to install pygplates yourself:

https://www.gplates.org/docs/pygplates/pygplates_getting_started.html#pygplates-getting-started

as well as a number of modules that may not be included by default in the distribution you selected (e.g. 'Basemap', 'requests')







##

This work shows an early attempt to address a key stakeholder issue which is the classification of products from product descriptions. The IPython notebook shows an early attempt to address this challenge. Included in this work is data analysis, discussion of performance metrics, implementation of a simple text classifier and some classifier parameter tuning. This work is an early version of how an overall project might look, so we included several recommendations for future work.

The report and analysis are both included in the IPython notebook. Users should be able to see all work done by simply opening the notebook. However, if users wish to analyze and expand upon the work, the instructions below detail how to recreate the same Python environment in MacOS.

## Setting up a virtual environment (MacOS)

In order to set up all the dependencies to run the Python code, you will need to first ensure you have all the correct dependencies. In order to do this, we are going to create a virtual environment. If you don't already have virtualenv installed, do so now using the following command:

	python3 -m pip install --user virtualenv

Once you have virtualenv installed, you will create a virtual environment for this project with the following steps:

1. Find out where your default Python3 installation is located:
	which python3
2. Create a new virtual environment set up your virtual environment:
	virtualenv -p /path/to/python3 venv

Be sure to replace /path/to/python3 with the result of the 'which python3' command.

Next, activate the virtual environment:

	source venv/bin/activate
	
Once inside your virtual environment, you will install the dependencies:

	pip3 install -r requirements.txt
	
Create a new kernel for the Jupyter Notebook:

	ipython kernel install --user --name=censusbureau
	
Start Jupyter Notebook and select your notebook to run.

	jupyter notebook

Once inside Jupyter, select kernel > Change kernel > censusbureau to use the virtualenv you'e created.

	
	
	


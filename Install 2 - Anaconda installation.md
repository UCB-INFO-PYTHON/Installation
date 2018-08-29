# Anaconda setup instructions
--
**What is Anaconda and why are we using it?**

We are using the Anaconda distribution of python in order to smooth the process of installing python. There are numerous conflicts that can occur across and within python installations. Anaconda manages the packages to avoid conflicts. It also automatically loads most of the common workhorse packages in one click so you can get to coding.


**1. Download *python 3* from the [Anaconda distribution page](https://www.anaconda.com/download)**

* If you are working on a Linux or MacOS machine, you can choose to download the command line or graphical installer version.
* Windows users should install the graphical package.

## With the graphical installer

* The graphical package can be downloaded and the installer should walk you though the set up.
* Be sure to allow the Anaconda to:

**"prepend the Anaconda3 install location to PATH" - Be careful because this may not be the default** 

so that the anaconda components can be found.

## From the command line

* The steps are the same for MacOSX and Linux.
* Download the command line installer by **clicking** on the link, using **curl**, or using **wget** to download the file for you.

		$ curl -O "https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh"

**Execute the installer**

* Change your directory (**cd**) to the folder with the file and run the installer

* write "bash" even within the bash shell
you should be able to locate the downloaded file in your local folder or in the downloads folder

		Anaconda3-5.2.0-MacOSX-x86_64.sh

		$ cd <directory-with-installer>
		$ bash Anaconda3-5.2.0-MacOSX-x86_64.sh


* Be sure to allow the Anaconda to **"prepend the Anaconda3 install location to PATH"** so that the anaconda components can be found


## Verify that things are working well

* Type python at the command line and you should see a version of python 3 listed

		$ python
		"Python 3.5.2 |Continuum Analytics..." # some version of python 3

* Exit and run the juptyer notebook

		>>> exit ()
		$ Jupyter notebook


		 **On the command line you should see:**
		"[I 13:30:37.290 NotebookApp] Saving file at.."

* your browser should open with the Jupyter notebook

		ctrl - c to exit


______

# Install a virtual environment
----

* If python 2 opens instead of python 3 or if the Jupyter notebook does not open, try creating a virtual environment with conda.

* you can use virtual environments to run isolated version of python and its packages and avoid incompatibilities.

**also** If you already have Anaconda and have python 2 installed you can make a new "virtual environment" and specify python 3 during setup.

# Create a new virtual environment

* the name py3jp is arbitrary
* The virual enviroment allows you to specify the python version python packges to be installed.

		$ conda create -n py3jp python=3 jupyter matplotlib

* To activate this virtual environment

		$ source activate py3jp  

* Check the python version and jupyter notebook shown above

  		$ python
		>>> exit()
		$ Jupyter notebook
		ctrl-c

* When you are done

		$ source deactivate

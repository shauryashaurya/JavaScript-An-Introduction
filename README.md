# JavaScript - An Introduction

Cool cool cool cool cool... let's do this. 
Early commit for a introduction to JS workshop.

# TODO:
1. Add examples
2. Add exercises

# Setup:

We'll use Jupyter Notebooks here. 
Meaning, we'll need to install a nodejs kernel for Jupyter.

Get the following installed on your windows machine first (all of this should be actually easier on a Mac/*nix):
* Anaconda (this gets you python and a bunch of other packages including Jupyter)
	* I prefer the Python 3.x version, even if it's a little extra work to get ijs to work.
* NodeJS
_really? links? can't google?_
_also just get the latest versions_

1. Ensure that Anaconda is installed on your system
2. If you have Anaconda3 (Python 3.x) installed, you'll first need to add Python 2.7 environment because the javascript notebooks only support 2.7 as of now.
3. run the following commands from an elevated command prompt:
`conda create -n Python27 python=2.7`
4. open python2.7 environment using the following command:
`activate Python27`
5. after this is done, install the windows build tools (VC2015):
`npm install --global --production windows-build-tools`
6. now install ijavascript kernel:
`npm install -g ijavascript`
7. run ijsinstall so it can register with jupyter:
`ijsinstall --install=global`
8. (Only if you are on Anaconda 3) after we are done with today's tutorial, remember to run
`deactivate Python27`
to switch back to Python 3.x

# Check out the notebook now
* Open the command line
* Navigate to the folder you've got this js notebook
* Run:
`jupyter notebook`
* The browser should open up, click on the right notebook 

_TODO: add some details on how to navigate a notebook_
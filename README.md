# fmp_project
Repository for 21M.587 Final Project

This project tackles Automatic Pitch Detection according to "Polyphonic Pitch Detection by Matching Spectral and Autocorrelation Peaks" by Sebastian Kraft, Udo Zolzer. Some liberties were taken due to potential inaccuracies/lack of 'instruction' in the article.

You will be running Python in Jupyter Notebooks. To do so, you will need Python 3.11 and a few Python modules. The recommended approach is to create an isolated environment for this project so as not to interfere with other Python modules that you've already on your computer. You will also need [numpy](https://numpy.org/install/) and [matplotlib](https://matplotlib.org/stable/install/index.html) installed. 

# Setup with Miniconda
Setup using [miniconda](https://docs.conda.io/projects/miniconda/en/latest/). Since it provides a single streamlined interface to install specific Python versions as well as set up a new Python environment. It will not interfere with any other Python versions on your machine and is easy to remove if you want to uninstall at the end of this class, and is supported on Mac, Windows, and Linux.

Go to the miniconda quick install page and follow the installation instructions for your system. Select the latest **64-bit** python installer.
After miniconda is installed, start a new terminal window  
**Windows Note:** to use miniconda's python, you must start the "Anaconda Prompt" as opposed to the regular Command Prompt.
Create a new python environment for this project and activate it.  
`conda create --name fmp_project`  
`conda activate fmp_project`  

Remember to activate this environment every time you start a new terminal/shell for this project  
Install python:  
`conda install python=3.11`  
Verify the environment setup. Start a new terminal (Windows: Anaconda Prompt)  
`conda activate fmp_project`  
`python --version`

This should print 3.11.x (doesn't matter what x is).

# Running project

Clone the repository onto your local machine. Make sure that you are in the `fmp_project` environment everytime you run this project. Choose the audio file you want to use and then run All Cells. Will take a while to run, but use the last graph shown to see what the detected pitches were

# Future steps

Instead of having hard coded reference tracks, I could work towards interpreting the MIDI files as reference tracks to compare my spectral detected notes against.
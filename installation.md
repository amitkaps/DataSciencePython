# Installation

## Pre-requisites
* Laptop running Linux / OSX / Windows operating system
* Minimum 4GB of RAM
* Laptop charger

## Recommended Installation
We will be using Python 3.5 version for the exercise. Users should install the Anaconda distribution from Continuum - [https://www.continuum.io/downloads](https://www.continuum.io/downloads). We request you to check if your Operating System is 32 bit or 64 bit and download the according Anaconda installer

To find out what architecture your OS is, here are references for Windows, OSX and Ubuntu: 

- Windows and OSX: [http://www.akaipro.com/kb/article/1616#os_32_or_64_bit](http://www.akaipro.com/kb/article/1616#os_32_or_64_bit)
- Ubuntu: [http://askubuntu.com/a/41334](http://askubuntu.com/a/41334)

Please note that installing Anaconda is the **recommended** option for doing the workshop.

## Post Anaconda Installation
Please run the below commands from your command line interface

```conda install seaborn```

## Data for the workshop
Please run the below commands from your command line interface

```git clone https://github.com/amitkaps/DataSciencePython.git```

If the participant does not have git, please download the repo. Please navigate to:
https://github.com/amitkaps/DataSciencePython

And there's a button: `clone or download`. Please download the files.

## Check installation

To test your installation, change to the tutorial directory, and run:

    $ python check_env.py

If the required packages are present, you will see the message:

    $ OK.  All required items installed.

If you see message to install particular package(s), please install them using the command:
    
    $ conda install <package name>


## Python Basics
If you want to start learning / brushup your basics python programming skills, here is the material you can use - http://anandology.com/python-practice-book/getting-started.html

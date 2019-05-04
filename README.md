# Internship - Scraping Redfin data 

## Setting up virtual python setup

Follow this link to [documentation](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) for installing the virtual environment for python.

### Installing packages using pip and virtual environments for macOS

- Installing pip latest version
    python3 -m pip install --user --upgrade pip
- Installing virtualenv¶
    python3 -m pip install --user virtualenv
    
- Creating a virtual environment
    python3 -m venv env
- Activating a virtual environment
Before you can start installing or using packages in your virtual environment you’ll need to activate it. Activating a virtual environment will put the virtual environment-specific python and pip executables into your shell’s PATH.

- On macOS and Linux:

    source env/bin/activate
- You can confirm you’re in the virtual environment by checking the location of your Python interpreter, it should point to the env directory.

- On macOS and Linux:

which python
.../env/bin/python

- Leaving the virtual environment
If you want to switch projects or otherwise leave your virtual environment, simply run:
    deactivate
If you want to re-enter the virtual environment just follow the same instructions above about activating a virtual environment. There’s no need to re-create the virtual environment.

Installing packages¶
Now that you’re in your virtual environment you can install packages. Let’s install the excellent Requests library from the Python Package Index (PyPI):

pip install requests

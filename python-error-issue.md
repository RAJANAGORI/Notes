Install pip2
1. https://bootstrap.pypa.io/pip/2.7/get-pip.py
2. python get-pip.py

If you getting any error like this
ERROR: Command errored out with exit status 1: python setup.py egg_info Check the logs for full command output.
when you install python module using pip fot python2 version

then you need to run 
1. python -m pip install --upgrade pip setuptools wheel

to install the module related to python2 then you need run
1. python -m pip install -r requirements.txt

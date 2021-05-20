### Install pip2
- wget -L https://bootstrap.pypa.io/pip/2.7/get-pip.py -O get-pip.py
- python get-pip.py

But sometimes installing modules with pip2 give some shit error like this:
``` 
ERROR: Command errored out with exit status 1: python setup.py egg_info Check the logs for full command output. when you install python module using pip fot python2 version
```
then you need to run
- python -m pip install --upgrade pip setuptools wheel

and after complete the above command install pip2 depended module by given format
- python -m pip install -r requirements.txt

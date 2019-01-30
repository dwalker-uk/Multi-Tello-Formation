***Tello Edu SDK 2.0 - for Python 3***

This is a fork from the official SDK, hosted at https://github.com/TelloSDK/Multi-Tello-Formation.  The priority changes were to make the Python library compatible with Python 3, and to enable more advanced control from within Python.  Specifically, that means transforming the simple text-driven commands into Python functions, which can then be extended.

The install scripts which formed part of the official SDK version contained a large binary copy of PIP, and so have been removed.  The very few dependencies can be easily installed by the user.

Key functionality will be described below as it is tested and updated, as an English language update from the original Chinese readme.

***Configuration / Setup***

Only two non-standard libraries are required - ```netifaces``` and ```netaddr```.  These can be installed on Mac or Linux with the following commands:
```
pip3 install netifaces
pip3 install netaddr
```
For Windows, I understand the following commands are needed:
```
python -m pip install netifaces
python -m pip install netaddr
```



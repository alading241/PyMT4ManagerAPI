# PyMT4ManagerAPI
Python Interface based on MT4 Manager API.

MT4 Manager API is a windows dll which can only used in c/c++ program. With the help of swigwin-3.0.12, I managed to wrap this dll with python.

Please copy _MT4ManagerAPI.pyd into C:\Python27\DLLs folder. I don't test it with Python3.

Please use test.py to do testing. For security, I have changed the MT4 server IP and manager account in test.py. Please fill in your MT4 server IP and manager account for testing.

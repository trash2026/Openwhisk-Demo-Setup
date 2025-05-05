

# Openwhisk-Demo-Setup

To setup openwhisk locally using ansible,couchdb and docker.

### Operating system
- Ubuntu 20.04

### Setup Virtual Environment for Python
This demo requires Python 2.7.

```
virtualenv --python=python2.7 something 
```

Go to demo/setup.sh and from line 25-33 change the directory to your virtualenv directory



### Run Demo

-Go to demo folder
```
./setup.sh
```
```
python3 run_demo.py
```
```
wsk -i activation list
```

This will show the result of the demo





  



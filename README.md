# py2Jupyter

base image: python:2.7.13-jessie

numpy==1.13.1

pandas==0.19.2

TA-Lib==0.4.10

jupyter==1.0.0

matplotlib==2.0.2

urllib2==1498656401.94

docker run -it -p 8888:8888 -v $(pwd):/path py2Jupyter

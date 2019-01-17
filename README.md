# XG-C100C

## To build the driver yourself, go on your docker host and use follwing shell commands to build it.

mkdir driver-xg-c100c

cd driver-xg-c100c

git clone https://github.com/xcp-ng/xcp-ng-build-env

git clone https://github.com/rushikeshjadhav/XG-C100C.git

chown 1000 ./XG-C100C/ -R

./xcp-ng-build-env/run.py -b 7.6 --build-local XG-C100C/ --rm

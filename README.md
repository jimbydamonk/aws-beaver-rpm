Builds a rpm for use with AWS Linux for beaver. 
This rpm will:
* create beaver user and group
* log to /var/log
* adds an init scirpt

Not so nice stuff:
* python2.7 is hardcoded in the spec file
* you have to check for deps yourself
* pip-2.7 install conf_d
* pip-2.7 install glob2
* pip install msgpack_pure

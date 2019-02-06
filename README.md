# GCPTrain - Startup Script for Load Balancer Test - HTTP. 

For USA 

#! /bin/bash

apt-get update

wget https://raw.githubusercontent.com/dhanajimusale/GCPTrain/master/frontend-uswest.py

sudo python frontend-uswest.py &


.


For  Asia 

#! /bin/bash

apt-get update

wget https://raw.githubusercontent.com/dhanajimusale/GCPTrain/master/frontend-asia.py

sudo python frontend-asia.py &


.


For  Europe 

#! /bin/bash

apt-get update

wget https://raw.githubusercontent.com/dhanajimusale/GCPTrain/master/frontend_europe.py

sudo python frontend_europe.py &


############################################################################


Curl Command

Slow 

while true ; do (curl http://[Load Balancer ExternalIP]/service ) ; sleep 2 ; done 


Fast

while true ; do (curl http://[Load Balancer ExternalIP]/service ) ; sleep 0.1 ; done 



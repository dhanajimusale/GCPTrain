# GCPTrain - Startup Script for Load Balancer Test - HTTP. 

For USA 

#! /bin/bash

apt-get update

wget https://raw.githubusercontent.com/dhanajimusale/GCPTrain/master/fronend-uswest.py

sudo python fronend-uswest.py &


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

sudo python frontend-europe.py &


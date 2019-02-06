# GCPTrain - Startup Script for Load Balancer Test - HTTP. 

For US west 

#! /bin/bash

apt-get update

wget https://raw.githubusercontent.com/dhanajimusale/GCPTrain/master/fronend-uswest.py

sudo python frontend-uswest.py &



for  asia 

#! /bin/bash

apt-get update

wget https://raw.githubusercontent.com/dhanajimusale/GCPTrain/master/frontend-asia.py

sudo python frontend-asia.py &

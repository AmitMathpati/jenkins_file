#!/bin/bash
sudo apt update
sudo apt install zip
sudo apt install openjdk-17-jdk
wget <paste url>
unzip apache-maven-3.9.6-bin.zip
sudo ln -s <copy the path>/bin/mvn /usr/local/sbin/mvn
sudo chmod 777 /usr/local/sbin/mvn

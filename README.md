#!/bin/bash
sudo apt update
sudo apt install zip
sudo apt install openjdk-17-jdk
wget https://dlcdn.apache.org/maven/maven-3/3.9.6/binaries/apache-maven-3.9.6-bin.zip
unzip apache-maven-3.9.6-bin.zip
sudo ln -s /home/ubuntu/apache-maven-3.9.6/bin/mvn /usr/local/sbin/mvn
sudo chmod 777 /usr/local/sbin/mvn

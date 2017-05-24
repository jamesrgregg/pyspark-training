# Project Details

Date: 2017-05-23



## Project Setup
Vagrant up using Vagrantfile for 1 hosts

 - pyspark (Python Spark) 
    - Install [jdk](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 
    - Install [Spark](https://spark.apache.org/downloads.html)
        - apt-get update
        - apt-get install -y software-properties-common unzip
        - apt-add-repository -y ppa:ansible/ansible
        - apt-get update
        - apt-get install -y ansible python-dev libkrb5-dev krb5-user python-pip libssl-dev libffi-dev
        - pip install --upgrade pip
        - pip install pywinrm pykerberos requests_kerberos shade

 - docker
    - sudo apt-get update
    - sudo apt-get install docker.io
    - sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 36A1D7869245C8950F966E92D8576A8BA88D21E9
    - sudo sh -c "echo deb https://get.docker.com/ubuntu docker main\ > /etc/apt/sources.list.d/docker.list"
    - sudo apt-get update
    - sudo apt-get install lxc-docker

 
## References
* Docker install on ubuntu
    - http://buildvirtual.net/docker-installing-docker-on-ubuntu-trusty-14-04/
* PySpark Tutorial
    - https://www.datacamp.com/community/tutorials/apache-spark-python#gs.5=0yEEM
* JDK8 Install 
    - https://www.digitalocean.com/community/tutorials/how-to-install-java-on-ubuntu-with-apt-get#installing-default-jrejdk

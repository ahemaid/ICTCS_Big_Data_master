# ICTCS'2017: Lowering the Barriers to Big Data Solutions

"Lowering the Barriers to Big Data Solutions" workshop will present the results achieved throughout the BigDataEurope (BDE) project, which is the part of the European Union’s Horizon 2020 research Europe flag and innovation program. The workshop will concentrate on the practical aspects of developing and maintaining Big Data applications. The applications will be deployed on the Big Data Integrator platform, a modular platform for deploying Big Data applications, which is developed in the BDE project. The workshop will cover the theory behind Big Data applications and will provide the explanation of the key decisions for the Big Data Integrator platform architecture. Each theorethical part will be followed by a hands-on session. The participants will be invited to accomplish assignments, which will teach them how to solve Big Data problems using Spark and BDI platform.

Read more on the [ICTCS'2017 website](http://www.ictcs.info/page/workshops).

# Preparing for hands-on sessions
You will need an Ubuntu 16.04. [Install Docker](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-docker-ce) and [docker-compose](https://docs.docker.com/compose/install/#install-compose) on your Ubuntu box.

Then create a directory for all the workshop files:
```
$ mkdir ~/Workspace/ictcs-lowering-barriers-to-bd && cd ~/Workspace/ictcs-lowering-barriers-to-bd
```
Clone the Docker Hadoop Spark Workbench ([install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) first if necessary):
```
$ git clone git@github.com:big-data-europe/docker-hadoop-spark-workbench.git && cd docker-hadoop-spark-workbench
```
Pull all the necessary docker images:
```
$ docker-compose pull
```
And additionally pull java spark template docker image:
```
$ docker pull bde2020/spark-submit:2.1.0-hadoop2.8-hive-java8
```

# Schedule
* 9:00-10:00 [Introduction: Big Data Europe Project, Architecture, Components and Interfaces](./slides/Introduction.pdf)
* 10:00-11:00 [Planning BDI Stack for Your Application](./slides/Planning_bdi_stack.pdf)
* 11:00-11:15 Coffee Break
* 11:15-11:45 [Introduction to Docker](./slides/Introduction_to_docker.pdf)
* 11:45-12:15 Hands-on: [Configuring Docker and Docker Swarm Cluster](./handson/configuring_docker.md)
* 12:15-13:00 Hands-on: [Deploying BDI Stack Locally and on Remote Server](./handson/deploying_bdi_stack.md)
* 13:00-14:00 Lunch
* 14:00-15:00 [Methodologies for Developing a Big Data Applications](./slides/Methodologies.pdf)
* 15:00-16:30 Hands-on: [Developing and Deploying a Big Data Application](./handson/developing_bda.md)
* 16:30-17:00 [Conclusions, Closing Remarks, Q&A Session](./slides/Conclusions.pdf)
# ICTCS-Big-Data-master
# ICTCS-Big-Data-master

LabKey via Docker
=================

*WORK IN PROGRESS, PLEASE DO NOT USE THIS YET.*

This folder contains the Dockerfile, additional scripts and instructions for running a Docker image which you can use to give LabKey Server a try. An image built with this Dockerfile will soon be available on DockerHub.

**IMPORTANT:** *This image is meant for trying out LabKey and not meant for running a production server or for storing important biomedical data.*

## Is there an image already built? 

An image built with this Dockerfile will soon be available on Docker Hub. This image will contain: 

* LabKey Server 14.1 
* Tomcat 7
* Oracle Java 7
* PostgreSQL 9.3 

### Running LabKey Server standalone in a container

To run the image 

    docker run --name labkey-standalone -d -p 8080:8080 piegsaj/labkey

After few seconds, open [http://&lt;ip.of.yoour.host&gt;8080](http://<ip.of.your.host>:8080) to see the LabKey web application.

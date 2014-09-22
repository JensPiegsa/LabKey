LabKey via Docker
=================

*WORK IN PROGRESS, PLEASE DO NOT USE THIS YET.*

This folder contains the Dockerfile, additional scripts and instructions for running a Docker image which you can use to give LabKey Server a try. An image built with this Dockerfile is available at [bconn/labkey-standalone](https://registry.hub.docker.com/u/bconn/labkey-standalone/) on DockerHub.

**IMPORTANT:** This image is meant for trying out LabKey Server and **not** meant for running a production server or for storing important biomedical data. 

## Is there an image already built? 

An image built with this Dockerfile is available at [bconn/labkey-standalone](https://registry.hub.docker.com/u/bconn/labkey-standalone/) on DockerHub. This image contains: 

* LabKey Server 14.1 
* Tomcat 7
* Oracle Java 7
* PostgreSQL 9.3 

### Running LabKey Server Standalone in a container

To run the image 

    docker run --name labkey-standalone -d -p 8080:8080 bconn/labkey-standalone

After few seconds, open [http://<host>:8080](http://<host>:8080) to see the LabKey Server initialization page.

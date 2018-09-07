# Image JIRA Software with Oracle JRE Licensed

## Description

I saw a lot of people use the OpenJDK with the tar.gz but the lastest version of JIRA does not support it. So I did a docker image with the binary from Atlassian that has the Oracle JRE license. So this image is ok for production use. 

## Available versions

* 7.6.x : `7.6.0`, `7.6.1`, `7.6.2`, `7.6.3`, `7.6.4`, `7.6.5`
* 7.7.x : `7.7.0`, `7.7.1`, `7.7.2`, `7.7.3`, `7.7.4`
* 7.8.x : `7.8.0`, `7.8.1`, `7.8.2`, `7.8.3`, `7.8.4`
* 7.9.x : `7.9.0`, `7.9.1`, `7.9.2`
* 7.10.x : `7.10.0`, `7.10.1`, `7.10.2`
* 7.11.x : `7.11.0`, `7.11.1`, `7.11.2`
* 7.12.x : `7.12.0`, `7.12.1`

> New grafical interface in 7.10 version. ReactJS finally here !

### Usage

To pull the version you want you can do : `docker pull frogbis/jira-software:$VERSION`

If the version is not available on my DockerHub repository, you can edit the ARG JIRA_VERSION on the docker file to put the version you want to use.

#### Defaut values

- Xms : 1024
- Xmx : 2048


#### Volumes you can mount

- install directory : /opt/atlassian/jira/
- data directory : /var/atlassian/application-data/jira

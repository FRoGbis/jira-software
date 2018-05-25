# Image JIRA Software with Oracle JRE Licensed

## Description

I saw a lot of people use the OpenJDK with the tar.gz but the lastest version of JIRA does not support it. So I did a docker image with the binary from Atlassian that has the Oracle JRE license. So this image is ok for production use. 

## Available versions

* 7.6.x : `7.6.0`, `7.6.1`, `7.6.2`, `7.6.3`

### Usage

To pull the version you want you can do : `docker pull frogbis/jira-software:$VERSION`

#### Defaut values

- Xms : 1024
- Xmx : 2048


#### Volumes you can mount

- install directory : /opt/atlassian/jira/
- data directory : /var/atlassian/application-data/jira

# Image JIRA Software 7.6.0 with Oracle JRE Licensed

### Description

I saw a lot of people use the OpenJDK with the tar.gz but the lastest version of JIRA does not support it. So I did a docker image with the binary from Atlassian that has the Oracle JRE license. So this image is ok for production use. 

#### Defaut values

- JIRA_VERSION =  7.6.1
- Xms : 1024
- Xmx : 2048


#### Volumes you can mount

- install directory : /opt/atlassian/jira/
- data directory : /var/atlassian/application-data/jira

# rkjain.github.io

## About Me

Rishabh Jain
Software Services Engineer IV
LinkedIn: linkedin.com/in/rishabh-jain-6a610775
GitHub: github.com/rkjain

I am an experienced software developer with 8 years of experience in design, development, and deployment. My expertise includes platform engineering and building and maintaining distributed services. I am currently working in the Cloud and Network Functions Virtualization (NFV) organization at Ericsson.


## WORK EXPERIENCE

### Ericsson Platform Engineering - Cloud and NFV
Client: Verizon
Time Frame: 01/2022 - Present, Achievements/Tasks

Achievements/Tasks:
- Designed and implemented solution to help estimate the dimensioning of the on-premise OpenShift cluster for running NFV
workloads
- Designed solution for replicating NFV conﬁguration between primary and secondary deployment servers
- Designed solution for development teams to collect application core dumps on demand from openshift worker nodes Support platform upgrade activities on openstack , openshift, outline, f5 vega and aspenmesh

### Airship Community Developer, Ericsson 
Client:  ATT and Microsoft
Time Frame: 10/2020 - 12/2021,

Achievements/Tasks:
- Design implementation architectures and scalable cloud solutions leveraging AT&T's open source project airship (now micrsoft) on
behalf of Ericsson to integrate cluster api with airshipctl. The integration allows airshipctl to create kubernetes clusters locally using docker, and production grade kubernetes clusters on google cloud platform
- Created proof of concepts and documented usage of cluster api to create kubernetes clusters using infrastructure providers such as docker, azure, and gcp. This was done to gauge the overall eﬀort required to integrate the same functionality with airshipctl
- Got Airship 2.0 Cloud Native Computing Foundation certiﬁed
- Participated and led discussions for features developed and present them to the airship community Created documentation on patchset usage, and created screencasts to spread community awareness Created Zuul CI Gates on opendev to test feature patchsets


### DevOps Engineer, Ericsson 
Client: TMobile IAM
Time Frame: 03/2020 - 09/2020
Achievements/Tasks:
- Developed playbooks to automate ECE, and CAC deployments using Ansible Designed solution to transition Jira Issues from the Gitlab CI/CD Pipeline Created a sftp utility for ECE PDU to upload large artifcats on rosetta artifcatory
- Designed and developed solution to generate software baseline programmatically from jfrog artifactory


### DevOps Platform Engineer and Tools Developer, Ericsson
Project: Market Area North America DevOps
Time Frame: 10/2019 - 02/2020
Achievements/Tasks:
- Onboarded Projects from Ericsson North America to MANA DevOps platform on premise and on azure cloud
Supported and performed routine upgrades on MANA Devops Platform running services like GitLab, Artifactory , Sonarqube, Sensu, Trafeik, and Rundeck on rancher
- Created best practices and solutions for projects to use Jira and Gitlab for issue management, and developed additional modules for Jira and Gitlab that can be used to add feedback from the CI/CD pipeline as comments on a Jira Issue via Jira Rest API


### Deployment Engineer, Ericsson Order Care, Ericsson
Project: Tmobile Uprising
Time Frame: 08/2014 - 12/2018
Achievements/Tasks:
- Designed Weblogic Application Server Architecture to support Ericsson Order Care Applications in production
- Designed Java Messaging Servers with High Availability and Load Balancing Functionality, which hosts distributed queues, ,topics and messaging bridges to communicate application transactions between multiple Ericsson Applications
Developed custom Ansible modules, playbooks and managed ansible inventories to support deployments in lab and production environments
Led a deployment team of 3 members onshore in US and 5 members oﬀshore in India to support multiple product deployments


### IT System Administrator, Center for Academic Support and Assistance, University of Houston
Time Frame: 08/2013 - 08/2014
Achievements/Tasks:
- Administered Innovate.uh.edu, a Word Press based Multi site Network conﬁgured on LAMP Stack on systems running Centos and Ubuntu
Deployed, conﬁgured Big Blue Button Server, an open source web conferencing tool which provides learning features like Black Board Learn on Ubuntu
- Conﬁgured Hyper-V on Windows 2012 Server to install and conﬁgure virtual machines running Ubuntu and CentOS

## SOFTWARE PROJECTS

### Kubernetes Cluster Utilization Dashboard

- Developed a Kubernetes Cluster Utilization Dashboard that displays cluster utilization based on the resources requested by applications, 
  including CPU and memory allocation, requests, and limits.

### IPMI Sensor Data Visualizer
- Implemented an IPMI Sensor Data Visualizer that measures power consumption statistics during peak traffic and can be used in conjunction with power capping on HP servers to reduce power consumption. 
  The visualizer generates various plots such as Maximum Power and Total CPU Power Utilization over time, Fan Speed, DIMM Temperature and CPU Temperature over time.



### JIM - Jira Issue Manager (01/2020 - Present)
- A utility to tranistion Jira issues to a given state, add comments on a Jira issue, and also validate an issue if required
- Used internally in GitLab deployment pipeline to add continuous feedback in form of comments including job url, status and transition issues from one state to another based on the state of the pipeline

### Uproar SFTP Client (07/2019 - Present)
- A SFTP client that supports running proxy commands over SFTP
- Offers the ability to transfer source file or directory to destination directory structure, creating any necessary directories
- Offers multiple file transfers by reading source and destination from a YAML configuration file
- Enables integration with daily CI jobs to upload artifacts directly to the SFTP server

### Mdownload - Software Baseline Manager (01/2019 - Present)
- A utility to programmatically create a software baseline from Jfrog Artifactory and download packages on deployment server
- Creates a YAML based inventory file, consisting of software information of multiple Ericsson applications, filtered on criteria such as latest version, last uploaded time, software size, md5 checksum, release candidate, and release dates
- YAML based inventory file can also be used as input by the tool to directly download packages from Jfrog Artifactory

### Environment Flow Diagram (05/2017 - Present)
- Generates graphs by collecting data from configuration files used by active applications, specific to an environment
- The graph consists of nodes (application name, IP and port) and edges (unidirectional and bidirectional), reflecting flows between the applications
- Tool compares information gathered from applications and publishes a warning label if differences in endpoint configuration are detected. For example, a warning is published if Application "A" endpoint is different in Application "B" & "C" configuration files
- Artifacts created by the tool includes SVG image that is hosted on a web server, a YAML config file used by Ansible, and dot code published on Confluence


## EDUCATION
Masters of Science, Computer And Systems Engineering
University of Houston
Time Frame: 08/2012 - 05/2014

Bachelor of Technology, Electronics And Communication Engineering
Rajasthan Technical Univeristy
Time Frame: 08/2007 - 05/2011

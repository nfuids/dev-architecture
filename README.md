# dev-architecture

The objective of this project is to build an architecture that can be used to develop microservices solutions. 

Here is what it should look like once completed:
* Everything should be based off of text file for easy source control (kubernetes configs, docker images definition, ansible script, etc.)
* Use Kubernetes to orchestrate everything
* Everything should be run inside Kubernetes
* Run Jenkins to automate docker images creation/update to make it easy to stay up to date
* Run a private Docker Registry 
* Use Ansible when infrastructure automation is required
* Run a ELK Stack (ElasticSearch, Logstash and Kibana) for everything log related
* Run an API Gateway 
* Run a service mesh
* Run a LDAP Server + (Identity and Access Management)
* Every part of the architecture should somehow push logs to the ELK Stack

The idea is that once that everything is set, it's easy to start a new project with the base already in place. Install a kubernetes environment, install all the components and start developing your solution.
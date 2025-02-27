# HPE Deployment Guide for Red Hat OpenShift Container Platform on HPE Synergy with HPE 3PAR Storage

Prior to using the instructions in this README.md file it is recommended that you read and understand the deployment guide found in the root of this folder. Instructions found in the deployment guide will take precedence over instructions in README.md files. It is further recommended that the installer read and comprehend the installation instructions for OpenShift Container Platform provided by Red Hat. these instructions may be found at https://docs.openshift.com/container-platform/3.11/getting_started/install_openshift.html.

This guide is accompanied by a Reference Configuration. The Reference Configuration highlights business value and provides a bill of material for the tested configuration. It can be download from https://h20195.www2.hpe.com/V2/GetDocument.aspx?docname=a00056101enw.

The person implementing this solution should have a strong working knowledge of Red Hat Enterprise Linux, the hypervisor solution (RHVH or vSphere) they are choosing to implement, servers, storage and networking knowledge, an understanding of PaaS solutions, containers and of COEs, a working knowledge of Ansible and shell scripting and an ability to follow code in its written form. 

________________________________________
## About ##
________________________________________

This repo contains Ansible plays and scripts to automate the installation of Red Hat OpenShift 3.11.

________________________________________
## Prerequisites ##
________________________________________

Consult the Deployment Guide linked in this folder for full instructions on utilizing the playbooks and resources included in this repository.

________________________________________
## Summary ##
________________________________________
The plays outlined in this repository have been tested with the following.

Red Hat Enterprise Linux 7.6

Red Hat Virtualization Host 4.2

Red Hat Virtualization Manager 4.2

Red Hat Ansible Engine 2.7

Red Hat OpenShift Container Platform 3.11

________________________________________
## Change Tracker ##
________________________________________
v 3.0 - July 3rd, 2019 - Initial release

v 3.0.1 - July 15th, 2019 - Updated document, fixed formatting issues, minor grammar fixes, addition of multiple appendices covering Ansible Tower, Prometheus, log aggregation with EFK and Kube-bench.

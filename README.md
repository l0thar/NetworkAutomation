# NetworkAutomation

This repository provides a Vagrant box for building and testing Ansible network automation solutions based on Ivan Pepelnjak's Network Automation course over at ipspace.net. The Vagrantfile will set up a second network connection on the box that is connected to the flat1 VIRL network (ip: 172.16.1.12). It will also clone the ipspace/NetOpsWorkshop github repository and run the installer for the various tools used in that course, including Python, Ansible, and NAPALM.

## Environment
  * VMWare Workstation
    * Cisco VIRL
    * Vagrant Ubuntu 16.04 box
    
## Requirements
It is assumed that you have configured the flat1 network in VMWare Workstation and Cisco VIRL to use the 172.16.1.0/24 network.


# md-vagrant-docker


This project provides a streamlined setup for creating a virtual machine using Vagrant and provisioning it with Docker using Ansible. The Vagrantfile in this repository defines the virtual machine's configuration, and the Ansible script automates the installation of Docker on the virtual machine.
 
# Prerequisites
Before you begin, ensure that the following software is installed on your system:
Vagrant
VirtualBox
 
Clone the repository to your local machine:
 
git clone https://github.com/your-username/your-project.git
cd your-project

This command will download the base box, create the virtual machine, and execute the Ansible playbook to install Docker.

vagrant up
 
Once the provisioning is complete, SSH into the virtual machine: 

vagrant ssh
 
Verify that Docker is installed:

docker --version

This should display the Docker version information, confirming a successful installation.

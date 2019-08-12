# VMCreation
Creation of VMs
This is for creating new VM's on virtual box using Vagrant.
  VM Config:
  1. Node1, Node2, Node3: RAM: 4GB
  2. LB1, LB2: RAM: 512MB

# Prerequisites
1. Install Vagrant from below link.
  https://www.vagrantup.com/downloads.html

2. Install VirtualBox from below link.
  https://www.virtualbox.org/wiki/Downloads
  
3. Make a directory VMs/vagrant-centos-7 and download the centos7 image using below command.

  $ vagrant box add centos/7
  
# Initialization and Startup
1. Initialize the Vagrant by below command. This will create a Vagrant file. The content of new Vagrant file has to be replaced by the content of Vagrant attached above in the git repository 
  
  $ vagrant init
  
2. Once the content of the Vagarant file has been coppied then we can go ahead and run the command to start up the virtual machines. All the steps mentioned above has to be carried out only once and there on just running the below command will create the virtual machines.
  
  $ vagrant up

# Introduction

## Prerequisites

> ####  _Orhan Ergun_ - Ansible Basics 'Fundamentals' Course
[OrhanErgun.net](https://orhanergun.net/courses/ansible-basics-for-network-engineers/) - 
[GitHub](https://github.com/OrhanErgun-net/Ansible-Basics-Network)

The following topics are convered in *Ansible Basics 'Fundamentals' Course* and will not be in this course topics
* Ansible Concepts
* LAB Setup (VMware, RedHat, EVE-NG, VS Code, etc...)
* Simple Ansible installation

## Installation
 * #####  RHEL <span style="color:red"> **8.5** </span> , Ansible <span style="color:red"> **2.9** </span>, and Python <span style="color:red"> **3.6** </span> are used in the following, Always make sure what version you are using.
 * ##### Check the latest <span style="color:red"> **version** </span> and <span style="color:red"> **release** </span> numbers

1. [Optional] you may uninstall **Ansible** if you previously installed it using *Python pip3* and re-install python3
   ```sh
   pip3 uninstall ansible
   pip3 uninstall ansible-core
   yum remove python3.9 -y
   yum install python3
   ```
2. Update system packages
   ```sh
   yum update -y
   ```
3. Enable Ansible repo
   ```sh
   subscription-manager repos --enable ansible-2.9-for-rhel-8-x86_64-rpms
   ```
4. Start **Ansible** installation
   ```sh
   yum install ansible -y
   ```
5. Verify **Ansible** version
   ```sh
   ansible --version
   ```

## Get The Code
 * ##### Check the latest version and release

1. [Optional] you may install **git** if your system doesn't have it by default
   ```sh
   yum install git -y
   ```
2. Download the course repo locally
   ```sh
   git clone https://github.com/OrhanErgun-net/Ansible-Advanced-MultiVendor-Networks.git 
   ```

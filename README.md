# Ansible Homework Assignment 1

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Folder Structure](#folder-structure)
- [Setup and Usage](#setup-and-usage)
- [Key Features](#key-features)

## Introduction

Ansible_HW1 showcases how to use **Ansible**, to manage infrastructure as code (IaC). The project includes playbooks, inventory files, and roles to automate common infrastructure tasks efficiently.

## Prerequisites

To use the files in this repository, ensure you have the following:

- **Ansible** installed (Version 2.9+ recommended)
- A control node (e.g., your local machine) and managed nodes (target servers)
- Access to managed nodes via SSH with appropriate user privileges
- Python installed on the managed nodes
- Basic understanding of YAML and Ansible playbooks



## Folder Structure

The repository contains the following structure:

1. **inventory/**: Define the hosts (grouped or standalone) targeted by the playbooks in [hosts.ini](https://github.com/MEGHKUMARPATEL/Ansible_HW1/blob/main/hosts.ini).
2. **playbooks/**: Core Ansible scripts that describe the tasks and their sequence.
    1. [webserver.yml](https://github.com/MEGHKUMARPATEL/Ansible_HW1/blob/main/webserver.yml): The main playbook for deploying web servers.
    2. [undeploy.yml](https://github.com/MEGHKUMARPATEL/Ansible_HW1/blob/main/undeploy.yml): The playbook for undeploying web servers.
4. **roles/**: Modular task definitions for reusable configurations.
5. **group_vars/host_vars**: Variable files for customization based on hosts or groups.




## Setup and Usage

### Clone the Repository

```bash
git clone https://github.com/MEGHKUMARPATEL/Ansible_HW1.git
cd Ansible_HW1
```

## Key Features
1. Infrastructure Automation: Automate repetitive infrastructure tasks.
2. Modular Design: Use roles for scalability and reuse.
3. Custom Variables: Easily adapt configurations with group and host variables.
4. Version Control: Keep track of changes and collaborate effectively.

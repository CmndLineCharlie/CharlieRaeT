# Project Name
JoannaCopy and Archive Playbook

## Description
This project automates server management tasks using Ansible.
Variables: I defined a variable named mave.
Tags: I  assigned tags to some tasks (copy and fancytag). 
File Permissions: The 0644 permission set in my  playbook allows read and write access for the owner and read-only access for others.
Destination Paths  match my intended directory structure.
Package Installation: The last task installs the nfs-utils package using the yum module.

## Installation
To get started, clone the repository:git@github.com:CmndLineCharlie/CharlieRaeT.git.
Make a branch on work done from this branch:Joannabranch
Have ansible installed , verify ssh keys are configured to your target server-Done.
Setup your inventory host file:inventory.ini
Run an adhoc command to get the current disk space of your target server, redirect it to a file called output.txt:Done.
Create a playbook using the copy and  archive module:JoannaCopy ,  Archive Playbook, tags and installation.
In the root of your gitrepo , create a README.md file , In this file give details of what your project is about ,ie any commands that need to run etc:Commands used- touch,gzip,chown,groupadd,etc.
Push all changes / updates to the gitrepo branch: Done.

## Usage
- Run the following commands to execute the playbook:ansible-playbook Joannafile.yaml

## Contributing
Contributions are welcome! Please submit pull requests to the  Joannaokbranch.

## License
This project is a test project.i

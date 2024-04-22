# Project Name
JoannaCopy and Archive Playbook

## Description
This project automates server management tasks using Ansible.The task to copy files to the home directory (/home/CharlieRaeT/testfile) was executed, and it resulted in a change (changed: [localhost]). This means that the file was successfully copied.
The task to archive the copied files was also executed, and it completed successfully (ok: [localhost]).The playbook ran on the localhost because the hosts directive in the playbook specifies localhost. If you intended to run it on remote hosts, you need to update the hosts directive accordingly.

## Installation
To get started, clone the repository:git@github.com:CmndLineCharlie/CharlieRaeT.git.
Make a branch on work done from this branch:Joannabranch
Have ansible installed , verify ssh keys are configured to your target server-Done.
Setup your inventory host file:inventory.ini
Run an adhoc command to get the current disk space of your target server, redirect it to a file called output.txt:Done.
Create a playbook using the copy and  archive module:JoannaCopy and Archive Playbook.
In the root of your gitrepo , create a README.md file , In this file give details of what your project is about ,ie any commands that need to run etc:Commands used- touch,gzip,chown,groupadd,etc.
Push all changes / updates to the gitrepo branch: Done.

## Usage
- Run the following commands to execute the playbook:ansible-playbook Joannafile.yaml

## Contributing
Contributions are welcome! Please submit pull requests to the  Joannaokbranch.

## License
This project is a test project.i

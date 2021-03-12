# VPC Migration Tools
## Scope

This repository is dedicated in providing different types of tools and solutions that may be
useful with your infastructure migration to IBM Cloud VPC.  The tools are made up of collection
of individual scripts or with existing open source utility.  The tools are made available to
anyone who wishes to use them as is or free to modify them to fit their needs. As a recommended
practice, review carefully any materials from this repository before using them on any live
system.

## Pre Validation Check Scripts ##
When migrating an existing guest machine image to IBM Cloud VPC as a custom image, it needs to
meet the minimum requirements in order for it to be migrated over as described in the following [link](https://cloud.ibm.com/docs/vpc?topic=vpc-managing-images).

The below scripts were created to help automate the validation of the candidate guest machine.
- [Redhat Precheck Script](Linux-Precheck-Srcripts/)
- [New custom Windows Prep Script for Importing](Create-Windows-Import/)

## Data Migration ##
There are many tools available to migrate data from the source to the target machine. The
script provided here is using an open source utility rsync with the some default commands.
[rysnc script](data-migration/)

## Image Conversion ##
If you are looking to move away from other hypervisor, then image needs to be in qcow2. This
scripts helps convert guest images from Vmware in vdmk format to qcow2.
[image conversion](image-conversion)

## Suggestion/Issues ##
While there are no warranties of any kind, and there is no service or technical support
available for these materials from IBM support, your comments are welcomed by the maintainers
and developers, who reserve the right to revise or remove the materials at any time. We,
maintainers and developers, will support the scripts posted in this repository. To report a
problem, provide suggestion or comment, please open a GitHub issue or email us at
[*<email_distribution_list>*](mailto:blah@ibm.com?subject=[VPC Migration Tools]). If the
scripts are modified and have issues, we will do our best to assist.

<!-- A more detailed Usage or detailed explaination of the repository here -->

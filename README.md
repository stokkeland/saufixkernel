# saufixkernel
A simple script to purge old kernels for apt based distros (Ubuntu)

For version and Usage info please see the script source

No guarantees, use at own risk for testing only, never use in production environment
If you are thinking of actually running this, ALWAYS do list first before purge
Originally written for Ubuntu 22.04 LTS
This is bloated and not ver elegant, it started as a simple list and evolved a bit at 
the time over the years

What prompted this is how many people keeps on posting something that you can simply
do autoremove with purge, i found this never really works...
Some argued we should check for ii vs rc, personally i want to purge it all, so if
want to add options for remove and purge separated and based on installed/configured
mode then please develop this and submit a pull request.

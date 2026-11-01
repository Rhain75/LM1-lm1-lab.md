# LM1-lm1-lab.md
 ##Task 1- Get-CimInstance Win32_LogicalDisk -ComputerName PC01
a. asks windows for info about your pc and lists its disks.
b. An admin could use it to check how much space a pc has which would be useful before downloading new software.
c. limitations of using this command would be 1. the command has to be edited everytime a new pc is checked 2. its shown in bytes which can sometimes be hard to read 3. could be ran in different ways and get inconsistent results.

##Task 2- 
a. Purpose is to use it to be reusable on any pc
b. the command used is Get-DiskReport to get information on the drives
c. the expected output would be a table of the disks

##Task 3-
a. parameter name would be computername
b. the parameter can be used on any PC
c. it returned the disk information ofr my pc
##Task 4-
The purpose of the comment # is to help future administrators with helpful notes/comments on things like this

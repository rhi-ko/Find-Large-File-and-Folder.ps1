# Find-Large-File-and-Folder 
This Powershell script will scan a computer's Hard Drive and identify the largest files located on the Hard Drives and which folder on the root drive is the largest.

I modified this script to use to identify which files were taking up the most space on a Hard Drive to help free up space for other system functions. There are software applications that can be used to do the same thing as this script but that would involve installing a program which is kind of going in the opposite direction I want to go in. Since Powershell is installed on any Windows 7 and newer machine the only added ammount of space needed is less than 50k. If this script is run on a domain, it can just reside on the technican PC and run the script remotely over the network.

The problem I ran into before was that a computer hard drive was full at 98%. Installing another program on this drive might not have been the smartest thing to do. This was the reason I found and modified this script.

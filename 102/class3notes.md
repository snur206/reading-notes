# Class 3 Reading Notes

**Version Control** 

Is a system that allows you to revisit various versions of a file or a set of files by recording the changes. 
With version control you can revert a file or project to a previous version, track modifications and modifying individuals and compare changes
Using Version Control System (VCS) mistakes with files can be corrected
**Local Version Control** 

was created by programmers years ago
Local VCS entails database on your hard disk that stores/saves changes to the files

**Centralized Version Control**

The need for collaboration within a developer team on a single file or a set of files where it would lead to the arrival of the Centralized Version Control System (CVCS)
System entails a single server storing all of the changes and file versions that can bee found/accessed by various clients 
Allows programmers to gain more knowledge of team members’ activities with certain files and gives administrators a lot more control over divvying up revision privileges.

**Distributed Version Control (DVCS)**

Addresses the major vulnerabilities from CVS: server as a single point of failure.
If CVS goes down, collaborators will cannot work with one another on a file, save changes and new versions.
All work will be lost, except any portions on local machines in the event of corruption of the central database’s hard disk if it has no backups.
DVCS allows multiple mirrored repos where programmers that are working in teams can collaborate with each other in different ways to finish a team project. That enables the use of various workflows be done at the same time.

**GIT?**

*Snapshots*

Git is a DVCS that stores date in a system made of snapshots. Every time you save a changed version of your project (commit) Git will create a snapshot of the file and stores a reference to it. 
Git only stores a reference to the already-stored identical version of it.

*Local Operations*
Most necessary information can be found in local resources, which is why Git mostly relies on this. 

*Tracking Changes*

Every change applied to any file or directory is tracked by Git. Git as the gatekeeper, will always detect file corruption or loss of information in transit.

*Loss of Data*

Git is a setup that minimize the possibility of irreversible damage to files, like accidentally losing data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost. 

*States*

Files in Git can reside in three main states: committed, modified and staged.

*Committed*

Data is securely stored in a local database

*Modified*
File has been changed but not committed to the database

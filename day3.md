# A Git Tutorial

### Version Control

Version Control is a system that allows to revisit various versions of a file or set of files by recording changes.

Version Control (VCS) allows: 
+ file or project can be reverted to previous cersion
+ track modifications and modifying individuals
+ to ompare changes

### Local Version Control

Local VCS entails one database on your hard disk that stores changes to files.

### Centralized Version Control
Created because of the need for collaboration within a developer team on a single file or set of files. Single server stores all changes and file versions kind of data backups.

### Distributed Version Control System (DVCS)
Help to avoid the one big disadvatage: the server as a single point of failure. To avoid data lost DVCS allows clients to create mirrored repositories

## GIT

### What is git? 
It is a Version Control System. A system that keeps track of all versions, history of changes. 

I gives the ability to view, apply and remove those changes. Git keeps all the project files in one repository. Allows multiple poeple on the code, on the same file together.

### How does it work - Snapshots taken in time. 

Commit (snapshot) represents each succesive version of file or files. It is the Git version of save as. Commit keeps track of what the file look at the different point of time.

#### Keeping track
- each commit (snapshot) has a label that points to it
- HEAD - the label meaning "You are here"
- There can be a message assign to the commit
- Messages - captions for the snapshots  

### What is a Github?

A way to share code with others. Online place to store the code. IT uses git to help menage the team's work

## Other useful commands

#### To check the file Staus use:
```
$ git status
```
#### Tracking a file: 
```
git add filename
```

#### Tracking files:
```
$ git add *
```

#### Making a Commit:

After staging one or multiple files, the changes should be commited and recorded what you did within the commit message:
```
$ git commit -m “made change x,y,z”

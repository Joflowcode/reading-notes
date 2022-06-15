## Class 03 Reading Notes

CLass 03 Reading Notes

**Plain language summary per assignment:** 

We learned more about git which is a version control system. In short that means it keepgtis track of all the changes you make to a file, the time, what was changed, what the originial looked like. It gives a full history of the file's life.

The "Head" is the current most recent version of your file in GIt.

A repository are files that you have told Git to pay attention to. Git is not keeping version control history.

* Add
* Commit
* Push

ACP is like staging a pic, taking pic, then sharing.

So add the file with git add
then commit it with a comment
then make sure to push it (correct branch, main for this course)

git pull origin main  - to get github commits to local terminal

**Lecture Notes**

Git is a version control system

(example given of a term paper with different titles for different 
* drafts.doc
* term paper.doc
* term paper 2.doc
* term paper with footnotes.doc
* final term paper.doc
* term paper for submission.doc
* term paper for submission for real.doc

commit (snapshot) has a label
HEAD = The label meaning "You are Here"

Github - a place to store your code to others. Github uses git to hel you manage your teams work

Repository is a collection of files that you've told Git to pay attention to. 

Add, Commit, Push

Linking repo
it is done by cloning from cloud to local machine


Gives us a git number after commiting 

**Vocabulary**

* VCS - version control system. In short that means it keeps track of all the changes you make to a file, the time, what was changed, what the originial looked like. It gives a full history of the file's life.

* Git vs Github - GIt is a version control system, github (online code storage) stores the code that you are working with git
local vs remote  Git is the local storage for repositority, github is remote. 

* clone - copying your repository from github to local repository on git


**Commands Learned:**

git clone https:link 

git remote -v

git status

git add

git commit -m

git push origin main (we are only using pain for this course)

**Reading Notes from Udemy Git Course in Reading 3 Assignment**

Exact Quotes from article

> **Snapshots**
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

> **Tracking Changes**
Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

Files in Git can reside in three main states: committed, modified and staged.
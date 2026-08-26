# Version Control

The original idea of _Version Control Systems_ (VCS) was to manage tracking changes to documents. The associated meta-data can also be stored; who made the changes, when, and why?

In the past when I worked on long-lived documents, at the start of each session I saved previous version with a date stamp. In every document repository, I have a folder called archive. I can go back to every version I’ve ever written of that document, and I can estimate how much work I put in at any time and how productive I’ve been.

But it’s a manual system and it’s intended for the use of a single person for documents without complex version structure or development branches. And I still do this for important documents! This is a manual _Local Version Control System_, (LVCS) although any system worth that name probably has an underlying database to track things.

When I started configuring Unix and DOS based systems, I started keeping script files. My earliest scripts dated back to the 1980s. I started putting in headers and revision numbers. If I could port these to a new Unix system, I could run my scripts and configure systems very quickly. Then the cloud came along!

Dropbox let me share to Windows or Linux, all my scripts moved there. But I was still using very manual techniques or _Subversion_ on a Cloud share. However, the open-source world has moved heavily to GIT and website services like GitHub. These tools are different, although most people seem to associate them as being the same.

In this sequence of notes, I will introduce you to GIT and GitHub in both Windows and Linux. My preferred version control has been GIT for several years now. At the start of any collaborative project, I will create a git repository dedicated for that project.

After that, I’ll consider opening the project to my collaborators. This is a _Centralized Version Control System_(CVCS). I can take all this one step further, by mirroring the contents of a CVCS to my local system and working on it independently.

Every copy is a full backup of the original.

If we set up some tracking mechanisms so that multiple users can make changes and then merge them together to the CVCS, we have a _Distributed Version Control System_ (DVCS).

I can add a file, so it becomes a tracked document. When I make a change as a distributed copy, I can stage those changes, selecting which files are to be included. I can commit those changes, permanently recording them in the local database. I can then push the change to the DVCS.

Sometimes when I’m working on academic papers with collaborators, we use tracking in Word. It can be madly complicated, as we all make changes, put in notes, change the changes, etc. We need something better for complex documents and projects.

In such a system, we can see

- What changes were made and keep track of the changes in the long term
- Who made changes (blame)
- When they were made
- We can go back to earlier versions.

What is the scope and functional requirements for a versioning system?

Firstly, I need my files to be kept in a location where they can be accessed by me and by others. In a revision control system, a starting point is to create a repository or repo. There is an expression; _single source of truth_. You can’t have multiple, unconnected versions of the same project. If the versions are unconnected, that’s a different project.

If we _clone_ a repository, we create a copy, but we could keep it synchronized with the original. You can clone any repository which has public access or which you have authentication to access.

For any public repository, you could create a _fork_, that is a copy of that repository in your own account; everything. From the time you fork the repository, it is a separate strand of development. If the owner of the original repo performs other commits, they will not show in your fork. Similarly, if you perform commits, they do not show in the original repo. After an initial release, the repository could hold bug fixes, new versions, etc.

Secondly, we would need to be able to track any files in the repo considering collaboration between team members. 

Finally, we should be able to see who did what and when, we call this _blame_. We need the ability to roll-back changes which might have proved problematic, accountability.

Although we can track files individually, for complex projects we track the project as a whole and files are specifically subject to revision control. Where a user needs to edit a file, it is checked out and made available to that user as a working copy. When the user is satisfied with the edit, they can commit the file by saving it and then checking it in, back into the repository. 

But I may need to change several files for a single feature add or bug fix. I will make sure each of these files is tracked by using the _ADD_ command. We say this file has been __staged__. When I have made my changes to all these files I will perform a _COMMIT_. Each time a commit occurs, it is identified by a unique revision number and the most recent version is the _HEAD_. A commit is the checkpoint I can revert back to if I need to reverse my changes.

If multiple people are working on the same dataset, then they may produce conflicting edits, and any revision control system will require a protocol for merging changes. Thinking of this in terms of graph theory, the version control system can be viewed as a directed tree with multiple parallel lines of development which may branch and later merge. Multiple users can share a version control system, but it is possible to have conflicts, and, in this case, manual intervention may still be required during merge operations.

The above summary will make more sense after you go through the worked example.


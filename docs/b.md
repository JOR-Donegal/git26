# GIT

Linux kernel development was informal from c. 1991 onwards, with patches being passed around in various archive formats. From c. 2002, these patches were maintained in a proprietary distributed version control system; BitKeeper. In 2005, free access to this DVCS was removed and legend has it that Torvalds wrote GIT in 10 days!

GIT is based on a repository (or repo), a file system with meta-data to track versioning. Each time a change is committed, GIT takes a snapshot of what the file system looks like; any file which has been changed is stored, and file which is unchanged is saved as a link to the previously saved version.

All operations are local, you only need to be connected to the Internet to update a central repo.

Integrity is built into GIT; every file is fingerprinted using a SHA1 hash. A hash is a unique fingerprint of a file, changing any character will change the hash value.

## Installing GIT

At the start of any collaborative project, I will create a git repository dedicated for that project. I will set the repository up to a consistent best practice and add readme files and structure. I’ll do some initial work on code if I think patterns and practices need to be established. After that, I will consider opening the project to my collaborators.

GIT and GITHUB are related but they are separate tools and have completely different purposes.

GIT is a revision control system, GITHUB is a centralized hosting service for GIT, as a distributed version control system.

I mostly use GIT on Linux, but it is an easy install on Windows as well.

If you are experimenting with GIT, download the appropriate installable from the Internet. Before you install, I recommend you select and install a programmer’s editor.

Across all platforms I now use Visual Studio Code (VSC).

Note that you must install the text editor before installing GIT. 

I do a lot of development work in Linux, and GIT is ideal for keeping shell scripts, configuration files, Ansible playbooks, et cetera.

A lot of my coding is in Python, and the IDE I use (VSC) integrates seamlessly with GIT.

Python itself is hosted by GITHUB!

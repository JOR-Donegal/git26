# Add and Restore

Type 

````dos
git status
````

to see the status of this repository.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig16.jpg">
<figcaption>Fig 16. Configuration.</figcaption>
</figure>

I created a file called hello.bat, but I have not added it to the repo. A file can be in the folder, but not managed by Git. Type

````dos
git add hello.bat 
````

to stage file(s) __hello.bat__.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig17.jpg">
<figcaption>Fig 17. Configuration.</figcaption>
</figure>

Prior to this, the file is not yet _tracked_. Stage means that a file is made ready to add to the repository but is not yet added. We can continue to make changes to that file without those changes being copied to the repository. None of those changes are recorded and it will not be possible to revert to these versions.

The format of the command is 

````dos
git add name
````

to stage a file or directory. If I think I have mangled the file I am working on, I can type 

````dos
git restore filename
````

to get the last good version of the file in the repo and overwrite the one in my working directory.


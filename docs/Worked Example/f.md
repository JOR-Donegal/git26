# Diff

Being able to see the difference between two versions of a file is a critical function of version control. I made a small change to hello.bat and save as if I am working on a real project now.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig18.jpg">
<figcaption>Fig 18. A test edit.</figcaption>
</figure>

If I run the command 

````dos
git diff hello.bat
````

I get difference information on versions of the file. The minuses signify that something was removed from that version of the file, and the pluses signify that something is added to the file.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig19.jpg">
<figcaption>Fig 19. A diff output.</figcaption>
</figure>

The green text with the + shows what was added.

The red text with the - shows what was subtracted.

GIT was always based on text files and will detect any change to any line. A small change to a line will be treated as if that line was deleted and then the edited version added as a new line.

If I type 

````dos
git status
````

I can see what the status of these changes is and it even tells me what to do.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig20.jpg">
<figcaption>Fig 20. A status output.</figcaption>
</figure>

I can add the file and commit, or I can restore the previous version.

The __diff__ command allows us to track back previous versions and see what changes have occurred to the current state. In the example below we can see unique hash value associated with this update. Go research what a hash value is, we will cover it in more detail in the networking module.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig21.jpg">
<figcaption>Fig 21. Hash values.</figcaption>
</figure>

# Roll back

The main purpose of our version control system is to store versions of files, to have the ability to review these versions, and to revert to any version.

First, I review the log, one line at a time.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig24.jpg">
<figcaption>Fig 24. Review log entries.</figcaption>
</figure>

I want to revert to the previous committed version, I use the command


````dos
git revert HEAD
````

Visual Studio Code pops up so I can add a message. I click the tick symbol.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig25.jpg">
<figcaption>Fig 25. Review log entries.</figcaption>
</figure>

A quick review of the file demonstrates that I have reverted.

There are many functions which we can use to undo changes, I'm not going to go into them here.

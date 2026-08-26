# Config Parameters

At some point, we need to be able to identify users. Git recommends we add the global username and e-mail to our information. You may see prompts for this when you commit. 

I will also set my default editor. I use the commands

````dos
git config --global user.name "john.oraw"
git config --global user.email john.oraw@atu.ie
git config --global core.editor “code --wait”
````

If you enter a command like commit without a message, Git will open Visual Studio Code (VSC) for you to type the message. The wait argument causes Git to wait for VSC to close and complete before committing. The command 

````dos
git config --list
````

gives me a lot of configuration information and it should show these new parameters.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig15.jpg">
<figcaption>Fig 15. Configuration.</figcaption>
</figure>

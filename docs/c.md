# Install on Windows

In an ATU Laboratory, GIT should already be installed. If not, talk to your lecturer!
I normally get students to build a Windows VM , I do not ask you to install software on your laptop.
Assume the instructions below are for a Windows 11 VM.

## GIT

Create a directory to do your work in. I am using C:\Users\student\Desktop\GIT

On my Windows 11 machine, I go to https://git-scm.com/downloads.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig1.jpg">
<figcaption>Fig 1. GIT download.</figcaption>
</figure>

I download the 64-bit version and double-click to install. I use defaults until I get to choosing an editor. Choose Visual Studio.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig2.jpg">
<figcaption>Fig 2. Editor.</figcaption>
</figure>

Use main as the default branch.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig3.jpg">
<figcaption>Fig 3. Branch.</figcaption>
</figure>

Use defaults until you get to the terminal, choose Windows Default.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig4.jpg">
<figcaption>Fig 4. Terminal selection.</figcaption>
</figure>

Use defaults for the remaining options.

## GIT GUI

If you run GIT GUI, you will get a screen similar to

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig5.jpg">
<figcaption>Fig 5. GIT GUI.</figcaption>
</figure>

## Test

Go to the terminal in your Python development directory and type 

````
git –version
````

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig6.jpg">
<figcaption>Fig 6. First test.</figcaption>
</figure>

I have previously created a directory called C:\Users\student\Desktop\GIT

In file explorer, I go to this directory and right-click, select Show More Options. then select __Open Git GUI here__.

I create a repo called 26OCT23. I will use that for all the following exercises.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig7.jpg">
<figcaption>Fig 7. New repo.</figcaption>
</figure>

I now have a graphical summary of my new repo.

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig8.jpg">
<figcaption>Fig 8. GUI.</figcaption>
</figure>

Many people will encourage you to use the GIT Bash shell. I will not be using that here.

In File Explorer, I go to View->Show->Hidden Files.

There is a hidden GIT directory!

<figure>
<img src = "https://jor-donegal.github.io/git26/images/fig9.jpg">
<figcaption>Fig 9. Hidden directory.</figcaption>
</figure>

If I wanted to write code now, in file explorer, I go to this directory and right-click, select Show More Options. then select Open with Code here. 

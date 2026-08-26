# Finally

We have scratched the surface and left out many critical features, such as branching. I'll cover branches in a follow up when we look at GITHUB.

## Binary Files

When I’m working with some IoT devices, they have binary configurations. Although Git can track these and even identify that files differ, it is primarily a text tool, it doesn’t analyze binary files well.

## GIT Ignore

If there are specific file types which you do not want GIT to check into a repo,  you define these in a file called __.gitignore__ in the root of a repo.

More on this when we look at GITHUB.

You can also have .gitignore files in each specific folder. So for example, I could have a folder of shell scripts with specific things to ignore. In my Python repos, I have the line *.pyc in my .gitignore, so compiled Python code does not get included in the repo.

Sometimes we include credentials or SSH keys in a working directory.

If you have just read through these notes, you, will remember nothing!

- Go through the steps in the walkthrough. These worked when I carried them out but products and operating systems change. If you run into a problem, try to resolve yourself.
- At the end of all this, you should have a folder called exercise1. We ill need that later.
- Do a cheat sheet of the basic commands you have learned (in Excel) and save it in your exercise folder.  

And locate a good primary reference source. I use this [site](https://git-scm.com/learn) as mine.

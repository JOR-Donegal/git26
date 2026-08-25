# Introduction

!!! abstract "Using GIT"

You may have done coding before and if you are like most people, there are bits of programmes on your hard drive or cloud share. Not very useful! In most working environments, we would move our code to a _repository_ or _repo_. This is primarily a code archive, where we can see current code, as well as the versions that mark its evolution. The versioning aspect of this it's critically important.

- I can roll my code back to a point in time before an error was made, perhaps.
- I can work collaboratively, and each contributor can see and track what others have done.

You will hear the terms _version control_, _revision control_ and _source control_. If I mix up the naming, I am referring to the same thing! These notes are delivered as part of Infrastructure as Code (IaC) learning. Realistically, we do not automate without having the repo sorted out first.

And its not just for coding, think about network appliance configuration files. Suppose you save the configuration of a router or switch in a Git repo. Does this have a useful purpose? Would the ability to review differences from configuration to configuration have a value? As a good practice, you should always have a good, known version of a project or configuration.


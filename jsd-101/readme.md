# GIT

Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

![git-basic-flow](https://securitypatterns.io/images/01-code-mgmt/overview.png)
> -- <cite>[image author][1]</cite>

# Goal

Learn what is git and to perform a git push to some github repository

# Basic usage

- [Codemy School - GIT: Installation, Configuration and First Commit](https://www.youtube.com/watch?v=QqP7YZlZEOo&ab_channel=CodemySchool)

# Theory

- [Introduction to Version Control with Git](https://warwick.ac.uk/research/rtp/sc/rse/training/introgit/introduction_to_version_control.pdf)
- [Introduction to Version Control with Git and GitHub](https://indico.cern.ch/event/814979/contributions/3401190/attachments/1831474/3105348/git_workshop.pdf)


# Why use Git?

**The distributed architecture**

Unlike Centralized version control systems that force developers to access the single central repository to be able to “checkout” and commit changes to the individual files, Git follows a distributed approach. In the distributed architecture, every developer has their own local copies of the entire central repository, allowing them to work offline, access complete revision history and easy branching and merging.

**Powerful performance**

Branching, merging, committing, etc. are really easy and fast with Git workflow because of its intelligent deep knowledge algorithms that understand the access patterns to the T.

**It is Secure**

Git stores all file content including relationships between versions and directories, cryptographically using a SHA1 as its hashtag algorithm. Any accidental or malicious code change is completely traceable.

**Open-source**

Being open-source, Git is free, enjoys good community support, continuously scrutinized for quality and is backed-up with loads of documentation and tutorials for learners.

**Faster releases**

Git’s distributed development and easy branching and creating of new features encourages developers to make more frequent changes in an agile workflow
> -- <cite>[Git Best Practices – How to make the most of (g)it][2]</cite>

# Workflow & Commonly Used Commands

Let's review a simple project workflow and the CLI commands that help us move from one step to the next. Below is a diagram of a workflow including Git & Github. This diagram most closely represents the flow of my group project.

![git workflow](https://i.ibb.co/YB1tBJ5/git-workflow.jpg)

> -- <cite>[Molly Nemerever - dev.to/mollynem/git-github--workflow-fundamentals-5496][3]</cite>

More readings:

- https://ipbus.web.cern.ch/doc/dev/html/workflow.html

# Distributed Teams

Having a distributed system, Git allows the users to work simultaneously on the same project, without interfering with others’ work. When a particular user gets done with their part of the code, they push the changes to the repository and these changes get updated in the local copy of every other remote user which pulls the latest copy of the project.

![git Distributed](https://media.geeksforgeeks.org/wp-content/uploads/20191203164948/Distributed-Version-Control-System.jpg)

> -- <cite>[www.geeksforgeeks.org][4]</cite>

# Installation and Configuration

**Windows**

- [Simplilearn - How To Install Git on Windows 10](https://www.youtube.com/watch?v=2j7fD92g-gE&ab_channel=Simplilearn)
- [How to Download & Install Git on Windows 10 & Choose Install Options](https://www.youtube.com/watch?v=nbFwejIsHlY&ab_channel=TheGrokShop)
- [ProgrammingKnowledge2 - How to Install and Configure Git and GitHub on Windows
](https://www.youtube.com/watch?v=J_Clau1bYco&ab_channel=ProgrammingKnowledge2)

**Linux**

Is already installed

# First Push

- [Codecademy - How to Push Code to Github](https://www.youtube.com/watch?v=wrb7Gge9yoE&ab_channel=Codecademy)
- [Study Zone- GitHub Create Local Repository and push to github | Push an existing repository to github](https://www.youtube.com/watch?v=vbQ2bYHxxEA&ab_channel=StudyZone)
- [Version Control and collaboration with Gitand Github](https://www.bu.edu/tech/files/2017/01/Version-Control-and-collaboration-with-Git.pdf)


[1]: https://securitypatterns.io/docs/01-code-mgmt-security-pattern/
[2]: https://drupalsun.com/shefali-shetty/2019/07/02/git-best-practices-%E2%80%93-how-make-most-git
[3]: https://dev.to/mollynem/git-github--workflow-fundamentals-5496
[4]: https://www.geeksforgeeks.org/git-features/

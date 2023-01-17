---
title: Read: 03 - Revisions and the Cloud
filename: Read03-revisionsandthecloud.md
---

# Lab - 03 Notes

Doing this Lab got me more familiar with using the terminal and Git. I learned how to move around with my terminal using `cd ..` `touch` `mkdr` and others. I now find it easy to move in between folders and create new files. 

I'm also happy with Git, like clone, pull, push, add, commit etc. 

Using code like `touch Read0{1..10}.md` is also really helpful to quickly make many files, as we had to do for the lab. I was surprised how easy it was to learn and get used to working this way. 


Below are my reading notes and some commands for GIT in further detail. 

Reworded and understood from [this](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)


## Version Control 

Version control is a filing system that makes you avoid doing the classic project_final_final02 that I remember fondly from my many .psd files. While project_final_final02 isn't a very good version control system (**VCS**) it *is* one, just very prone to error. Let's look at a better one. 

## Local Version Control 

My example above would be a local version control system. It's maybe a folder on my hard drive, or a database, where I store all my changes. When doing 3d work it was pretty common to use projectname_001, projectname_002 etc all in a pretty strict projects file. This isn't really made to be shared with others, or stored off my local drive. 

## Centralized Version Control. 

What if we need multiple people to be able to make changes? We could upload all of our files to a server, that stores all changes/file versions from multiple users. This is much better for collaboration (an admin could restrict access to files). There are still some issues...

## Distributed Version Control 

What if our CVC server goes down? Or someone sets fire to our server? Or a kaiju attacks? None of our workers will be able to work! Instead of relying on a single point of contact (our Centralized Server) lets distribute our files among all our workers, so we have mirrors of all our files. 

# What is Git?

Git is a DVC system, that revolves around Snapshots

### Snapshots 

Each time you save a version of your project from your working directory, called a 'commit' - Git creates a 'snapshot' of the file and creates a reference to it. 

### Local Operations 

Git seems to make file saves to your local system because it's faster then fetching new data from a remote each time you change something. 

### Tracking changes

Git sees all changes. It observes. 👀 This makes it hard to lose data. 

### States 

Files in Git exist in three main states: Committed, modified and staged

* Committed - Data is stored locally (git commit)

> Modified - Your file has been changed, but it has not been committed to the local database. (ie in VS code)

* Staged - You've flagged a files modified version to be committed  (git add)

![Git Diagram](https://phoenixnap.com/kb/wp-content/uploads/2021/09/git-workflow.png)

## Getting Git Working

### Import and Clone, Track and Push

To import from a remote repo, use 

`git clone https://github.com/test`

We now have a copy of all of our files from our remote repo (doesn't have to be GitHub) and have initialized git inside it. It will automatically retrieve the latest version of the files.

To target the location of the clone, use:

`git clone https://github.com/test myfolder`

`add` will add files from your working directory to your index

`commit` will commit files from your index to your head

    Head is your main/important branch. It's where your brain is!

**Tracked** files are tracked and can be modified, staged, etc

**Untracked** Were not included in the latest snapshot. 

After editing a file, Git will flag is as having been modified. 
We then stage the file. 

To see the state, we'll use `git status`

`git remote -v` lets you view all the remote URLs your repo is tied to. 

`git fetch [remote-name]` will let you fetch data you don't have from a remote repo. It doesn't merge. 

`git push [remote-name][branch-name]` will push files to a remote repo once you've committed them. eg `git push origin main`


### O S*!T I wanna undo

`git commit --amend` will alter a commit message, or allow you to add files you've forgotten. 

To unstage a file do:

`git reset HEAD index.html`

Will uncommit your index.html and return it to the modified stage. 

`git reset --hard` Git will overwrite all changes, destroying all uncommited changes. Bit scary!

To undo a committed snapshot:

`git commit -m "example"`

`git revert HEAD`

Git will make a new commit so you don't lose the old commit? - Look up

To return your file to its state when you last committed it, use

`git checkout -- example.html`

Not on the above - you are overwriting any other changes you've made - you are importing the last version you committed and overwriting other changes.









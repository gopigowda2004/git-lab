
Commands
Git add

Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.
Related tutorials
Saving changes: git add
Learn Git with Bitbucket Cloud: Copy your Git repository and add files
Using branches: git merge
Inspecting a repository: git status
Git branch

This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.
Related tutorials
Using branches: git branch
Using branches: git checkout
Using branches: git merge
Learn Git with Bitbucket Cloud: Use a Git branch to merge a file
Git checkout

In addition to checking out old commits and old file revisions, git checkout is also the means to navigate existing branches. Combined with the basic Git commands, it’s a way to work on a particular line of development.
Related tutorials
Using branches: git checkout
Undoing changes: git checkout
Comparing workflows: Gitflow workflow
Git clean

Removes untracked files from the working directory. This is the logical counterpart to git reset, which (typically) only operates on tracked files.
Related tutorials
Undoing changes: git clean
Git clone

Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.
Related tutorials
Git LFS
Comparing workflows: Forking workflow
Setting up a repository: git clone
Git commit

Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.
Related tutorials
Using branches: git merge
Rewriting history: git commit --amend
Learn Git with Bitbucket Cloud: Copy your Git repository and add files
Saving changes: git add
git commit --amend

Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.
Related tutorials
Rewriting history: git commit --amend
git config

A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.
Related tutorials
Setting up a repository: git config
Git LFS
Install Git: Install Git on Mac OS X
Install Git: Install Git on Linux
git fetch

Fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.
Related tutorials
Syncing: git fetch
Refs and the reflog: Refspecs
Syncing: git pull
git init

Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.
Related tutorials
Setting up a repository: git init
git log

Lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.
Related tutorials
Inspecting a repository: git log
Advanced Git log: Filtering the commit history
Advanced Git log: Formatting log output
Advanced Git tutorials: Overview
git merge

A powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.
Related tutorials
Merging vs. rebasing: Workflow walkthrough
Using branches: git merge
Comparing workflows: Gitflow workflow
Merging vs. rebasing: Conceptual overview
git pull

Pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.
Related tutorials
Syncing: git pull
Comparing workflows: Centralized workflow
Git LFS
Comparing workflows: Forking workflow
git push

Pushing is the opposite of fetching (with a few caveats). It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. This is like svn commit, but it sends a series of commits instead of a single changeset.
Related tutorials
Syncing: git push
Refs and the reflog: Refspecs
Comparing workflows: Gitflow workflow
Git LFS
git rebase

Rebasing lets you move branches around, which helps you avoid unnecessary merge commits. The resulting linear history is often much easier to understand and explore.
Related tutorials
Merging vs. rebasing: Workflow walkthrough
Rewriting history: git rebase -i
Merging vs. rebasing: Conceptual overview
Rewriting history: git rebase
git rebase -i

The -i flag is used to begin an interactive rebasing session. This provides all the benefits of a normal rebase, but gives you the opportunity to add, edit, or delete commits along the way.
Related tutorials
Rewriting history: git rebase -i
git reflog

Git keeps track of updates to the tip of branches using a mechanism called reflog. This allows you to go back to changesets even though they are not referenced by any branch or tag.
Related tutorials
Rewriting history: git reflog

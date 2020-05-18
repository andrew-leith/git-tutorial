# git-tutorial
Git and Github Basic Tutorial (1st draft)

Git and Github are two related tools for managing code, documentation, and related files.  Used in concert, they facilitate **version control** - the process of editing files while maintaining a continous history of previous iterations of those files.  

Git is a command-line tool for tracking changes in files; it also enables synchronization of files between a user's computer and a remote **repository** (sometimes abbreviated "repo") where files are hosted.  Repositories are used to store files for a variety of reasons - backup/archiving, publication, and collaboration between multiple developers are among the most common use cases for respositories.  The most well-known repository hosts are Github, Gitlab, and Bitbucket; this document is hosted on the andrew-leith/git-tutorial repository on Github.

Github is a web platform for hosting git repositories.  On Github, a repository can be either public (that is, shared with all users), or private (shared only with users of a particular organization).  A repository can contain multiple files, and in general, a given project is allocated its own repository.  There are cases where a project is spread across multiple repositories, but it is generally bad practice to have multiple separate projects within a single repository.  Github is the most popular platform for use with git, as well as the most commonly used host for source code in the world; thus, when people talk about using git or Github, they are typically addressing both of these tools collectively unless otherwise specified.

This document constitutes a brief 15-minute introduction to using git and Github.

### Repository Creation

placeholder

### Synchronizing / Managing Files

To begin working with your new remote repository, you must synchronize it with a directory on your computer.  Creating a local copy of a remote repository hosted on Github is simple - all that you need to do is click the large green button on the repository's main page labeled "Clone or download", copy the URL, and use the `git clone` command.  `git clone` creates an exact copy of the remote repository in your terminal's working directory.


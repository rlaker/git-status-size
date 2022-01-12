# Git-Status-Size

I have been caught out a few times by committing files larger than 100mb, which throws an error when uploading to Github. This then involves a complicated [filter-repo](https://github.com/newren/git-filter-repo) process to remove the files from the git history.

I found [Git-Status-Size](https://github.com/jtloong/git-status-size) which checks the size of the files in `git status` and then prompts the user if they want these files to be added to `.gitignore`. This is a great idea, but I use [Git Bash for Windows](https://gitforwindows.org/), which does not include the `bc` command to do calculations. Therefore, I have adapted to it now use `awk` instead.
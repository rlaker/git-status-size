# Git-Status-Size

This is a small custom git command that allows you to see the sizes of all of the untracked, modified, and added files in a repo.

## Installation

1. `git clone https://github.com/jtloong/git-status-size`
2. You'll have to move the executable into your git PATH. For my machine this would be `sudo cp git-status-size /usr/bin/`
3. `chmod +x git-status-size`

Now it should work! Go to any repo and in the command line call `git status-size`, and you should get an output like so:

```bash
----
Added: edited_file.jpg - 7.28 mb
Added: new_file.jpg - 7.28 mb
Modified: sequence-alignment/.ipynb_checkpoints/Untitled-checkpoint.ipynb - 0 mb
Modified: sequence-alignment/.ipynb_checkpoints/experiment_2-checkpoint.ipynb - 0 mb
Modified: sequence-alignment/Untitled.ipynb - 0 mb
Modified: sequence-alignment/experiment_2.ipynb - 0 mb
Modified: sg2im - 0 mb
----
```

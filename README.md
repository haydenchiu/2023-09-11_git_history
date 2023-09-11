# 2023-09-11_git_history
DSCI521_lecture_3

Definitions: 
- clone: copy remote to the local computer and make a connection between the local repo and remote repo.
- init: 
- `add <FILENAME>`: put short listed files from the local repository to the staging area.
- `commit -m "MESSAGE"`: commit with a message everything in the staging area.
- `push <WHERE> <WHAT>`: upload the commits to remote (where) using the commits from specificed branch (what).
- `pull <WHERE> <WHAT>`: pulls (updates) the local repo with contents in the remote (where) using the information in the specified branch (what).

- `log`: shows the log
    - `log --oneline`: shows the log in condenced format
    - this may open a terminal program called `less` that lets you scroll.
    - use `q` to quit out of less.

- `diff`: shows you the difference between your changes and last known git state.
    - `diff --staged`: shows you the diff of the files in the staging area.
- `restore --staged <FILE>`: unstages <FILE> from the staging area.

Here's a change by mistake...
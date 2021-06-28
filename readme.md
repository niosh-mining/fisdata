# FIS DATA
A repo for storing (smallish) data files used by FIS. It is not to be used directly but rather by certain fis modules.

## Adding files

Simply find (or create) an appropriate subdirectory in the data folder and add your file. Please don't add files which are bigger than a few dozen mb.

## no diffs

The following command is useful to avoid storing differences in binary files in git

Command to ignore index:
git ls-files -z data/ | xargs -0 git update-index --skip-worktree


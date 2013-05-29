git-helpers
===========

Some helper scripts for common operations I need to perform that arise as
a result of using multiple disjointed git-svn repositories.

### git-apply-if-check
Run git apply --check on a list of patch files, and apply them with with git am.

### git-dir-format-patch
Run git format-patch 1 by 1 for the top N patches of a given directory.

### git-scpchanges
Copy changed but unstaged/uncommitted files over scp.

### git-tarchanges
Archive changed but unstaged/uncommitted files.

git-hooks
=========

The name pretty much says it all.  They're git-hooks I've written/stolen for
some purpose or another.

## pre-commit
A PHP hook which checks the current branch against entries in a blacklist and
forbids the commit if it's being made against one of the blacklist branches.

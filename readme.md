ansible-common
==============

this repo has been created to reduce duplication and speed up development.
i have been creating similar code that can be re-used across multiple
projects

### naming standards

playbooks should be named in descriptive, easy to understand language
starting with the tool or application.

e.g. clone-git-repo should be named git-clone-repo to make it easy to 
identify and find git roles.

each playbook will have an example playbook to show by example and to test
functionality.

git-clone-repo
--------------

a fairly basic clone git 

### how to run?

```bash
    go-git-clone-repo.sh <repo> <workspace> [local]
```

### how it works?

imagine, for a moment, if you will.
- you want to perform this action remotely or optionally, locally
- you have some repo, http://github.com/foo/bar.git
- you want to clone the repo to /tmp/workspace so you end up with
  /tmp/workspace/bar
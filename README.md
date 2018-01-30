# workflow
short collection of ideas to improve the workflow

## github versioning and branching
Short tutorials are here:
https://git-scm.com/book/en/v2/Git-Basics-Tagging
https://www.digitalocean.com/community/tutorials/how-to-use-git-branches

Dispay all adresses you have registered for that repository::

    git remote -v

Setup your forked online repository path::

    git remote add my_origin https://urlto_repository_here

create new branch and checkout::
  
    git checkout -b newbranchname

make changes and commit all changes::
  
    git commit -a

push to forked repository::
  
    git push my_origin newbranchname

In case branch is close to completion send pull request to master
Go in browser to main repository and click PullRequest and select the branch you want to have merged.

## Profiling
Mark fills here ...

## Continuous Integration
Is an environment to automatically test the code base that is under development.
Hard to maintain and needs a lot of experience, ...

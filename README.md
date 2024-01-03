# Project1
Git &amp; GitHUB overview
$ git pull git://example.com/project.git theirbranch
Store the fetched branch into a local branch before merging into the current branch:
$ git pull git://example.com/project.git theirbranch:mybranch
After creating commits on a local branch, update the remote branch with your commits:
$ git push ssh://example.com/project.git mybranch:theirbranch
When remote and local branch are both named "test":
$ git push ssh://example.com/project.git test
Shortcut version for a frequently used remote repository:
# it is now included on git hub
# change 2

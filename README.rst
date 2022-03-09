Project test
============

- Create a new project project-test in GitLab
- Copy this project on a new local folder (example: ~/repos/sandbox/project-test1)
- Initialise git repo ::

    cd project-test1
    git init

- Set user and mail in local repo::

    git config --local user.name "user1"
    git config --local user.email "user1@maison.be"

- Set remote, add, commit and push ::

    git remote add origin git@gitlab.unamur.be:jbcabrer/project-test.git
    git add .
    git commit -m "Initial commit"
    git push -u origin master

Fix bugs, add features, do commits and merges.

- Clone the project in a new folder ::

    gti clone git@gitlab.unamur.be:jbcabrer/project-test.git project-test2
    cd project-test2

- Set user and mail in local repo::

    git config --local user.name "user2"
    git config --local user.email "user2@maison.be"

- fix bugs and test different scenarios with 2 users

# BGSU-Git-Tutorial
How to use Git for coursework at BGSU.

## Setting it up

There are a few ways to use git for your coursework.

* You can use Git locally to track your changes, and revert when things go wrong.
* You can use a remote git service such as GitHub or GitLab to enable easier collaboration.

### Installing Git

#### GNU/Linux
On Debian based Linux distributions such as Ubuntu or Linux Mint
`apt install git`

Most package repositories should just call it git.

#### Windows
Git is available at https://gitforwindows.org

## Common Git Problems, and diagnosing them.
$man git <command> answers a lot of questions.

#### I made a typo in my commit message!
$git commit --amend will allow you to edit the commit note.

## Git best practices.
Commit early, and often.
Use CI if you can.

# TECHed 🌍

### Setup Instructions ⬇


1. First fork this repo by clicking Fork icon 🍴 on top right corner & then clone your repo using command

```
$. git clone https://github.com/your_github_username/repo_url
or
$. git clone git@github.com:your_github_username/repo_url
```
2. Change directory & add upstream repository URL
```
$. cd Edfoal.github.io/
$. git remote add upstream https://github.com/Shiitu/TECHed.git
or
$.git remote add upstream git@github.com:Shiitu/TECHed.gitit
```
3. Always Pull recent changes from upstream repository before doing any work then checkout different branch other than main
```
$. git pull upstream main
$. git checkout -b branch_name
```
4. Make changes and stage those changes with this command.
```
$. git add .
```
5. Write commit message, Follow this [convention](https://www.conventionalcommits.org/en/v1.0.0/). 
```
git commit -m"commit_message_here"
```
6. Push those changes to your Fork Repo, and [Create Pull Request](https://www.atlassian.com/git/tutorials/making-a-pull-request).
```
$. git push origin your_branch_name
```
7. Sit back & Relax and wait for maintainers for rewiewing your [PR](https://www.atlassian.com/git/tutorials/making-a-pull-request).

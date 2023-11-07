Git setup


Git installation:
# sudo apt update
# sudo apt install git
# git --version

Setup git:
# git config --global user.name "Your Name"
# git config --global user.email "youremail@domain.com"


1. git clone repo
# git clone <repo url>

2. to check git branch
# git branch

3. To create a branch
# git branch <branch name>

4. To swicthc to a specific branch
# git checkout <branch name>

5. To check the status
# git status

<Create some file>

6. To add file:
# git add filename

7.To check working tree status:
# git status

8.To commit staged files to local repository:
# git commit -m "commit message"


9. Staging and committing multiple files:
# git commit  -a  -m "commit message"

10. git push code to remote:
# git push origin <branchname>

11. Merge the branch in remote repo to main branch
# Rasie pull request and merge.


The final outcome is the code from respective branch should be reflecting in main branch.


12. Git pull to get latest code in local repo
# git checkout main 
# git fetch 
# git pull

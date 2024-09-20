# PRACTICAL APPLICATION OF THE BASICS OF GIT WORKFLOW.
# 🎯Overview.
This is an exercise that allows me to not only practice, but to also put all that I have learnt over the past few days on Git Worflow to good use.

# 📢Intructions.
- Create a folder called learn_git.
- Cd (change directory) into the learn_git folder.
- Create a file called third.txt.
- Initialize an empty git repository.
- Add third.txt to the staging area.
- Commit with the message "adding third.txt".
- Check out your commit with git log.
- Create another file called fourth.txt.
- Add fourth.txt to the staging area.
- Commit with the message "adding fourth.txt"
- Remove the third.txt file.
- Add this change to the staging area. (Using the command "git add .)"
- Commit with the message "removing third.txt".
- Check out your commits using git log.
- Change your global settings to core.pager=cat - you can read more about that here.
- Write the appropriate command to list all the global configurations for git on your machine.
- You can type git config --global to find out how to do this.

# 🛠️Tools used.
- Git.
- Github.
- VSCode.
- Notebook.

```
git init
git add .
git commit -m "comment"
git log
git rm --cached "filename"
git config --global --list
```

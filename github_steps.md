# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

1. Create a cloud repo via the github website.
2. Navigate to the directory your project is located in
3. `git init` to establish tracking of the repo with git.
4. connect to local repo to the cloud repo via ssh key to your github account:
    - `git remote add origin git@github.com:USERNAME/REPO_NAME.git`
5. `git branch -M main` confirms that the directory you're working in will be the "main" branch of your cloud repo.
6. `git add <filename>` - To add the file to the staging area
7. `git commit -m "Message"` - To "Initial Commit" or provide details of what was changed in the code.
8. `git push origin main` to initiate upload of modified files to the cloud repo.
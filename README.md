# learning-git
Learning Git and Github via CLI

## Step 1:

If youre using git on your distro for the first time, you might need to generate an SSH key and add it to your github profile to get started.

1. ssh-keygen -t rsa -b 4096 -C "youremail"
2. eval $(ssh-agent -s)
3. ssh-add ~/.ssh/id_rsa
4. cat ~/.ssh/id_rsa.pub (copy the SSH key)
5. then go to your remote repository on github and goto settings-> SSH and GPG keys ->new SSH key ->enter any title and paste the copied SSH key and save it
 

 ## Git commands:

 1. git status: List of file(s) that have been added, deleted or edited but have not yet been saved in a commit
 2. git add .: tracks all the files in the current directory
 3. git commit -m "your message": creates a commit with your specified message
 4. git push origin "branch name": pushes the commit to the repo on github
 5. git init: Initialises git in the directory thats created locally

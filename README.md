# learning-git
Learning Git and Github via CLI

## Step 1:

If youre using git on your distro for the first time, you might need to generate an SSH key and add it to your github profile to get started.

1. ssh-keygen -t rsa -b 4096 -C "youremail"
2. eval $(ssh-agent -s)
3. ssh-add ~/.ssh/id_rsa
4. cat ~/.ssh/id_rsa.pub (copy the SSH key)
5. then go to your remote repository on github and goto settings-> SSH and GPG keys ->new SSH key ->enter any title and paste the copied SSH key and save it

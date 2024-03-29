This file's content is focused on making connection to github easy and secured.  

## Using SSH is the easiest and most secure way to connect to GitHub (clone, push,...). 
To do so, SSH keys must be created and added locally and to GitHub (only the public key is added to GitHub, NOT THE PRIVATE KEY! For more on how ssh keys work, see this [video](https://www.youtube.com/watch?v=y2SWzw9D4RA) and for how PKI works see this [video)](https://www.youtube.com/watch?v=FCf5LIJ0HWE)). With this option, there's no need to remember a passphrase or having to use a username and personal access token (PAT):

### Create SSH Keys: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

### Add Keys to Github account: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

### Test SSH Connection: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection

If using a private email on github, a commit email needs to be setup in order to push your commits to Github. This link goes over setting a commit email: https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address

If using a passphrase if preferred, this link goes over the steps to set it up:  https://docs.github.com/en/authentication/connecting-to-github-with-ssh/working-with-ssh-key-passphrases 

If using HTTPS  for cloning is preferred over SSH, this link outlines the steps to cache credentials in Git: https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git



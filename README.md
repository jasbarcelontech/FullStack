# Setup new GitHub Repository from scratch
# GITHUB Site
1. create GitHub Account
2. create new repository in GitHub

# TERMINAL PC
3. generate SHH first in terminal
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
        # https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
# GITHUB Site
4. Add SHH generated "id_rsa.pub" in GitHub Site
# TERMINAL PC
5. open terminal in desired folder to store git
6. git add README.md
7. git commit -m "first commit"
8. git remote add origin git@github.com:alexpchin/<reponame>.git
9. git push -u origin master


1)How to push first time local repo:
--create this repo in github
--git init -b main (It's name main because github branch has the same name )
--create local files and projects (local project must not be empty)
--git add -A
--git commit -m "my first commit"
--git remote add origin git@github.com:your_ssh_link_to_github_repo
--git push -u -f origin main

2)Git ask your credentials:
--git remote set-url origin github@github.com:your_ssh_link_to_github_repo

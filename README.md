# deploy bash

## Summary
This is an extra script for [git-ftp](https://github.com/git-ftp/git-ftp). You can easily deploy to your staging or production environment.

## How to use

1. Install git-ftp https://github.com/git-ftp/git-ftp/blob/master/INSTALL.md
2. Place the deploy file in your project folder
3. IMPORTANT .gitignore the deploy file
4. Insert your hosting credentials (staging and production) in de deploy file
5. Give permissions `chmod +x scriptname`
6. Be sure if your git repo is up to date.
7. Run the script `./deploy`
8. Some questions will be asked
8.1 Do you want to init the project? [yes or no] Type `yes` if this project isn't online yet or typ `no` if you want to update your current project
8.2 Where to deploy? [staging or production]
9 Your project is being deployed.
# Practicing connecting a Local Directory to a Remote Repository
## Steps for creating a GitHub repository
- Create a local repository (directory)
- Create a GitHub repository
  - In GitHub, select + and choose "New Repository"
  - Make sure you are listed as the "Owner"
  - Enter a repository name that matches the local repository
  - Leave the settings at default and choose "Create repository"
- Connect the two repositories
  - git remote add origin [ssh file]
  - git branch -M main
  - git push -u origin
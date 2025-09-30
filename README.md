**Git, WebStorm, and GitHub Tutorial for MAC**

**1. Install Git on Mac**
Git is a version control system used to track and manage code changes.  

   1. Open **Terminal**.  
   2. Install Git using Homebrew:  
      $ brew install git
   3. Check if it's installed by using
      $ git --version

**2. Configure Git**

  1. Before using Git, configure your identity
      $ git config --global user. name "Your Name"
      $ git config --global user.email "email"
  2. Check your settings
      $ git config --list

**3. Create a GitHub Account**

  1. Go to https://github.com/join
  2. Sign up for a free account
  3. Verify your email

**4. Install WebStorm**

  1. Download WebStorm which is free for students from: https://www.jetbrains.com/student/
  2. Install and launch WebStorm

**5. Connect Git with WebStorm**

  1. Open WebStorm.
  2. Go to Preferences -> Version Control -> Git
  3. Enter the Git path /usr/local/bin/git
  4. Test to confirm WebStorm recognizes Git
  
**6. Create a Repository on GitHub**

  1. Log in to GitHub
  2. Click the + in the top-right corner -> New Repository
  3. Name your repository
  4. Select Public and check Initialize with README
  5. Click Create Repository

**7. Clone a Repository into WebStorm**

  1. In WebStorm go to VCS -> Get from Version Control
  2. Choose Git
  3. Paste your GitHub repository URL
  4. Select a local folder to save the project
  5. Click Clone

**8. Create and Add Files**

Inside WebStorm:
  1. Go to File -> New -> HTML File or Stylesheet
  2. Save the file
  3. WebStorm will ask to Add to Git, Click Add

**9. Commit Changes**
Committing saves changes to your local Git repository

  1. In WebStorm, press Cmd + K or go to VCS -> Commit
  2. Write a short commit message, anything is fine
  3. Click Commit

**10. Push Changes to GitHub**

  1. Press Cmd + Shift + K or go to VCS -> Git -> Push

  2. Confirm and push

  3. Refresh your GitHub repository page and you’ll see your files online

Hendela, A. H. (2019). Introduction to GitHub and WebStorm [PowerPoint Presentation]. NJIT IS117.

**Glossary**

**Branch**: A parallel version of a repository that lets you work on changes without affecting the main project until you’re ready to merge.

**Clone**: A copy of a remote repository that’s downloaded to your local machine, so you can work on it offline.

**Commit**: A snapshot of your project at a specific point in time, recording changes you’ve made to tracked files.

**Fetch**: Downloads new data from a remote repository without applying it to your current work.

**Git**: A distributed version control system used to track changes in code and coordinate work among developers.

**GitHub**: A cloud-based platform that hosts Git repositories and provides tools for collaboration, issue tracking, and project management.

**Merge**: Combines changes from one branch into another, integrating updates.

**Merge Conflict**: An error that happens during a merge when Git cannot automatically resolve differences between two versions of the same file.

**Push**: Send your local commits to a remote repository.

**Pull**: Fetches changes from a remote repository and merges them into your local branch.

**Remote**: A reference to a repository stored elsewhere, connected to your local repository.

**Repository**: A storage space for your project that contains all files, commits, and version history tracked by Git.

# Git and GitHub Hands-on Assignment


## Student Details

**Name:** Rupa Gupta
**Course:** MCA
**Roll No:** 47
**Subject:** DevOps Lab
**Assignment:** Exploring Git and GitHub Commands


## Objective

The objective of this assignment is to learn and practice the basic concepts of Git and GitHub. This includes creating a repository, tracking changes, committing files, working with branches, and collaborating using GitHub.


## Tools and Technologies Used

* Git
* GitHub
* Command Line / Terminal
* Visual Studio Code (optional)


## Task 1: Setting Up Git and GitHub

1. Installed Git on the system.

2. Verified the installation using the command:

```bash
git --version
```

3. Created a GitHub account.

4. Created a new repository named **DEMO_GitHub_RollNo**.

5. Cloned the repository to the local machine using:

```bash
git clone <repository_link>
```

---

## Task 2: Configuring Git Locally

Configured Git with username and email using the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Verified the configuration using:

```bash
git config --list
```

---

## Task 3: Basic Git Commands and File Tracking

1. Navigated to the project folder.

```bash
cd DEMO_GitHub_RollNo
```

2. Created a file named **ReadMe.md**.

3. Checked the repository status:

```bash
git status
```

4. Added the file to the staging area:

```bash
git add ReadMe.md
```

5. Committed the changes:

```bash
git commit -m "Added ReadMe file"
```

6. Pushed the changes to GitHub:

```bash
git push origin main
```

---

## Task 4: Creating and Managing Branches

1. Created a new branch:

```bash
git checkout -b feature1
```

2. Created a file **feature1.txt** and added content.

3. Added and committed the file:

```bash
git add feature1.txt
git commit -m "Added feature1.txt"
```

4. Switched back to the main branch:

```bash
git checkout main
```

5. Merged the branch with main:

```bash
git merge feature1
```

6. Deleted the branch after merging:

```bash
git branch -d feature1
```

7. Pushed the updated changes to GitHub:

```bash
git push origin main
```

---

## Task 5: Collaboration Using GitHub

1. Learned about forking a repository.  
2. Cloned the forked repository to the local system.  
3. Created a new branch and made changes.

Checked the remote repository using:

```bash
git remote -v
```

4. Pushed changes to GitHub and created a **Pull Request (PR)**.  
5. Learned how merge conflicts can be resolved.

---

## Task 6: Undoing Changes

1. Unstaged a file from the staging area:

```bash
git reset ReadMe.md
```

2. Undid the last commit:

```bash
git reset HEAD~1
```

3. Checked commit history:

```bash
git log
```

Press **q** to exit the log.

---

## Conclusion

This assignment helped in understanding the basic workflow of **Git and GitHub**. It provided practical experience in repository creation, tracking file changes, committing updates, working with branches, and collaborating using GitHub. Git is an essential tool in **DevOps and modern software development** for version control and team collaboration.
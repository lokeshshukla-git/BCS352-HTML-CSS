# Experiment No. 2

## 1. Experiment Title

Pushing and Cloning a Repository

## 2. Aim

Create a local bare remote, push commits to it, and clone a working copy.

## 3. Software / Tools Required

- Visual Studio Code or another text editor
- Git and a terminal (for the repository exercises)
- A web browser such as Chrome or Edge (for HTML/CSS exercises)

## 4. Theory

A bare Git repository stores version history without a working tree and can act as a remote. A remote name such as origin is a shortcut for a repository address. Push sends commits to a remote branch, while clone creates a new local copy with repository history.

## 5. Algorithm / Procedure

1. Create ../html-remote as a bare repository, add it as origin, and list remote URLs.

2. Push the current branch and its commits to origin.

3. Clone html-remote into html-copy and display its commit history.

## 6. Program / Queries / Commands


- Task 1: Terminal commands: git init --bare, git remote add, git remote -v.

- Task 2: Terminal command: git push origin main (or master if that is the branch name).

- Task 3: Terminal commands: git clone and git log --oneline.

Refer to the listed task files and the assignment brief for the complete requirements. For the Git exercises, include the terminal commands required by each task.

## 7. Input

### Task 1
Existing html-lab repository and a local path ../html-remote.

### Task 2
Current branch name (main or master).

### Task 3
Local path html-remote and destination folder html-copy.

## 8. Output

The following images show the output screenshots already present in the GitHub lab folder:

### Task 1

![Task 1 output - Lab 2 - Task 1.png](Lab%202%20-%20Task%201.png)


### Task 2

![Task 2 output - Lab 2 - Task 2.png](Lab%202%20-%20Task%202.png)


### Task 3

![Task 3 output - Lab 2 - Task 3.png](Lab%202%20-%20Task%203.png)


## 9. Result

The lab tasks are completed by creating and running the required files or Git commands. Add the screenshots of your actual results above.

## 10. Viva-Voce Questions

1. What is a bare repository?
2. What does the origin remote represent?
3. How does git clone differ from git init?


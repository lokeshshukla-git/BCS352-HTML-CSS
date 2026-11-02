# Experiment No. 1

## 1. Experiment Title

Starting a Git Repository

## 2. Aim

Create a local Git repository, configure repository-specific identity, track an HTML page, and record changes in commits.

## 3. Software / Tools Required

- Visual Studio Code or another text editor
- Git and a terminal (for the repository exercises)
- A web browser such as Chrome or Edge (for HTML/CSS exercises)

## 4. Theory

Git records file changes in commits. The working tree holds current files, the staging area selects changes for the next commit, and each commit saves a snapshot with a message. Local Git configuration applies only to this repository, so this experiment sets and checks the author identity before tracking the HTML page.

## 5. Algorithm / Procedure

1. Initialize html-lab as a Git repository, set local user.name and user.email, and display both values.

2. Create index.html with an h1, inspect status, stage the file, and commit it as “Add home page”.

3. Add an h2 to index.html, commit as “Add next meeting heading”, and show the one-line history.

## 6. Program / Queries / Commands

### Task 1: Configure the repository

``` sh
mkdir html-lab
cd html-lab
git init
git config --local user.name "Your Name"
git config --local user.email "you@example.com"
git config user.name
git config user.email
```

### Task 2: Add and commit the first page

``` sh
git status
git add index.html
git commit -m "Add home page"
```

### Task 3: Update and commit the page

``` sh
git add index.html
git commit -m "Add next meeting heading"
git log --oneline
```

#### Complete source: index.html

```html
<!-- Name: LOKESH SHUKLA | Roll Number: 2510303281 | Assignment: BCS352 Lab 1 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML Lab</title>
</head>
<body>
    <h1>Welcome to My Lab</h1>
    <h2>Next Meeting</h2>
</body>
</html>
```

## 7. Input

### Task 1
Your Git author name and email; folder name html-lab.

### Task 2
An h1 heading of your choice.

### Task 3
An h2 heading of your choice.

## 8. Output

The following images show the output screenshots already present in the GitHub lab folder:

### Task 1

![Task 1 output - Lab 1 - Task 1.png](Lab%201%20-%20Task%201.png)


### Task 2

![Task 2 output - Lab 1 - Task 2.png](Lab%201%20-%20Task%202.png)


### Task 3

![Task 3 output - Lab 1 - Task 3.png](Lab%201%20-%20Task%203.png)


## 9. Result

The html-lab repository is initialized and configured with local author details. index.html is committed first with its home heading and again with the added meeting heading; git log --oneline displays both commits newest-first.

## 10. Viva-Voce Questions

1. What is a Git repository?
2. What is the purpose of staging changes?
3. What information does git log --oneline show?



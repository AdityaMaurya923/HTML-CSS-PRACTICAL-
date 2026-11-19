# Assignment 2: Pushing and Cloning a Repository

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Pushing and Cloning a Repository using Git.

## 2. Aim

To send commits to a second repository on the computer and make a copy of it with clone.

## 3. Software / Tools Required

- Git (version control system)
- Terminal: PowerShell / Git Bash / Command Prompt
- Any text editor (VS Code)

## 4. Theory

**1. Bare Repository:** A repository without a working folder, used as a shared remote (`git init --bare`).

**2. Remote:** A named link to another repository. `origin` is the usual name (`git remote add`).

**3. Push:** `git push origin <branch>` sends commits to the remote.

**4. Clone:** `git clone` makes a full copy of a repository, including its history.

## 5. Algorithm / Procedure

### Question 1: Create Bare Remote and Add origin

1. Start.
2. Run `git init --bare ../html-remote` inside `html-lab`.
3. Run `git remote add origin ../html-remote`.
4. Run `git remote -v`.
5. Stop.

### Question 2: Push Commits

1. Start.
2. Run `git push origin master`.
3. Stop.

### Question 3: Clone the Repository

1. Start.
2. Go up one folder with `cd ..`.
3. Run `git clone html-remote html-copy`.
4. Go into `html-copy` and run `git log --oneline`.
5. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Remote = ../html-remote, name = origin

**Question 2:**

- Branch = master

**Question 3:**

- Clone html-remote into html-copy

## 7. Output

Terminal output is saved in `output.txt` and `output.png` of each task folder.

**Question 1:**

```
PS D:\My Space\Assignments\Assignment2\html-lab> git init --bare ../html-remote
Initialized empty Git repository in D:/My Space/Assignments/Assignment2/html-remote/
PS D:\My Space\Assignments\Assignment2\html-lab> git remote add origin ../html-remote
PS D:\My Space\Assignments\Assignment2\html-lab> git remote -v
origin	../html-remote (fetch)
origin	../html-remote (push)
PS D:\My Space\Assignments\Assignment2\html-lab> 
```

**Question 2:**

```
PS D:\My Space\Assignments\Assignment2\html-lab> git push origin master
To ../html-remote
 * [new branch]      master -> master
PS D:\My Space\Assignments\Assignment2\html-lab> 
```

**Question 3:**

```
PS D:\My Space\Assignments\Assignment2\html-lab> cd ..
PS D:\My Space\Assignments\Assignment2> git clone html-remote html-copy
Cloning into 'html-copy'...
done.
PS D:\My Space\Assignments\Assignment2> cd html-copy
PS D:\My Space\Assignments\Assignment2\html-copy> git log --oneline
daba2fd Add next meeting heading
7db73cc Add home page
PS D:\My Space\Assignments\Assignment2\html-copy> 
```

---

**Result:** All three tasks were successfully executed to create a remote, push the commits to it and clone it into a new folder.

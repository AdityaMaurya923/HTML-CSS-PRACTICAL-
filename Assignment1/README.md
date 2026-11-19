# Assignment 1: Starting a Git Repository

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Starting a Git Repository using Git.

## 2. Aim

To start a Git repository for the lab folder and save work with commits.

## 3. Software / Tools Required

- Git (version control system)
- Terminal: PowerShell / Git Bash / Command Prompt
- Any text editor (VS Code)

## 4. Theory

**1. Git:** A version control system that records changes to files.

**2. Repository:** A folder tracked by Git, created with `git init`.

**3. Commands Used:**

- `git config --local` : Sets the name and email for this repository only.
- `git status` : Shows tracked and untracked files.
- `git add` : Moves a file to the staging area.
- `git commit -m` : Saves the staged changes with a message.
- `git log --oneline` : Lists commits, newest first.

## 5. Algorithm / Procedure

### Question 1: Create Repository and Set Name

1. Start.
2. Create the folder `html-lab` and go into it.
3. Run `git init`.
4. Set the name and email with `git config --local`.
5. Show them with `git config user.name` and `git config user.email`.
6. Stop.

### Question 2: First Commit

1. Start.
2. Create `index.html` with one h1 heading.
3. Run `git status` (index.html is untracked).
4. Run `git add index.html`.
5. Run `git commit -m "Add home page"`.
6. Stop.

### Question 3: Second Commit and Log

1. Start.
2. Add an h2 heading below the h1 in `index.html`.
3. Run `git add` and `git commit -m "Add next meeting heading"`.
4. Run `git log --oneline`.
5. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Folder = html-lab, name = Aditya Kumar Maurya, email = aditya.maurya@example.com

**Question 2:**

- File = index.html with one h1 heading, message = "Add home page"

**Question 3:**

- Added h2 heading, message = "Add next meeting heading"

## 7. Output

Terminal output is saved in `output.txt` and `output.png` of each task folder.

**Question 1:**

```
PS D:\My Space\Assignments\Assignment1> mkdir html-lab
PS D:\My Space\Assignments\Assignment1> cd html-lab
PS D:\My Space\Assignments\Assignment1\html-lab> git init
Initialized empty Git repository in D:/My Space/Assignments/Assignment1/html-lab/.git/
PS D:\My Space\Assignments\Assignment1\html-lab> git config --local user.name "Aditya Kumar Maurya"
PS D:\My Space\Assignments\Assignment1\html-lab> git config --local user.email "aditya.maurya@example.com"
PS D:\My Space\Assignments\Assignment1\html-lab> git config user.name
Aditya Kumar Maurya
PS D:\My Space\Assignments\Assignment1\html-lab> git config user.email
aditya.maurya@example.com
PS D:\My Space\Assignments\Assignment1\html-lab> 
```

**Question 2:**

```
PS D:\My Space\Assignments\Assignment1\html-lab> Set-Content index.html "..."
PS D:\My Space\Assignments\Assignment1\html-lab> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html

nothing added to commit but untracked files present (use "git add" to track)
PS D:\My Space\Assignments\Assignment1\html-lab> git add index.html
PS D:\My Space\Assignments\Assignment1\html-lab> git commit -m "Add home page"
[master (root-commit) 7db73cc] Add home page
 1 file changed, 9 insertions(+)
 create mode 100644 index.html
PS D:\My Space\Assignments\Assignment1\html-lab> 
```

**Question 3:**

```
PS D:\My Space\Assignments\Assignment1\html-lab> Set-Content index.html "..."
PS D:\My Space\Assignments\Assignment1\html-lab> git add index.html
PS D:\My Space\Assignments\Assignment1\html-lab> git commit -m "Add next meeting heading"
[master daba2fd] Add next meeting heading
 1 file changed, 1 insertion(+)
PS D:\My Space\Assignments\Assignment1\html-lab> git log --oneline
daba2fd Add next meeting heading
7db73cc Add home page
PS D:\My Space\Assignments\Assignment1\html-lab> 
```

---

**Result:** All three tasks were successfully executed to create a Git repository, set the local user details and save two commits.

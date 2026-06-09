---
---

--- Before Day-5 ---
I already knew .same as before
--- 

## Day-5 Checklist

- [ ] I have set up the basic Git configuration using `git config --global user.name "Your Name"`, `git config --global user.email "your.email@example.com"`, and set the default branch as main using `git config --global init.defaultBranch main`
- [ ] I know GitHub allows only one user account per person, so I have merged my accounts (IITM and personal) into a single unified account
- [ ] I understand the three states of a file in Git: working tree → staging → committed
- [ ] I can run the daily workflow commands `git status`, `git diff`, and `git log` and know what each shows
- [ ] I know how `.gitignore` works and how to use it to ignore files and folders that should not be pushed to the remote repository (e.g., `venv`, `__pycache__`, `.env`)
- [ ] I can make a commit: `git add` → `git commit -m "message"` → `git push`
- [ ] I know what `origin` and `main` are and can explain them in one sentence each
- [ ] I can set up SSH key authentication and push to GitHub without entering a password
- [ ] I can create an annotated tag (`git tag -a v0.1.0`) and push it to GitHub
- [ ] I can write a meaningful commit message (not "fixed stuff" or "final.py")

--- After Day-5 ---
I learned these things ...
1)Working Tree  →  Staging Area  →  Commit (Repository)
   (edit)         (git add)          (git commit)  
2)Working tree = writing a document ,
Staging = selecting pages to print(pre-commit checkpoint.like /git add filename/),
Commit = printing and saving a final copy(git commit -m "your message")-->changes are permanently recorded in Git history.
3)git status-->What’s going on right now(Which files are modified,Which are staged)
4)git diff-->What exactly changed(Line-by-line differences between.Working tree vs staging area)
5)git log — History of commits(List of commits,Author name & email)
6)git clone https://github.com/username/repo-name -->connect my local WSL folder to GitHub repo.
7)git add filename -->Add files you want to include in the commit
8)git push -->Send my commit to GitHub.
9)git add .  => . = current directory
10)Full workflow in order:
git add .
git commit -m "your message"
git push

11) origin = where GitHub repo is.
main = which branch inside your project
12)Setting up SSH lets you push to GitHub without typing your password every time.

13)Tag = label for a specific commit (like a release point)
Annotated tag = tag with message + metadata
Push = send that release marker to GitHub
14)git tag -a v0.1.0 -m "first release" (Create a tag)
15)git push origin v0.1.0 (Send tag to GitHub).Suppose You finish your app and want to mark it as version 0.1
---

--- Feedback (Suggestions for the TDS Team) ---
This is my feedback ...If it could be easier to learn
---

---
---

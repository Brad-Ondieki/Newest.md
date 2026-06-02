# GIT CHEAT SHEET 
---

## ⚙️ SETUP (ONE TIME)

git config --global user.name "Your Name"
git config --global user.email "[you@example.com](mailto:you@example.com)"

---

## 📁 START A PROJECT

git init
→ Create new repo locally

git clone <url>
→ Copy repo from GitHub

---

## 🔍 CHECK STATUS

git status
→ Shows changes in files

---

## ➕ ADD FILES

git add .
→ Add all files

git add filename
→ Add specific file

---

## 💾 SAVE CHANGES

git commit -m "message"
→ Save snapshot of project

Example:
git commit -m "Added login page"

---

## ☁️ SEND TO GITHUB

git push origin main
→ Upload code to GitHub

---

## ⬇️ GET UPDATES

git pull origin main
→ Download latest changes

---

## 🌿 BRANCHING (WORK SAFELY)

git branch feature-name
→ Create branch

git switch feature-name
→ Move to branch

git switch main
→ Go back to main

---

## 🔀 MERGE BRANCHES

git merge feature-name
→ Combine branch into current branch

---

## 🌐 REMOTE REPO

git remote -v
→ Check GitHub link

git remote set-url origin <url>
→ Change repo link

---

## ⚠️ COMMON ERRORS

❌ Permission denied (403)
→ You don’t own repo or no access

Fix:

* Get added as collaborator OR
* Fork repo OR
* Change remote

---

## 🔄 FULL WORKFLOW

clone → edit → add → commit → push

git clone <url>
git add .
git commit -m "update"
git push origin main

---

## 🧾 KEY TERMS

1. Repo = Project
2. Commit = Save point
3. Branch = Separate version
4. Merge = Combine code
5. Push = Upload
6. Pull = Download

---


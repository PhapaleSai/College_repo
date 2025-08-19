

1st Pratical 

# 1. Initialize a new Git repository

```bash
 git init
```
    
# 2. Add a remote repository (replace with your actual GitHub repo URL)
```bash
 git remote add origin https://github.com/your-username/your-repo.git
```

# 3. Verify the remote URL
```bash
 git remote -v
```

# 4. Add all files to the staging area
```bash
 git add .
```

# 5. Check the status of the working directory
```bash
 git status
```

# 6. Commit the staged changes with a message
```bash
 git commit -m "I have made some changes in demo.txt"
```

# 7. Push changes to the main branch of the remote repository
```bash
 git push origin main
```

That's a great mindset — documenting your learning like a step-by-step story is the best way to remember what you did!

Here's a **properly formatted README file for your Practical 2**, written in **simple, easy-to-follow language** (like you're 5 years old), including **step-by-step instructions**, explanations, and helpful notes.

---

# 🧑‍💻 Practical 2: Cloning, Branching, Pushing, and Pull Requests on GitHub

## 🧠 What I Learned

Today, I learned how to:

1. **Clone a GitHub repository** to my computer.
2. **Make changes** to files.
3. **Create a new branch** to work separately.
4. **Push changes** to GitHub from a new branch.
5. **Collaborate** using **Pull Requests** on GitHub.
6. **Sync changes** from GitHub to my computer.
7. **Clear old login information** using Credential Manager.

---

## 🔧 Steps I Did in Order

### ✅ 1. Cloned the Repository from GitHub

This brings the GitHub project from the internet to my computer.

```bash
git clone https://github.com/PhapaleSai/College_repo.git
```

👉 Now a folder named `College_repo` is on my computer.

---

### ✅ 2. Checked What's Inside

```bash
ls
cd College_repo/
ls
```

📁 This shows me all the files inside the project.

---

### ✅ 3. Created or Edited a File

I made or updated a file called `sai.txt` using the `vim` editor.

```bash
vim sai.txt
```

👉 Press `i` to **insert text**, type what you want, then:

* Press `Esc`
* Type `:wq`
* Press `Enter` to **save and quit**

---

### ✅ 4. Checked Git Status

This shows what files I changed or added.

```bash
git status
```

---

### ✅ 5. Committed My Changes

But wait! First, I **forgot to add** the file to the staging area. 😅
So I fixed that:

```bash
git add sai.txt
```

Then I saved my work with a message:

```bash
git commit -m "Added some content to sai.txt"
```

📝 This creates a snapshot of my changes.

---

### ✅ 6. Created a New Branch

I wanted to work on a separate line called `feature`.

```bash
git branch feature
git checkout feature
```

🔄 Now I'm working in the **feature** branch.

---

### ✅ 7. Added Remote Link (If not already added)

Just to make sure Git knows where my GitHub repo is:

```bash
git remote add origin https://github.com/PhapaleSai/College_repo.git
git remote -v
```

This shows the link to GitHub is working. 👍

---

### ✅ 8. Pushed My Changes to GitHub

I sent my changes from my local `feature` branch to GitHub.

```bash
git push origin feature
```

🚀 Now my changes are on GitHub, under the `feature` branch.

---

### ✅ 9. Created a Pull Request (on GitHub)

Now it's time to **ask** GitHub to bring my `feature` changes into the main project.

🖱️ Go to: [https://github.com/PhapaleSai/College\_repo](https://github.com/PhapaleSai/College_repo)

Then:

1. Click the **"Compare & Pull Request"** button near the `feature` branch.
2. Write a small **title and description** (e.g., "Added content to sai.txt").
3. Click **"Create Pull Request"**.
4. If you're ready to bring the changes into `main`, click **"Merge Pull Request"**.
5. Click **"Confirm Merge"**.

🎉 Done! Your changes are now part of `main`.

---

### ✅ 10. Sync Changes from GitHub to My Computer

First, switch back to the `main` branch on your local machine:

```bash
git checkout main
```

Then get the latest changes from GitHub:

```bash
git pull origin main
```

🌐 This updates your local `main` branch with everything from GitHub.

---

### ✅ 11. Important Note: Credential Manager

If someone else was logged in before, you might see their GitHub login.

To fix this:

1. Go to **Windows Search** > type `Credential Manager`.
2. Open it.
3. Go to **Windows Credentials**.
4. Find anything that says `git:https://github.com` and **remove it**.
5. Next time you push or pull, Git will ask for **your GitHub login**.

🔐 This keeps your GitHub account safe and correct.

---

## 📌 Summary of Commands Used

```bash
git clone <repo-url>
ls
cd College_repo/
vim sai.txt
git status
git add sai.txt
git commit -m "Added some content to sai.txt"
git branch feature
git checkout feature
git remote add origin <repo-url>
git remote -v
git push origin feature
git checkout main
git pull origin main
```

---

## 💡 Tips for Future Me

* Always make a **new branch** for new features or edits.
* Use **`git status`** often to check what’s happening.
* If login is wrong, fix it in **Credential Manager**.
* Don’t forget to **add** files before committing!
* Use **Pull Requests** to share and merge changes on GitHub.

---

Let me know if you'd like this in a downloadable format like `.md` or PDF!





